---
layout: post
title:  Connecting remote Github 원격저장소 연결하기
tags: [Github]
sitemap: true
---

<br><br>

Git에서는 로컬 저장소에서만 관리하던 소스코드를 원격 저장소에 올려 다른 사람들이 참고하고 사용활 수 있도록 하고 있습니다.
이를 통해 단순 공유뿐만 아니라, 협업, 더 나아가 **오픈소스**의 기여까지 작업할 수 있습니다.
이번 포스트는 원격저장소를 연결하는 방법을 소개하려고 합니다.

##원격(Remote) 저장소
리모트 저장소가 있는지 확인하거나 저장소 이름 확인
<pre><code> $ git remote </code></pre>

##원격저장소 연결하기
웹에서 repository를 생성한 후 repository 주소를 터미널에서 연결하고자 하는 로컬 저장소 폴더에 등록해준다.
<pre><code> $ git remote add origin [repo주소]</code></pre> 

##원격저장소 여러 개 연결하기
repository는 여러 개 등록가능하다. 대신에, 원격저장소의 이름을 다르게 설정해준다.
<pre><code> $ git remote add addorigin [다른 repo주소] </code></pre>

#####이 때는 푸시할 때 원격 저장소의 이름을 구분해준다.
origin 원격저장소에 push시 
<pre><code> $ git push origin master </code></pre>

addorigin 원격저장소에 push시
<pre><code> $ git remote addorigin master</code></pre>

##원격저장소 연결 확인하기
-v 옵션을 통해 연결한 저장소의 상태를 체크할 수 있다.
<pre><code> $ git remote -v</code></pre>

##원격저장소 clone하기
으원식이 바보 
원격저장소를 clone하고 싶은 위치로 이동한 뒤, 해당 상위폴더 위치에서 project-clone이라는 이름의 새로운 폴더를 만든다.

그리고 이미 로컬저장소가 연결되어 있는 원격저장소를 project-clone폴더에 clone 명령어로 내려받는다.
<pre><code> $ git clone [repo주소] project-clone </code></pre>

##fetch, merge, pull, and push

