---
layout : post
comments : true
title: Git blog 만들기_(3)
excerpt : "건물에 스킨 입히기"
permalink: /blog-3/
categories: 
 - _posts/git_blog/
tags:
  [Blog, Github]

last_modified_at: 2024-01-10
toc: true
toc_sticky : true

---

### 1. Jekyll 다운로드

이제 땅에 건물설계도까지 마무리 되었다. 이제 건물을 올리고 스킨을 입혀보자.<br>
<span style="font-size: larger;">[Ruby for Windows](https://rubyinstaller.org/downloads/)</span>로 접속해서 

![ruby_install](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/6fe7115a-eba2-4959-bf6a-4985daf17a32)

사진처럼 다운받아 주자.

다운받다보면 옵션선택하는 창이 나오는데 웬만하면 선택하자

다운이 끝났으면 다시 cmd창으로 돌아가자

<span style="background-color: black; color: yellow;">gem install bundle</span><br>
<span style="background-color: black; color: yellow;">gem install jekyll</span> 을 입력해주자.

아차차 라이 차차차

cmd경로를 바꿔줘야되는데 앞서 clone한 폴더로 가주자
폴더로 들어가면 README.md가 있을것이다. 거기서 빈곳에 마우스 오른쪽클릭하여 '터미널에서 열기' 하면
쉽게 경로로 열린다.

경로로 이동이 완료되어있으면 저것들을 설치해주자
설치가 끝났으면<br>
<span style="background-color: black;">jekyll new ./</span> 을 입력해주자.

![20240111_173822](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/e19d54f1-2647-47cb-b744-114336eed8c8)

그럼 위와 같은 오류가 날텐데 큰일난건 아니고 폴더 내 파일 다지우라는 뜻이다.
따라서 폴더내파일을 모두 지우고 다시 하자

![스킨1](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/e794221c-f6dc-4b32-b295-98408493bdd4)
그럼 폴더 내에 다음과 같은 파일들이 생긴다.

자 그럼 cmd창에


<span style="background-color: black; color:yellow; font-size: x-large" >bundle exec jekyll serve</span> 을 입력해주자.

이 명령어를 강조하는 이유는 자주쓰이기 때문이니 잘 기억하자
![저장1](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/75ac526b-a86e-4f41-8b9b-c7c14dbd6c4c)

그럼 막 뭐라뭐라 뜨면서 위처럼 생긴 글자가 뜬다.
저기서 컨트롤을 누른상태에서 http://127.0.0.1:4000/ 을 눌러보자
그럼 당신의 블로그가 뜰 것이다.

![블로그탄생1](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/9789fb1f-85bd-436a-9aec-6afe55b5f73c)

Q> 그럼 블로그 들어가려면 127.0.0.1:4000을 쳐야되요? <br>
A> 아니요 지금은 그냥 나혼자만 볼 수 있는 상태입니다.

Q > 수정버튼이나 글쓰기 버튼이 없는데 그럼 수정이랑 글쓰기는 어케해요!<br>
A> 그건 다음 글에서~~~


<h3>자 여기까지 땅을 만들고 건물도 세웠다 이제 건물에 스킨을 입혀보자</h3>