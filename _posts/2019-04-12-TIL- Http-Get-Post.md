---
layout:     post
title:      "2019.04.12 Http(Get Post)"
subtitle:   "Get, Post, Put, Delete"
date:       2019-04-12
author:     gogoJH
header-img: img/post-bg-first.jpg
catalog: true
tags:
    - TIL
    - 개발일기
    - JS
---


<br>
  
# 오늘 한 일

> 웹사이트를 접속하고 어떤 행동을 했을 때 발생되는 일들에 대해서 정리해보았다.

### Http

&nbsp; **WWW** 상에서 정보를 주고 받을 수 있는 **프로토콜**(규약)
  : &nbsp; 우리가 ***'어떤 사이트'***에 접속 한다고 했을 때 주소를 넣고 엔터를 치거나 링크를 <br>
  : &nbsp; 클릭 하거나 브라우저 상에서의 모든 행동들은 저마다의 명령어가 되어서 서버에서<br>
  : &nbsp; 어떤 형태로든 자료를 가져오게 된다. 그 과정에서 어떤 **규약**이 없다면 웹사이트마다 <br>
  : &nbsp; 그에 맞는 통신 방법을 다 알아야 웹사이트를 사용할수 있게 된다 .<br>
  : &nbsp; 예를 들어 한국 사람이 영어를 못하면 미국인과 ***대화***를 못하듯이 말이다. <br>

![웹사이트 접속](/img/post-http-get-post.png)

<br>


#### Get
1. &nbsp; 웹페이지의 `정보`만 가져올 때 사용하는 Http **메서드**

  &nbsp; 처음 사이트명을 넣고 엔터를 치면 우리의 똑똑한 **브라우저**는 해당 ***도메인주소***를 <br>
  &nbsp; 가지고 있는 서버에게 웹사이트 정보를 달라고 요청하게 된다. ***정보***를 가져오기만 <br>
  &nbsp; 할 때 우리는 Get 메서드를 통해 가져오게 된다.<br>
  &nbsp; 그럼 서버는 처음 보여줄 웹 페이지의 정보를 Response에 담아 보내준다. <br>

![웹페이지 다운](/img/post-http-get-post2.png)

<br>


#### Post

- &nbsp; 웹페이지의 상태변화를 위해 `정보`를 보내주고 새로운 데이터를 가져올 때 <br>
사용하는 Http **메서드**

&nbsp; 웹페이지에서 우리는 그 사이트에 가입을 하거나 로그인을 하거나 하는 상태에<br>
&nbsp; 변화가 일어나는 일들을 하게 되는데 그럴 땐 Post 메서드를 통해서 내가 한 행동을 <br>
&nbsp; 보내주고 되고 그 행동에 맞는 정보를 서버는 Response에 담아 보내준다.  <br>

![정보 수정](/img/post-http-get-post3.png)

<br>
---



#### coment
&nbsp; 아직 내가 확실히 알고 있는지 모르겠다. 혹여나 검색에 걸려 이 글을 보고 계신다면 <br>
&nbsp; 틀린 부분에 대해서 코멘트 달아주세요 ^^;;<br>
  

### 끝!
<!--stackedit_data:
eyJoaXN0b3J5IjpbLTEwODcyNDEyNzZdfQ==
-->