---
layout : post
title : How to develop plugin for Android Studio_1
---

# How to develop plugin for Android Studio #1

## Reference links
> [Android Studio Plugin Development - Yalantis](https://yalantis.com/blog/android-studio-plugin-development/)
>
> [Android Studio plugin](https://plugins.jetbrains.com/docs/intellij/android-studio.html#configuring-intellij-platform-projects-for-android-studio-plugin-development)
>
> [안드로이드 스튜디오 플러그인 직접 만들어보기 - 차영호](https://academy.realm.io/kr/posts/android-studio-plugin-development/)
>
> [IntelliJ platform plugin SDK](https://plugins.jetbrains.com/docs/intellij/welcome.html?from=jetbrains.org)

## Downloads
> [Intellij IDEA Community](https://www.jetbrains.com/ko-kr/idea/download/#section=windows)
>
> [JDK Downloads](https://www.oracle.com/java/technologies/javase-downloads.html)

## Check
Matching Versions of the IntelliJ Platform with the Android Studio Version

> ### Intellij version of [Android Studio](https://developer.android.com/studio?gclid=CjwKCAjwg4-EBhBwEiwAzYAlsvsDYDr0rnSGoUBf2Adiy3oRjnedkwTg3if3U2Cyqyl6pFaoOiNC-RoC0dQQAvD_BwE&gclsrc=aw.ds)
>
>> Android Studio - Help - About
>>
>> Android Studio 4.1.1
Build #AI-<b>201.8743.12</b>.41.6953283, built on November 5, 2020
Runtime version: 1.8.0_242-release-1644-b01 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o
Windows 10 10.0
GC: ParNew, ConcurrentMarkSweep
Memory: 1237M
Cores: 8
Registry: ide.new.welcome.screen.force=true, external.system.auto.import.disabled=true
Non-Bundled Plugins: com.thoughtworks.gauge, org.intellij.plugins.markdown, com.intellij.marketplace
>
> ### Intellij version
>
>> IntelliJ - Help - About
>>
>> IntelliJ IDEA 2021.1 (Community Edition)
Build #IC-<b>211.6693.111</b>, built on April 6, 2021
Runtime version: 11.0.10+9-b1341.35 amd64
VM: Dynamic Code Evolution 64-Bit Server VM by JetBrains s.r.o.
Windows 10 10.0
GC: G1 Young Generation, G1 Old Generation
Memory: 750M
Cores: 8
Kotlin: 211-1.4.32-release-IJ6693.72
>
> ### Build Number Ranges
>> IC-211.6693.111
>>
>>Product ID (**IC for IDEA Community**, IU for IDEA Ultimate, RM for RubyMine, PY for PyCharm, etc.)
>>
>> Branch number (211)
>>
>> Build number in the branch (6693)
>> https://plugins.jetbrains.com/docs/intellij/build-number-ranges.html
>
>
