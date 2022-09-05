# 회원 정보와 게시판 관리 RESTful API
**22.09.01 ~ 22.09.05**   
원티드 백엔드 프리온보딩 1차 과제입니다. `backend`
## 🌱 서비스 개요

회원 정보 내용을 포함하는 테이블을 설계하고 다음과 같은 기능을 제공하는 RESTful API 서버 개발

- 공지사항, 자유게시판, 운영 게시판
- 회원 등급에 따른 게시판 기능 접근제어
- 회원가입, 로그인, 회원 탈퇴
- 이용 통계집계 (성별, 나이, 접속 시간 기준)
### ERD
⛔ 디비 설명등등등
![image](https://user-images.githubusercontent.com/50348197/188391627-1b7fec2c-f43e-45f6-bbb2-ba726d313b7e.png)
### 기술 스택
`nodejs` `express.js` `sequelize` `mySql` `swagger`
### 협업 방식( git flow )
  
⛔ git 크라켄 사진 있으면 넣으면 좋을 것 같아요~!   
  
`master` `stage` `feature` 세 종류의 브랜치를 기본으로 사용합니다.  
1. 이슈를 선정하고 이슈번호에 맞는 `feature/issueNumber` 브랜치를 만들어 기능을 개발합니다.  
2. 구현이 끝나면 `stage` 에 PR한다. 이때, 머지를 위해선 2인 이상의 리뷰가 필요합니다.  
3. 각 기능이 병합된 `stage` 에서 `master`로 병합합니다.  

## 💡 요구사항 구현 내용
### 회원 정보 관리
**회원가입**  
⛔ 회원가입 관련 내용
![image](https://user-images.githubusercontent.com/50348197/188390937-868a531e-19c0-47f9-b2a2-a3a715a48b32.png)
![image](https://user-images.githubusercontent.com/50348197/188390999-fd5821fa-6105-4726-b563-3ed4ac373966.png)
  
**로그인**    
⛔로그인 관련 내용
![image](https://user-images.githubusercontent.com/50348197/188390601-462ab506-05ee-41cf-89cd-e474edcbb7a9.png)
  
**회원탈퇴**  
⛔ 회원탈퇴 관련 내용
![image](https://user-images.githubusercontent.com/50348197/188395081-500fae2c-baca-4e43-9dfe-c159bc1a0d44.png)
  
**회원 권한 변경**  
⛔ 권한 변경 관련 내용쓰
![image](https://user-images.githubusercontent.com/50348197/188395162-38e812b6-2bfd-439f-8c05-ff65c8e5072d.png)
  
### 게시판 정보 관리
  
  ⛔게시판 정보 관리 스웨거 사진
  
### 통계 정보 관리
  ⛔ 통계 정보 관리 스웨거 사진
  
## 🛠 실행 방법 정리
```
npm init
```
👨‍💻👩‍💻 개발자용
``` 
npm start 
npm run dev // 개발자용
npm run swagger // ⛔swagger 테스트용
```

## 🧐 G팀 개발의 특징

⛔ 뭐가 있을까용
