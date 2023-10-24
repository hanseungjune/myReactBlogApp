# myReactBlogApp - Blog Web Page

<br/>

## 🗓️ 실질 개발 기간(재배포 프로젝트)

- 2023년 9월 24일 ~ 2023년 10월 16일
  
<br/>

## 🧭 목적

- fireBase를 통해서 CRUD 기능 수행 목적
- 블로그 화면 및 기능 구현 목적

<br/>

## ✅ Task

### ❗필수 요구 사항

- ⭕ CRUD 기능 구현
- ⭕ 사용자 인증 및 권한 관리
- ⭕ 라우팅과 페이지 구성

### ⭐ 앱 구조

- (create-react-app) SPA

### 📃 상태 관리

- Context API
- 권한관리
- 테마관리(다크모드 기능)

### 🎇 스타일 및 애니메이션

- CSS 사용 (BEM 구조)
- 캐러셀 transition

### 💬 배포

- Firebase

### 🎁 컴포넌트

- 헤더, 푸터, 리스트, 폼, 캐러셀

### ⚕️API

- firebase의 firestore를 이용한 실시간 데이터 생성
- firebase auth를 이용한 사용자 인증 개념

### 📌 사용 스택

- React
- typescript
- Firebase(로그인, 보안, 통신)
- CSS

### 🤓 기타 학습 개념

- 폴더 구조
- CRA 이용 프로젝트 세팅
- React hooks(useEffect, useState, useContext, useCallback)
- React-router-dom 라우터

## 구현 기능

### 🖥️ 공통 페이지

1. ⭕ 로그인 페이지 
    - Firebase Auth 사용자 인증 기본 로그인
2. ⭕ 메인페이지
    - 최신 글 목록, 특징 콘텐츠 보여주기
3. ⭕ 글 목록 페이지
    - 블로그에 작성된 모든 글의 목록 보여주기
    -해당 글 선택시 상세페이지 이동
4. ⭕ 글 상세 페이지
    - 글 제목, 내용, 작성자, 작성일 등 표시
5. ⭕ 글 수정 페이지(CRUD)
6. ⭕ 카테고리 메뉴
7. ⭕ 사용자 프로필 페이지(Velog,Medium st)

## 그 외 기능
- ⭕ 다크모드(Context API)
- ⭕ 내가 쓴 글 필터링
- ⭕ 댓글 CRUD

<br/>

## 🎖️ Members

<table border>
  <tbody>
    <tr>
      <td align="center" width="200px">
        <img width="100%" src="https://avatars.githubusercontent.com/u/92035406?v=4"  alt=""/>
        FE.<br/>
        <a href="https://github.com/hanseungjune">
          <img src="https://img.shields.io/badge/한승준-000000?style=flat-round&logo=GitHub&logoColor=white"/>
        </a>
      </td>
     </tr>
  </tbody>
</table>

<table border>
  <tr>
    <td><img src="./회원가입 및 로그아웃.gif" alt="회원가입 및 로그아웃"/></td>
  </tr>
  <tr>
    <td align="center">회원가입 및 로그아웃</td>
  </tr>

  <tr>
    <td><img src="./게시글 및 댓글 기능.gif" alt="게시글 및 댓글 기능"/></td>
  </tr>
  <tr>
    <td align="center">게시글 및 댓글 관련 기능</td>
  </tr>
</table>

### 🌳 File Tree

```
📦src
 ┣ 📂components
 ┃ ┣ 📜Carousel.tsx
 ┃ ┣ 📜Comments.tsx
 ┃ ┣ 📜Footer.tsx
 ┃ ┣ 📜Header.tsx
 ┃ ┣ 📜Loader.tsx
 ┃ ┣ 📜LoginForm.tsx
 ┃ ┣ 📜PostDetail.tsx
 ┃ ┣ 📜PostForm.tsx
 ┃ ┣ 📜PostList.tsx
 ┃ ┣ 📜Profile.tsx
 ┃ ┣ 📜Router.tsx
 ┃ ┗ 📜SignupForm.tsx
 ┣ 📂context
 ┃ ┣ 📜AuthContext.tsx
 ┃ ┗ 📜ThemeContext.tsx
 ┣ 📂pages
 ┃ ┣ 📂home
 ┃ ┃ ┗ 📜index.tsx
 ┃ ┣ 📂login
 ┃ ┃ ┗ 📜index.tsx
 ┃ ┣ 📂posts
 ┃ ┃ ┣ 📜detail.tsx
 ┃ ┃ ┣ 📜edit.tsx
 ┃ ┃ ┣ 📜index.tsx
 ┃ ┃ ┗ 📜new.tsx
 ┃ ┣ 📂profile
 ┃ ┃ ┗ 📜index.tsx
 ┃ ┗ 📂signup
 ┃ ┃ ┗ 📜index.tsx
 ┣ 📜App.tsx
 ┣ 📜firebaseApp.ts
 ┣ 📜index.css
 ┣ 📜index.tsx
 ┗ 📜react-app-env.d.ts
```