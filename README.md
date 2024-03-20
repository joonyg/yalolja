# Yalolja Project 소개  

### 사용 대상 : e-sport League-Of-Legend 관련 LCK 모든 구단 굿즈 대행 사이트
### 문제 의식 
- 사용자가 자신이 좋아하는 구단의 굿즈뿐만 아니라 다양한 굿즈를 쉽게 탐색하고 구매하고 싶어하는데, 이를 위한 편리한 통합 플랫폼이 부족하다고 생각하였습니다.

### 사이트
https://yalolja-omega.vercel.app/

### 시연 영상
https://www.youtube.com/watch?v=thD_Yfqu5Wg


![야롤자](https://github.com/joonyg/yalolja/assets/90684826/4ca98b46-5bbe-492f-a710-afac91be996b)

### 개발기간  
- 23.12.26 ~ 24.01.02 (5일)
### 팀원 
- 3명(Front-End)
### 기술 스택 및 라이브러리         
<div align=left>
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
   <img src="https://img.shields.io/badge/styledcomponents-DB7093?style=for-the-badge&logo=styledcomponents&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> 
  <img src="https://img.shields.io/badge/recoil-3578E5?style=for-the-badge&logo=recoil&logoColor=white">
   <img src="https://img.shields.io/badge/reactrouter-CA4245?style=for-the-badge&logo=reactrouter&logoColor=black">
  <img src="https://img.shields.io/badge/reactquery-FF4154?style=for-the-badge&logo=reactquery&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=white">
  <img src="https://img.shields.io/badge/vercel-A9A9A9?style=for-the-badge&logo=vercel&logoColor=white">
  
</div>

### 제공 서비스
- 각 소속별로 찾는 것이 아닌 모든 구단의 굿즈의 관련된 정보를 한눈에 알아 볼 수 있습니다.
- 해당 구단 카테고리 별로 굿즈를 찾아보고 좋아요를 누르고 프로필에서 확인이 가능합니다.

### 담당한 부분
#### 1.React-query를 사용하여 좋아요 기능 구현
- 상품 목록에서 좋아요 기능을 구현하기 위해 React-query를 활용했습니다.
- 사용자가 상품을 좋아요할 때마다 서버로 요청을 보내고, 즉시 화면에 반영되도록 구현했습니다.
- 데이터의 빠른 갱신을 위해 optimistic update를 활용하여 사용자 경험을 향상시켰습니다.
  
#### 2.React-Slick를 이용한 메인페이지 슬라이드 기능 구현
-  홈 페이지의 첫 시작을 에는 슬라이드의 활용이 긍정적으로 생각하여 한정된 시간 안에  기능을 구현하려면 React-Slick 라이브러리를 활용하는것이 좋다고 판단하여 구현하였습니다.
  
#### 3.Firebase를 이용한 API 연동
- 사용자가 앱에서 요청한 데이터를 Firebase를 통해 처리하고, 응답을 받아와서 화면에 동적으로 표시되도록 구현했습니다.
- RESTful API와의 통신 과정에서 발생하는 에러를 처리하고 안정적인 데이터 흐름을 보장하기 위해 사용하였습니다.
### 성장한 부분
- 프로젝트에서 React-Query를 처음 사용하여 데이터를 관리하고 좋아요 기능을 구현했습니다. 이를 통해 데이터를 효율적으로 처리하고 컴포넌트 간에 상태를 공유하는 방법에 대해 깊이 이해할 수 있었습니다. 또한, 비동기 데이터 요청 및 캐싱 기능을 활용하여 사용자 경험을 개선하는 방법을 배웠습니다.
