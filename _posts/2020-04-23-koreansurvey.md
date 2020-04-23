---
layout: post
permalink: /koreansurvey/
title: "대국민 질문 (외주 프로젝트)"
image: /assets/koreansurvey/01-main.png
description: "사회 이슈와 관련된 질문에 대한 유저들의 투표를 받는 간편 설문조사 웹앱입니다."
position: "Back-end Developer"
project-date: "2020.03 ~ 2020.04"
---

_**[배포 주소 >](https://koreansurvey.com){: target="\_blank"}**_

---

## About

사회 이슈와 관련된 질문에 대한 유저들의 투표를 받는 간편 설문조사 웹앱입니다. 문항에 투표한 사람의 성별, 지역, 연령을 분석하여 그래프로 결과를 출력하여 보여줍니다. 어드민 대시보드도 함께 제작했습니다.

### Main features

- 사용자들은 운영자가 올린 질문에 대해 투표합니다.
- 운영자 및 사용자들은 문항에 투표한 사람의 성별, 지역, 연령을 분석한 그래프를 볼 수 있습니다.
- NICE 인증을 사용하여 회원 가입합니다.
- 사용자는 원하는 질문이 없으면 질문신청을 할 수 있습니다.

#### admin dashboard

- 어드민 대시보드는 운영자만 접근 가능합니다.
- 질문과 그 질문에 맞는 두 가지의 선택지를 생성할 수 있습니다. 각 선택지는 png 파일과 gif 파일 등의 이미지를 업로드 할 수 있습니다.
- 질문을 생성한 이후 배포하기 전까지 자유롭게 수정과 삭제를 할 수 있습니다. 배포 이후에는 배포를 취소하기 전까지 수정과 삭제가 불가능합니다.
- 사용자가 신청한 질문을 확인할 수 있습니다.

### Stack

- JavaScript / ExpressJS / Node.js / MySQL / Sequelize.js / <br/>
  AWS(S3, CloudFront, ELB, Route53, Auto Scaling, RDS, EC2)

---

## Works

예상 사용자 만 명을 견딤과 동시에 합리적인 비용의 AWS 아키텍처 설계.

RDS 비용 절감을 위해 AWS RDS Aurora를 사용한 서버 리스 데이터베이스 구축.

만 명의 예상 사용자를 감당하기 위해 AWS Elastic Load Balancing과 Auto Scaling group 사용.

서버 관리의 부담을 줄이기 위해 AWS S3와 CloudFront를 사용해 https 프로토콜 웹사이트 배포.

사용자 데이터 보호를 위해 휴대폰 번호를 암호화하여 데이터베이스에 저장.

---

## Service GIF

<br/>

<center><img src="/assets/koreansurvey/02-browser.gif"><center/>

<br/>

<center><img src="/assets/koreansurvey/03-phone.gif"><center/>
