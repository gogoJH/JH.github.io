---
layout:     post
title:      "2019.04.23 Javascript Event loop"
subtitle:   "Sync, Async, Stack, Web APIs"
date:       2019-04-23
author:     gogoJH
header-img: img/post-bg-first.jpg
catalog: true
tags:
    - TIL
    - 개발일기
    - JS
---

<br>


## 오늘 한 일


> `Sync` , `Async` 개념을 알게 되었다.
> 
> 자바스크립트의 ***Event Loop*** 에 대해 이해하게 되었다.
> 
> ***Stack*** 과 ***Web APIs*** 작동원리에 대해 알게 되었다.

---

### Event Loop

![Event Loop](https://cdn-images-1.medium.com/max/800/1*m5M4NV495oH4ADvpnItnVQ.png)

***Java Script*** 는 싱글 스레드 기반의 언어라고 알고 있었고 처음에 ***동기 비동기*** 란걸 
신경 쓰지 않아도 되는 언어를 다뤘기 때문에 참 개념 자체가 생소했었다.
 
예전처럼 ***링크*** 하나 클릭하면 서버에서 HTML 문서를 던져주던 방식에선 그냥 당연히 기다려야하겠지 했었다.
근데 요즘처럼 ***Single Page*** 로 웹어플리케이션을 만들게 되고, 어떤 ***Event***에 따라 많은 데이터 변화가 끈김없이 일어나는 이런 환경에선 동기식의 
일처리 방식으론 사용자 친화적인 어플리케이션 개발을 할 수가 없는 지경이 되었을
거라 생각된다. 

### Coment



### 끝
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoibGF5b3V0OiAgICAgcG9zdFxudGl0bG
U6ICAgICAgXCIyMDE5LjA0LjIzIEphdmFzY3JpcHQgRXZlbnQg
bG9vcFwiXG5zdWJ0aXRsZTogICBcIlN5bmMsIEFzeW5jLCBTdG
FjaywgV2ViIEFQSXNcIlxuZGF0ZTogICAgICAgMjAxOS0wNC0x
NVxuYXV0aG9yOiAgICAgZ29nb0pIXG5oZWFkZXItaW1nOiAvaW
1nL3Bvc3QtYmctZmlyc3QuanBnXG5jYXRhbG9nOiB0cnVlXG50
YWdzOlxuICAgIC0gVElMXG4gICAgLSDqsJzrsJzsnbzquLBcbi
AgICAtIEpTXG4iLCJoaXN0b3J5IjpbLTU2MzE3MTI2NCwtMjA0
ODg5MTE4MCwtODQzNzg0NTIyLDkxOTM1MDM0MiwtNzQ5MTE3Nj
MwLDE1ODE0NDQ3NTQsNTg5NTkxMTc2LDE0MTY3OTYwMzIsLTE1
MTA3NjQwMzYsLTEyMzQ2NTExOTBdfQ==
-->