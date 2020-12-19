---
layout : post
title : How to make layout checker for multiple resolutions
---

Requirements
1. Andorid application을 개발하고 있다
2. GUI 구현이 포함된 Application
3. SQE에 Release 하기 전에 기능 검증을 마쳐야 한다
4. 기능 검증에는 다양한 resolution 을 지원하는 layout이 있고, 관련 resource 들이 표시되는지 확인하고 싶다
5. [checkerframework](https://github.com/typetools/annotation-tools/) 이라는 tool 있는것 같다.


layout checker가 기존에 있지 않나?
[checkerframework](https://github.com/typetools/annotation-tools/) 에 대해서 공부는 필요하지만 layout checker 를 만드는 것은 당장은 필요 없는것 같다.

layout check 는 [espresso](https://developer.android.com/training/testing/espresso?hl=ko) 를 통해서 할수 있는 방향으로.
