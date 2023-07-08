<div align="middle"> <h1>Eladin 도서 판매 서비스</h1> </div>
<div align="middle"> <img alt="엘라딘 로고" src="https://user-images.githubusercontent.com/47781507/210138012-8aaadec0-77b7-4e9d-9b22-c119396d3345.png" width=300> </div><br>

## 1. 서비스 개요

### 1-1. Topic

도서 구매 웹사이트

### 1-2. Service Name

Eladin(엘라딘)

### 1-3. Goal

기존 알라딘 사이트의 UX/UI 개선

### 1-4. Objective

기존 알라딘 사이트의 양탄자 배송에서 착안하여 사용자의 빠른 주문 및 배송이 가능하도록 단순화된 UI와 최소한의 기능 제공

### 1-5. Target User

복잡한 절차 없이 도서를 빨리 구매하고 싶은 사람

<br />

## 2. 팀원 소개

| 이름   | 담당 업무       |
| ------ | --------------- |
| 윤동주 | 팀장/프론트엔드 |
| 김유정 | 팀원/프론트엔드 |
| 김혜민 | 팀원/백엔드     |
| 서윤지 | 팀원/백엔드     |
| 이수빈 | 팀원/프론트엔드 |

<br />

## 3. 서비스 설명

<br />

### 3-1. 서비스 도메인

### https://eladin-lgurfdxfjq-du.a.run.app/ 

> ⚠ 서버가 내려간 상태입니다.

<br />

### 3-2. 테스트 계정

| Role  | ID                | PW       |
| ----- | ----------------- | -------- |
| Admin | cozyma@elice.com  | 12345678 |
| User  | python3@naver.com | python3! |

<br />

### 3-3. API 문서

### https://documenter.getpostman.com/view/18622149/2s8YRqjqCg

<br />

### 3-4. 서비스 주요 기능

#### 제품 등록, 장바구니 추가, 주문하기 등 쇼핑몰의 핵심 서비스 구현

1. 회원가입, 로그인, 회원정보 수정, 회원탈퇴 등 유저 정보 관련 **CRUD** 가능
2. JWT 토큰: 서버 DB가 아닌 프론트 단 **sessionStorage**에서 저장 및 관리
3. 카테고리에 따른 도서 목록, 도서 상세 정보 **조회** 가능
4. 장바구니 도서 조회, 도서 추가, 일부/전체 선택, 일부/전체 삭제 등 장바구니에서 **CRUD** 가능
5. 장바구니: 서버 DB가 아닌 프론트 단 **localStorage**에서 저장 및 관리
6. 장바구니에서 주문 목록 조회, 주문 완료 후 주문 정보 **조회 및 삭제** 가능
7. 관리자: 주문, 카테고리, 도서 **CRUD** 가능

<br>

### 3-5. 페이지 별 화면


|                                              |                                              |
| -------------------------------------------- | -------------------------------------------- |
| ![엘라딘_메인페이지](https://github.com/pansgraphy/Eladin/assets/95598010/412519b3-463f-4fda-8561-f0c04812d662) | ![엘라딘_회원가입](https://github.com/pansgraphy/Eladin/assets/95598010/875d7568-32ec-4492-a59f-7b0a79b87dd9) |
| 메인 페이지                                  | 회원가입 페이지                                |
| ![엘라딘_로그인](https://github.com/pansgraphy/Eladin/assets/95598010/bb402a4d-09ed-4278-b0ae-f313e4fecf4d) | ![엘라딘_카테고리별](https://github.com/pansgraphy/Eladin/assets/95598010/305fa6a0-b083-42ad-90d6-29929d7df692) |
| 로그인 페이지                                | 카테고리별 도서 리스트 페이지                         |
| ![엘라딘_도서 상세페이지](https://github.com/pansgraphy/Eladin/assets/95598010/3889ec0e-1b9a-461a-bf71-586be257ed2e) | ![엘라딘_장바구니](https://github.com/pansgraphy/Eladin/assets/95598010/934a9fef-01c3-41f9-8d0c-2949cd6240c9) |
| 도서 상세 정보 페이지                                | 장바구니 페이지                         |
| ![엘라딘_주문페이지](https://github.com/pansgraphy/Eladin/assets/95598010/54fcac81-226b-464f-a640-feba05aea0f1) | ![엘라딘_주문완료](https://github.com/pansgraphy/Eladin/assets/95598010/9f5bec17-d72b-4e64-94c7-219406364c6d) |
| 주문 페이지(장바구니 페이지 하단)                                | 주문 완료 모달                         |
| ![엘라딘_마이페이지](https://github.com/pansgraphy/Eladin/assets/95598010/870d5ac3-2709-4edd-8a47-c1dc0a8b36e1) | ![엘라딘_관리자페이지](https://github.com/pansgraphy/Eladin/assets/95598010/2327a3d7-6780-4825-9bfd-493badc87e3f) |
| 마이페이지                                | 관리자페이지                         |

<br />

## 4. 기술 스택

<!-- ![image](https://i.ibb.co/N34mXzy/image.png) -->

### 4-1. Language

|                                                                                                                   Javascript                                                                                                                    |
| :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://ymjm.synology.me/content/images/size/w2000/2023/03/javascript-vector-logo-yellow-png-transparent-javascript-vector-12-2.png" width="100px"/> |

### 4-2. FE

|                               Bulma                               |                                     LocalStorage                                     |                                                                                                                 SessionStorage                                                                                                                  |
| :---------------------------------------------------------------: | :----------------------------------------------------------------------------------: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
| <img src="https://bulma.io/images/bulma-logo.png" width="100px"/> | <img src="https://gyumin-kim.github.io/assets/img/local-storage.jpg" width="100px"/> | <img src="https://velog.velcdn.com/images/turnaroundwoo/post/dc91b462-5190-4ede-8754-4e01551ddd6c/image.jpeg" width="100px"/> |

### 4-3. BE

|                                                                                        Nodejs                                                                                        |                                                           Express                                                            |                                                 GCP                                                 |                                                                       MongoDB Atlas                                                                       |                                       Mongoose                                        |
| :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------: | :-------------------------------------------------------------------------------------------------------------------------------------------------------: | :-----------------------------------------------------------------------------------: |
| <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fk.kakaocdn.net%2Fdn%2Fd9ZeBr%2FbtrH5eJpnMq%2FPK52szk1xNqGtGHp7RJoi1%2Fimg.png" width="100px"/> | <img src="https://assets.website-files.com/61ca3f775a79ec5f87fcf937/6202fcdee5ee8636a145a41b_1234-p-500.png" width="100px"/> | <img src="https://www.logo.wine/a/logo/Google_Storage/Google_Storage-Logo.wine.svg" width="100px"/> | <img src="https://www.strongdm.com/hubfs/21126185/Technology%20Images/603c5eb831820c3ce6a8f057_603a1586fa052d17fc2a6929_MongoDBAtlas.png" width="100px"/> | <img src="https://avatars.githubusercontent.com/u/7552965?s=200&v=4g" width="100px"/> |

<br />

## 5. 구조

### 5-1. 인프라 구조

![엘라딘_인프라구조](https://github.com/pansgraphy/Eladin/assets/95598010/dcdb579c-ccba-49ec-982c-7e0dbae53751)
<br />

### 5-2. 폴더 구조

- 프론트: `src/views` 폴더
- 백: `src/views` 이외 폴더 전체
- 실행: **프론트, 백 동시에 express로 실행**

<br />

## 6. 실행 방법

### 6-1. 레포지토리를 클론하고자 하는 디렉토리에서 아래 명령어 수행

```bash
git clone https://kdt-gitlab.elice.io/sw_track/class_03/web_project/team4/eladin.git
```

### 6-2. 클론한 디렉토리에서 backend 디렉토리로 들어가 아래 명령어를 통해 Backend에서 필요한 module 설치

```bash
npm install
```

### 6-3. 최상위 폴더에 `.env` 생성 및 아래 내용 기입

```bash
MONGODB_URL=mongodb+srv://ming:dpffltm123@cluster0.soadvsp.mongodb.net/?retryWrites=true&w=majority
PORT=8000
```

### 6-4. Express 앱 실행

```bash
npm start
```
<br>

## 7. 버전

### 1.0.0
