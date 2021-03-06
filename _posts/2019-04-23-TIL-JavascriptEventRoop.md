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
 
예전처럼 ***링크*** 하나 클릭하면 서버에서 HTML 문서 던져주던 방식에선 그냥 당연히 기다려야하겠지 했었다.

근데 요즘처럼 ***Single Page*** 웹어플리케이션을 만들게 되고, 어떤 ***Event*** 에 따라 많은
데이터 변화가 끈김없이 일어나는 이런 환경에선 동기식의 일처리 방식으론 사용자 
친화적인 서비스를 할 수 없는 지경이 되었을거라 생각된다. 

![Why Non-Blocking](https://image.slidesharecdn.com/buildingnonblockingrest-151025131258-lva1-app6892/95/building-a-nonblocking-rest-api-in-less-than-30-minutes-11-638.jpg?cb=1445778858)
<br>
그래서 ***Javascript*** 는 `Web APIs`란 비동기영역을 만들어 두고, 데이터를 받아오는데 
시간이 걸리는 `메소드`들을 그쪽으로 보내둔다.

보내졌던 `메소드`들은 그 곳에서 실행을 마치게 되면, ***Callback Que*** 에 데이터를
보관하고 있다가 ***Stack*** 의 일처리가 끝난 후에 실행하게 된다. 

***Stack*** 에서 실행하는 메소드에서 `Web APIs`로 보내졌던 메소드의 데이터가 필요
하다면 콜백을 통해 동기적으로 사용할 수도 있다.

또한 좀 더 편한 사용을 위해서 ***Promise*** 가 등장하게 되고, ***Async await*** 가 등장하게 
된다. 

---
### Coment
처음에는 동기식 과 비동기식의 개념이 엄청 혼동 되서 머리가 아팠는데..

어느정도 이제 머리속에서 정리가 되어가는 느낌이다.

콜백 지옥을 맛보면 Async await가 얼마나 사랑스러운지 알게 되겠지 ..

### 끝
<!--stackedit_data:
eyJwcm9wZXJ0aWVzIjoibGF5b3V0OiAgICAgcG9zdFxudGl0bG
U6ICAgICAgXCIyMDE5LjA0LjIzIEphdmFzY3JpcHQgRXZlbnQg
bG9vcFwiXG5zdWJ0aXRsZTogICBcIlN5bmMsIEFzeW5jLCBTdG
FjaywgV2ViIEFQSXNcIlxuZGF0ZTogICAgICAgMjAxOS0wNC0x
NVxuYXV0aG9yOiAgICAgZ29nb0pIXG5oZWFkZXItaW1nOiAvaW
1nL3Bvc3QtYmctZmlyc3QuanBnXG5jYXRhbG9nOiB0cnVlXG50
YWdzOlxuICAgIC0gVElMXG4gICAgLSDqsJzrsJzsnbzquLBcbi
AgICAtIEpTXG4iLCJoaXN0b3J5IjpbNjA5MDU1MjRdfQ==
-->