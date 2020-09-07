---
layout: post
title:  Ubuntu에서 Logitech 쉽게 유니파잉하기
comments: true
categories: [environ, Ubuntu]
tags: [environ, Ubuntu]
sitemap :
  changefreq : daily
---

## Ubuntu에서 Logitech 쉽게 유니파잉하기
> 저 같은 경우는 기존의 마우스에 사용하던 동글을 잃어버려서 방법을 찾아보다가 유니파잉이라는 것을 알게되어 글을 쓰게 되었습니다. 
 
### 보통 유니파잉을 사용하는 이유는
1. 기존의 마우스 동글을 잃어버렸을 경우 
2. 블루투스 연결이 잘 되지 않을 경우 

위와 같은 문제를 해결하기 위해 로지텍 유니파잉을 통해 마우스를 사용가능합니다.

### 저는 두 가지 해결책을 소개하려고 합니다. 
먼저 말씀드리는 것은 편리한 방법입니다.
~~~
sudo add-apt-repository ppa:daniel.pavel/solaar
sudo apt-get update
sudo apt-get install solaar 
~~~
Ubuntu 터미널에서 위의 코드를 입력하면 설치 후 실행하면 사용가능합니다.

두 번째 방법은 **Mac과 Windows**에서만 사용가능합니다.
[Logitech 홈페이지](https://support.logitech.com/ko_kr/article/unifying-pairing)을 클릭하셔서 링크를 타고 가셔서 설치방법을 따르시면 될 것 같습니다.
