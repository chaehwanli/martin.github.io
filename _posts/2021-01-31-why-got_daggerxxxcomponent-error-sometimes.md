---
layout : post
title : Dependency Injection - 2 why I got DaggerXXXcomponent error sometimes?
---

I got errors about 'DaggerApplicationComponent' sometimes during implementations.

> Error Message
>> import com.example.di_sample_dagger.di.DaggerApplicationComponent;\
                                         ^ \
  symbol:   class DaggerApplicationComponent \
  location: package com.example.di_sample_dagger.di

If you get this error, it means you didn't declare the graph of Dagger classes.

Example
> @Component
public interface ApplicationComponent { \
    void inject(MainActivity mainActivity);
}

> public class MyApplication extends Application { \
    ApplicationComponent appComponent = DaggerApplicationComponent.create(); \
}

> public class MainActivity extends AppCompatActivity { \
    @Inject \
    MainActivityModelView mainActivityModelView; \
    @Override \
    protected void onCreate(Bundle savedInstanceState) { \
        ((MyApplication)getApplicationContext()).appComponent.inject(this); \
    } \
}

> class MainActivityModelView { \
}

If you not define 'Inject' method of 'MainActivityModelView' like uppder sample code, you will get this error.

> Error Message
>> import com.example.di_sample_dagger.di.DaggerApplicationComponent;
                                         ^ \
  symbol:   class DaggerApplicationComponent \
  location: package com.example.di_sample_dagger.di

To fix this build error, you need to add '@Inject' like belows.

> class MainActivityModelView { \
    @Inject \
    public MainActivityModelView() { \
    } \
}

