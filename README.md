# Quicklog

## 개요

Quicklog는 포스팅을 처음 시작하는 분들이나 어떻게 포스팅을 이어갈까 고민이 많으신 분들께 **쉽고 빠른 포스팅**을 위하여 AI를 이용하여 **다음 문장과 썸네일 이미지 등을 추천**해주는 서비스입니다.

<br>
<img width="660" alt="image" src="https://github.com/ssafyteam/ssafy-toy-project/assets/71087271/8988ce42-ab7c-46bd-ab52-ed31bba8b013">
</br>

## Table of Contents

- [1. 기획 및 설계](#1-기획-및-설계)
  - [1.1. 아이디어 배경 및 일정](#11-아이디어-배경-및-일정)
  - [1.2. UI 설계](#12-UI-설계)
  - [1.3. ERD 설계](#13-ERD-설계)
  - [1.4. 기술스택](#14-기술스택)
- [2. 주요 기능](#2-주요-기능)
  - [2.1. 포스팅 다음 문장 추천](#21-포스팅-다음-문장-추천)
  - [2.2. 썸네일 이미지 추천](#22-썸네일-이미지-추천)
  - [2.3. 포스팅](#23-포스팅)
  - [2.4. 피드](#24-포스팅)
  - [2.5. 인증](#25-인증)
- [3. CI/CD 구성 및 Commit Convention](#3-CI/CD-구성-및-Commit-Convention)
- [4. API Server](#4-API-Server)
  - [4.1. API Documentation](#41-API-Documentation)
  - [4.2. API Server Interaction](#42-API-Server-Interaction)
- [5. How to use](#5-how-to-use)
- [Contacts](#contacts)
  
<h2>Commit Convention</h2>

|이모지|태그|설명|
|:---:|:---:|:---:|
|sparkles|:sparkles: Feat:|새로운 기능을 추가하는 경우|
|zap|:zap: Update:|코드를 변경한 경우|
|fire|:fire: Remove:|코드나 파일을 삭제한 경우|
|bug|:bug: Fix:|버그를 고친 경우|
|memo|:memo: Docs:|문서를 수정한 경우|
|speech_ballon|:speech_balloon: Comment:|필요한 주석 추가 및 변경|
|twisted_rightwards_arrows|:twisted_rightwards_arrows: Merge:|브랜치 합병|
|lipstick|:lipstick: Design:|UI 디자인 변경|
|white_check_mark|:white_check_mark: Test:|테스트 추가, 테스트 리팩토링|
