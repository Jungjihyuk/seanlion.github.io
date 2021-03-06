---
layout:     post
title:      대학 축제 사이트를 만들어보자(2)
permalink: ux/11
description: 대학축제 사이트 기획 과정을 공유합니다.
date:       2017-10-05
summary:    대학 축제 사이트 기획 & 개발과정을 공유합니다.
category: 	서비스와 UX 습작
---

저번 글에는 사이트를 만들게 된 계기를 적어보았다. 

[지난 글 보기](https://seanlion.github.io/ux/7)

오늘은 구체적으로 기획과정을 공유해보도록 하겠다.(피드백은 환영이다!)

우선, 흐름을 따라가기 쉽게 진행 과정을 한번 더 리뷰!

* 사이트 정의
* 리서치
* 리서치 분석
* 정보 구조 짜기
* 화면 설계
* 개발 요소 정의
* 작업 분배하기
* 개발
* 테스트
* 런칭

- - -

## 사이트 정의(방향성)

일단 학교 축제 사이트라는 아이템은 정했는데 그 다음이 턱 막혔다.

<br>

<p align ="middle">	
 <img src="/images/question-mark.jpg" alt="alt text" width = "40%">
</p>

<br>

<h4><p align="center">‘사이트를 뭘 위해서, 어떻게 만들꺼지?’</p></h4>

<br>

그래서 우선 왜 이 사이트를 만들지, Why를 다시 떠올려보았다.

내 경험 상 학교 축제는 학기 중 가장 핫한 이슈 중의 하나이다. 학생들은 '가수는 누가 오는지', '어떤 이벤트들을 하는지', '축제 일정은 어떻게 되는지'에 대해 알고싶어한다. 그런 정보들은 대개 학교 내부에 있는 포스터, 게시판 등을 통하거나 관련 페이스북 페이지 등을 통해 제공된다. 요즘 웹 검색을 하면 일정이나 가수 라인업 등이 나오지만 정보가 혼재되어있는 경우가 많고 콘텐츠가 한정적인 경우가 많다. 즉, 관련 정보를 한 눈에 보는 것이 어렵다.

이렇다보니 정보를 모아볼 수 있는 사이트가 필요해졌다. 

<br>

<h4><p align="center">‘축제 관련 정보를 일괄적으로 명확하게 제공’</p></h4>

<br>

이게 사이트의 목표이고 내가 세운 Why였다.

목표에 대한 정량적인 지표도 구체적으로 잡아보고 싶었지만 경험이 없어 일단 페이지뷰 1000으로 잡아보았다.(사실 저때 서비스 기획에서 1000이 어느정도 숫자인지 감이 안 잡혔다..!)

- - -

## 설계요소 정의

Why를 다잡고나니 방향이 조금 보이기 시작했다. 그래서 How에 대한 고민을 해보기 시작했다.

<br>

<h4><p align="middle">어떻게 만들까?</p></h4>

<br>

1)	도구

사실 요즘 핫한 스케치를 써보고 싶었지만(제플린과 함께) 노트북이 맥이 아니었기에 무난한 PPT를 사용했다.(필자는 포토샵을 잘 못 쓴다.)

<br>

<p align ="middle">	
 <img src="https://sketchapp.com/images/social-twitter.jpg" alt="alt text" width = "70%">
</p>

{: refdef: style="text-align: center;"}
###### _이 녀석 조만간 써봐야겠다._
{: refdef}

<br>

팀에 디자이너가 없었기에 내가 기획하고 내가 디자인하고 개발에 참여도 해야 했다. 그렇기에 만든 기획안에서 디자인 요소를 고려하고 개발 할 때 디자인을 바로바로 적용하면서 수정했다.

2)	개발 환경 고려

기획안만 만드는 것이 끝이 아니고 직접 개발까지 해야했다. 그렇기에 최대한 내가 할 수 있는 개발 환경 안에서 좋은 기획안을 만들어야했다. 디바이스 환경도 고려해야 했고, 레이아웃도 어떻게 하면 좀 더 코드를 짜기 쉬운 레이아웃일지 생각해야만 했다. 또한 모르는 부분은 배워야했기에 학습 시간도 고려하여 개발 일정을 짜야만 했다. 구체적인 사항은 뒤에 개발 요소 정의 단계에서 이야기 해보겠다.

3)	정보 구조 (IA)

사이트를 설계하면서 가장 중요하게 들었던 생각은 ‘정보의 우선순위’였다.

무슨 정보를 제일 먼저 전달해야하고 어떤 순서로 임팩트있게 전달해야할까?

이것을 위해 정보 구조(Information Architecure, IA)설계를 준비했다. 

참고: 
[IA란?](https://m.blog.naver.com/PostView.nhn?blogId=mogni&logNo=70183062547&proxyReferer=https%3A%2F%2Fwww.google.co.kr%2F){:target="_blank" }

<br>

<p align ="middle">	
 <img src="http://cfile22.uf.tistory.com/image/236A154952D001D228BE61" alt="alt text" width = "100%">
</p>

{: refdef: style="text-align: center;"}
###### _이런걸 원했다._
{: refdef}

<br>

그 후, 원활한 구조 설계를 위해서 직접 서베이(리서치)를 진행했다.

- - -

## 리서치 진행

축제를 즐기러 오는 학생들을 대상으로 **관심있는 축제 정보**는 무엇인지에 대하여 온라인 서베이와 개인 인터뷰를 진행했다. 서베이는 총 3일 동안 진행했으며 학교 대나무숲 페이지, 지인을 대상으로 요청했다. 우리 학교 학생들과 타 대학교 학생들을 포함해 총 86명이 참여해줬다. 개인 인터뷰는 학교 학생 2명과 함께 간략하게 진행했다.

밑의 표는 당시 했던 서베이 항목 겸 질문이다.

<br>

<p align ="middle">	
 <img src="/images/kaufest_table.png" alt="alt text" width = "100%">
</p>

- - -

## 리서치 결과

결과를 분석하다 보니 몇 가지 흥미로운 점이 보였다.

#### 1.학년 분포

**1학년이 40%로 1위를 차지했다.** 아마 고학년보단 1학년들이 축제에 큰 기대(?)를 하는지라 이런 결과가 나온 것 같다.
타학교는 4학년이 반 이상 차지했다. (아무래도 조사자의 나이에 영향을 받은 것 같다.)


#### 2.콘텐츠 분포


콘텐츠 측면에서는 우리학교 학생과 타 학교 학생이 관심있어하는 정보가 상이했다.

먼저 우리학교 학생들의 관심사는 다음과 같았다.

1.주점 메뉴 및 가격

2.축제 프로그램

3.축제 일정

4.가수 라인업 

5.축제 동선

6.학과별 행사  

의외로 가수 라인업에 대한 우선순위는 상대적으로 낮았는데 아마 자기 학교 축제다보니 전반적인 일정이나 프로그램에 더욱 관심을 두지않았나 싶다.

개인 인터뷰의 답변 또한 서베이 분포 결과와 대부분 일치하는 모습을 보였다. 

반면 타 학교 학생들의 관심사는 다음과 같았다. 


1.가수 라인업

2.축제 일정

3.프로그램 

4.학교 오는길

5.주점 위치

6.대중교통 시간 

아무래도 다른 학교다보니 가수 라인업에 따라 참여 유무가 갈리는 것 같았고 찾아오는 길, 막차 시간에도 관심을 많이 두었다.

#### 3.건의 사항

서베이와 개인 인터뷰를 통해 사이트에 대한 아이디어와 요구사항을 받을 수 있었다. 아이디어를 정리해보자면 다음과 같다.

1)	실시간으로 축제에 대한 불만사항이나 건의사항을 올릴 수 있는 창

2)	간단한 구조로 중요한 것만 전달

3)	모바일로 주점 음식 주문

리서치를 통해 정보의 우선순위를 매겨볼 수 있었고 기능에 대한 아이디어도 얻을 수 있었다. 또한 이후 리서치 결과를 바탕으로 간략한 스케치를 하며 페이지의 미래 화면을 그려보기도 하였다.


쓰다보니 글이 너무 길어진 것 같다. 이 다음엔 정보 구조(IA) 설계를 진행했는데 IA 설계는 다음 글에서 이어서 얘기하도록 하겠다!
