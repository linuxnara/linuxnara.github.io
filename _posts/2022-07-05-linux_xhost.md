---
title: "root로 실행시 unable to init server: 연결할 수 없습니다: 연결이 거부됨"
date: 2022-07-05 16:43
categories: ["linux"]
tags: ["linux", "xhost", "terminal"]
---

리눅스 xwindow에서 터미널 실행 후 윈도우 프로그램을 실행할때 로그인한 계정의 권한으로 실행 할 경우는 
문제가 없으나 root권한이나 다른 사용자의 권한으로 실행할 경우 해다 오류를 볼 수 있다

```
Failed to initialize Xfconf: Cannot autolaunch D-Bus without X11 $DISPLAY
```

sudo su - 등으로 root권한으로 로그인 할 경우 아래 명령을 터미널에 입력하면 root권한으로 프로그램을 실행 할 수 있다

```
$ xhost +
```
