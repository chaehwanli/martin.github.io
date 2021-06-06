---
layout : post
title : bad credential - mockito building
---

# github
[mockito](https://github.com/mockito/mockito)

# build
build on release/1.x
jdk - C:\Program Files\AdoptOpenJDK\jdk-8.0.292.10-openj9

# build error
{
  "message": "Bad credentials",
  "documentation_url": "https://docs.github.com/rest"
}

ref - [[GitHub] API 응답시에 "Bad credentials" 메시지 발생시 조치방법](https://frankler.tistory.com/52)

# git
[core]
	editor = \"C:\\Users\\chaeh\\AppData\\Local\\Programs\\Microsoft VS Code\\Code.exe\" --wait
[filter "lfs"]
	required = true
	clean = git-lfs clean -- %f
	smudge = git-lfs smudge -- %f
	process = git-lfs filter-process
[user]
	name = githubname
	email = githubemail

해결 못함. ㅜ.ㅜ