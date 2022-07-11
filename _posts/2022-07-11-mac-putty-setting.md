---
title: "osx  putty 접속시 한글 깨지는 현상 해결"
date: 2022-07-11 11:03
categories: ["macos"]
tags: ["linux", "macos", "putty"]
comments: true
---

putty translation설정이 utf-8로 되어 있어야 함.

```
# export declare LANG="ko_KR.UTF-8"
```