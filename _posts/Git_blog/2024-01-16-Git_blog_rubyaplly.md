---
layout : post
comments : true
title: Git blog 만들기_(4)
excerpt : "건물에 스킨 입히기"
permalink: /blog-4/
categories: 
 - _posts/git_blog/
tags:
  [Blog, Github]

last_modified_at: 2024-01-24
toc: true
toc_sticky : true

---

### 1. 옷가게 가기

건물까지 세웠으니 스킨을 입혀보자. 우선 스킨을 입히려면 옷가게에 가야된다.<br>

[옷가게](https://jekyllthemes.io/free) <- 이주소를 클릭 해주자 그럼 다음과 같은 화면이 나타날것이다.


![옷가게](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/75f3c5a7-236d-4362-b9e8-4db91ae671db)


옷가게 들어왔으니 자기가 맘에 드는 옷을 고르면됩니다. 

저 같은 경우는 Not Pure Poole 테마를 골랐습니다.

![옷가게2](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/34b0b336-2624-426c-8c13-16337c3d15fe)

들어가서 다운로드를 클릭해줍니다.

압축 해제 후 우리가 모든 파일을 지웠던 폴더 안에 붙여넣기 합니다.<br>
※ 붙여넣기 하시겠습니까? 해도 놀라지말고 붙여넣으세요


### 2.Jekyll 테마 설치
저도 이부분은 잘 모르는데 다운 받은 테마를 설치하기에 앞서 초기화를 해야된다고 합니다.

따라서 다음과 같은 파일들을 삭제해주세요(없으면 안해도됨)


* #### `Gemfile.lock `
* #### `.travis.tml `
* #### `_posts 폴더삭제 `
* #### `docs 폴더삭제`
* #### `.github/workflows/pages-deploy.yml.hook 파일을 제외한 나머지 파일 삭제`
* #### `.github/workflows/pages-deploy.yml.hook 파일명을 pages-deploy.yml로 변경`


이제 다시 우리가 파일 옮긴 폴더로 가서(경로로 가서) cmd창을 열자<br>

cmd 창에<br>
<span style="background-color: black; color: yellow;">bundle install</span>을 치자

![bundle install](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/71f147f6-8927-4227-8348-65ff02215d28)
* 저거 가린건 개인 컴퓨터 이름이라 가림

여튼 다음과 같이 되고 로컬서버를 시작하는 문구인<br>
<span style="background-color: black; color: yellow;">bundle exec jekyll serve</span>를 입력하면!!!



<h3>오류가 뜬다!!!!!</h3>

![골치](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/92f727e2-356d-4ddb-9fab-f05f3262aa60)


당황하지 마시라

거의 8할 이상이 <h3>Webrick</h3>때문인데

![webrick 오류](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/8bcb5257-5931-4654-b348-a81ff455b8fc)


해결법은 초 간단하다.

<span style="background-color: black; color: yellow;">bundle add webrick</span>만 입력해주면 끝

![오류추가](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/53778f89-f754-40b5-991c-420855ec1ded)

그럼 위사진 처럼 설치가 되고
<span style="background-color: black; color: yellow;">bundle exec jekyll serve</span>을 다시 입력하면!!!!


![실행](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/e8258515-d0b6-4fd6-96b2-63f83e4b1495)

따란 스킨을 입힌 화면이 나타난다.

![초기화면](https://github.com/wanjinchoi/truewan.github.io/assets/100115901/3deff163-b770-45af-b6b0-ffa0dd6eec35)


<h3>자 이제 스킨을 입혔다. 이제 내몸에 맞게 수정해보도록 하자  </h3>