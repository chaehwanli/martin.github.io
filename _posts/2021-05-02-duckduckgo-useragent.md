---
layout : post
title : duck duck go - user agent change
---

# github
[duckduckgo android](https://github.com/duckduckgo/Android)

# how to change user agent of duck duck go?
> The [daum](https://www.daum.net) page is displayed as "desktop mode" when I use duckduckgo android what is built from github source.
> the page is displayed as "mobile page" if the changed user agent is used like below.
> duckduckgo android 를 빌드하고 사용했을때, daum page가 desktop page로 표시되는 부분을 아래 useragent 관련 코드에서 Application 정보를 지웠더니 mobile page로 표시 되었다.

> path
>> \duckduckgo\app\src\main\java\com\duckduckgo\app\browser\useragent\UserAgentProvider.kt

> before
>> private val applicationComponent = "DuckDuckGo/${device.majorAppVersion}"

> after
>> private val applicationComponent = null