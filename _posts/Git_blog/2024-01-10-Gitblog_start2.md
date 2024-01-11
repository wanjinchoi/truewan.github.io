---
layout : post
comments : true
title: Git blog 만들기_(2)
excerpt : "땅을 만들었다. 건물을 세워보자"
permalink: /blog-2/
categories: 
 - _posts/git_blog/
tags:
  [Blog, Github]

last_modified_at: 2024-01-10
toc: true
toc_sticky : true

---


### 1. 경로이동 부터

&nbsp;&nbsp;&nbsp;자 앞서서 땅이라고 표현한 레퍼지스토리를 만들었다. 그럼 건물을 세워보자.<br>
일단 내가 만든 Git을 내 로컬로 가져와야된다.

요즘은 긴설명보단 요약이니깐 요약간다.

1. clone할 폴더를 만든다.
2. cmd 창을 관리자권한으로 실행한다.
3. cd 해서 경로를 가져온다.
4. git 에서 경로에 clone한다.

사진으로 설명해주겠다.
![cmd 실행](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/a5b31872-c628-4a4e-a483-7c4b358d69ad)


"난 cmd가 뭔지도모르고, 관리자권한 실행도 모르겠다." 위 사진처럼 하자.<br>
(다른방법)<br>
-> window key(ctrl 옆에 있는거)랑 R키를 같이 눌러준다.<br>
-> cmd 검색한다.

그럼 여기서 궁금증이 풍부한 사람은 다음과 같은 질문을 할 것이다.

Q.> 왜 관리자 권한으로 실행해야되는데요?<br>
A.> 진짜 쉽게 얘기하자면 "그래야 에러 안남" 인데 더 자세하게 말자하면 "시스템 설정이나 파일에 대한 권한을 변경하거나 관리하기 위해서" 이다. 




난 바탕화면에 clone할 폴더로 blog라고 만들었다. 그럼 경로를 가져와보자.(잠깐)<br>

Q. 경로를 왜가져와야 되는데요?<br>
A. 컴퓨터에게 "여기다가 clone할거야"라고 알려주기 위함이다.<br>


<figure class="half">  
<a href="link"><img src="https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/673ec5c4-4e39-49d5-87c5-c59aadfefb8e"></a>  
<a href="link"><img src="https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/e5b60702-89e6-4a76-a719-fe321d7a66cf"></a>
</figure>


위 이미지를 자세히 보면 앞선 이미지는 경로를 가져오는법<br>
두번째 이미지는 cmd창으로 경로에 접근하는 법이다.<br>
방법은 "cd 경로" (cd 입력하고 한칸띄운다음 경로를 복사 붙여넣기) 하면된다.

이제 git에 업로드하기 위해 git을 clone 해보자

![git clonde](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/95a9d876-6de9-4e5a-a12d-05c8b749e7ee)

일단 내 Git에서 code 초록버튼을 누른다. 그럼 사진과 같은 팝업창이 나타나는데 네모두개가 겹쳐져있는 버튼을 누른다(복사버튼이다)

그런후 cmd창으로 돌아와 git clone 마우스 오른쪽 버튼을 클릭한다.


![git clonde2](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/45d46f43-2c5a-4311-b161-934670593466)


그럼 위 사진 처럼 되는데 엔터키를 눌러주자 



![git clone](https://github.com/wanjinchoi/wanblog.github.io/assets/100115901/8f8cc533-6016-4479-8ae8-0b78e719e5d9)

그렇게 되면 내가 만든 폴더에 git이 복사가 됐다.




