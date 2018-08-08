---
title: "Hugo Static Site Generator"
date: 2018-08-08T07:47:13-07:00
draft: false
tags: [hugo, blog, todo]
---

Facebook은 너무 개인 적이고 Instagram에 올릴 사진들은 요즘 찍지 않아서, 블로깅 툴을 검색하다 옛 감성 풀풀 풍기는 Static Site Generator인 Hugo를 발견하다.

- [Good Hugo tutorial](https://www.youtube.com/watch?v=qtIqKaDlqXo)
- [Host on Github](https://gohugo.io/hosting-and-deployment/hosting-on-github)

Hugo로 생성된 페지를 Github에 호스팅 하는 것의 핵심은

- Github는 `<USERNAME>.github.io`에 프로젝트를 웹 root로 한다

는 것을 이용해서 같은 이름의 프로젝트에 Hugo로 생성되는 public 폴더를 업로드 하는 것이다. Hugo 프로젝트 폴더도 Github에 올려두면 어느 장소에서건 체크아웃해서 작업할 수 있다.

현재 까지 단점은

- 포스팅 하나 업데이트를 하더라도 컴파일이 필요하다.

인데, Hugo 스트럭쳐가 파악되면 content 폴더에 md 파일만 업로드 하는 것으로 해결 될지도 모르겠다고 잠깐 생각했지만 아닐 듯, tag셍성이나 achieve에 링크를 만들려면 파일 업로드만으로 안될 것이 거의 확실. 