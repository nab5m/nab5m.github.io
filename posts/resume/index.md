---
layout: resume
title: 이력서
description: nab5m의 발전소
created: 2020-02-22
category: Resume
---

### 2020년 나를 데려갈 회사는 어디일까?
<br/>
<hr/>

# <연혁>

## 2020 (스물 두 살)
- 개인 프로젝트: 노래일기
- 구직 활동

## 2019 (스물 한 살)
- 독학사 컴퓨터과학과 1, 2단계 통과
- React와 Django 공부
- w-stone 소개 홈페이지 제작 (상호 협의 실패로 도메인 등록X)
- 개인 프로젝트: 북마크
- 개인 프로젝트: 노래일기
- GTQ 포토샵 1급

## 2018 (스무 살)
- 토익 920점

## 2017 (고3)
- 수능 공부 매진

## 2016 (고2)
- 전공 서적 : 난 정말 Java를 공부한 적이 없어요
- 동아리 발표회 2인 프로젝트 참여 (스타크래프트 RDP 공격 실습)
- 신입생 C언어 교육 조교로 참여
- 선린 장학생 해외연수(베트남)
- 동아리 주최 해킹대회 문제 출제 (안티 디버깅)
- 웹 기능반 소속 (jQuery, bootstrap, Php-Laravel)
- 교내 디지털콘텐츠 경진대회 동상

## 2015 (고1)
- 해킹 동아리 Layer 7 가입
- 교내 프로그래밍 경진대회 동상
- 전공 서적 : 윤성우의 열혈 C++ 프로그래밍
- 전공 서적 : 리버싱 핵심원리
- 보안 멘토링 프로그램 (DLL Injection 프로젝트)

## 2014 (중3)
- 선린 인터넷고에 다니기 위해 부모님 수 차례 설득

## 2013 (중2)
- 정보보안 전문가의 꿈을 갖게됨
- 광화문 교보문고에서 윤성우의 열혈 C프로그래밍 책구매
<br/><br/>
<hr/>

# <포트폴리오>

## 노래 일기

{% include_relative music_diary_gallery.html %}

**Demo:**<br/> 
&nbsp;&nbsp;[music-diary](http://ec2-15-165-171-10.ap-northeast-2.compute.amazonaws.com/){:target="_blank"} <br/>

**Repository:**<br/>
&nbsp;&nbsp;[#front-end](https://github.com/nab5m/music-diary-frontend){:target="_blank"}&nbsp;&nbsp;&nbsp;&nbsp;[#back-end](https://github.com/nab5m/music-diary-backend){:target="_blank"} <br/>


**Description:** <br/> 
&nbsp;&nbsp;코인 노래방에 가는 것을 좋아해서 <mark>노래방에 가면 부르는 노래 목록을 정리</mark>해보고 싶었습니다. 새로운 노래 한 곡을 완곡했을 때의 기분이 좋아 <mark>어제 오늘 어떤 노래를 불렀는지</mark> 어플리케이션을 통해 알고 싶었습니다. 디자인은 모바일 Sns 어플리케이션의 디자인을 참고했습니다. 아이콘과 초기 화면에 들어가는 사진은 <mark>일러스트</mark>와 <mark>포토샵</mark> 프로그램으로 만들었습니다. React Native 웹 뷰를 사용해 하이브리드 어플리케이션을 제작해보는 것으로 목표를 설정하고 만들기 시작했습니다. 프론트엔드 개발은 <mark>React.js</mark>, 백엔드는 <mark>Django</mark>를 사용했습니다. mobile-first 사이트이므로 모바일 환경에서 보면 훨씬 깔끔합니다. PC에서는 F12버튼을 눌러 화면 크기를 조절해주세요! 노래 목록을 CRUD하는 기능을 추가했습니다. Staff <mark>권한</mark>이 있는 계정과 Kakao 로그인한 사용자만 api를 요청할 수 있습니다.

**Progress:** <br/>
&nbsp;&nbsp;AWS EC2 인스턴스에서 gunicorn과 nginx를 통해 배포했습니다. 일기 생성 및 수정 화면을 어떻게 구성할지 생각중입니다. 일기 CRUD 기능을 구현하고 달력 뷰를 완성할 계획이 있습니다.

**Difficulties:** <br/>
&nbsp;&nbsp;카카오 Rest api로 <mark>로그인 토큰</mark>을 받고 이것을 어디에 저장해야할지 선택하는 데 어려움을 느꼈습니다. React(3000번 포트)와 Django(8000번 포트) 서버가 다른 위치에 있어 ajax 요청할 때마다 세션이 달라지는 문제가 있었습니다. <mark>CORS 문제</mark>임을 알아내는 데 시간이 걸렸습니다. 답을 찾는 동안 다양한 대안을 생각해보았지만 클라이언트 측에 <mark>쿠키로 저장하는 것은 보안상 위험</mark>하다 생각해 구현을 중지했습니다. 검색을 통해 ajax 요청 시에 credentials 파라미터를 추가하는 방법을 찾았습니다.

## W-stone

{% include_relative wstone_gallery.html %}

**Demo:**<br/> 
&nbsp;&nbsp;[w-stone.herokuapp.com](https://w-stone.herokuapp.com/){:target="_blank"} <br/>

**Description:** <br/>
&nbsp;&nbsp;스터디 사람의 소개로 <mark>신생 회사 소개 페이지</mark>를 만들어 봤습니다. 빠른 개발을 위해 html 무료 템플릿을 베이스로 하고 소개말, 공지사항, 지도 콘텐츠를 추가했습니다. <mark>Django Admin</mark> 인터페이스를 활용하여 <mark>네비게이션 목록이나 콘텐츠의 노출 유무를 손쉽게 수정</mark>할 수 있습니다. 상호 협의가 원활히 이루어지지는 않아서 도메인을 가지고 배포하지는 않았습니다.