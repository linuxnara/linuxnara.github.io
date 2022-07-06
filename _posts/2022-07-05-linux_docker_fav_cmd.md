---
title: "docker 컨테이너 내부 shell 실행"
date: 2022-07-05 17:00
categories: ["linux", "docker"]
tags: ["linux", "docker"]
comments: true
---

container id 확인
```
$sudo docker ps -a 
```

현재 실행되고 있는 컨테이너의 쉘 실행
```
$ sudo docker exec -it <docker container id> /bin/bash <--이미지명 아님
```