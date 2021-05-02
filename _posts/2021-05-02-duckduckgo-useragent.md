---
layout : post
title : duck duck go - user agent change
---

# github
[duckduckgo android](https://github.com/duckduckgo/Android)

# how to change user agent of duck duck go?
> path
>> \duckduckgo\app\src\main\java\com\duckduckgo\app\browser\useragent\UserAgentProvider.kt

> before
>> private val applicationComponent = "DuckDuckGo/${device.majorAppVersion}"

> after
>> private val applicationComponent = null