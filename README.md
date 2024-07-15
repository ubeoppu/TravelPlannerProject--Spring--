# :memo:스프링 여행플래너웹사이트 README
</div>
<p align="center">
     <img src="https://github.com/ubeoppu/TravelPlannerProject/assets/157093883/6f5c8328-c4d0-4f37-877d-4f4f99e88833" width="1500" height="500">
</p>
    <div align="left>
    <div style="font-weight: 700; font-size: 15px; text-align:left;">
      <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🔍️프로젝트 소개</h2>
        ●&nbsp;     스프링을 사용해 여행 플랜 작성 프로젝트를 구현하였습니다. 카카오 로그인, 결제 시스템, 명소 확인 등 여러가지 기능을 구현해보았습니다.
        ●&nbsp;     여행을 떠나시기 전 여행 계획을 쉽고 간단하게 작성할 수 있게끔 도움을 줄 수 있는 웹사이트입니다.<br>
        ●&nbsp;     원하시는 지역을 고른 후 원하시는 명소, 식당, 카페 등을 골라 계획을 만들 수 있습니다.<br>
        ●&nbsp;     여행을 즐기면서 시간을 절약하고 알찬 여행이 되게끔 도움을 줄 수 있습니다.<br>
        ●&nbsp;     여행지에 대한 정보를 공유 할 수 있는 게시판을 통해 유용한 정보를 얻을 수 있습니다.<br><br>
        &nbsp;&nbsp;&nbsp;&nbsp;<b>프로젝트 진행기간 : 24/05/02 ~ 24/05/27</b>
    </div>
        </div><br>
    <div align= "left">
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 🛠️ 개발 환경 </h2> 
    <div style="margin: 0 auto; text-align: center;" align= "left"> <img src="https://img.shields.io/badge/Apache Tomcat-F8DC75?style=for-the-badge&logo=Apache Tomcat&logoColor=white">
          <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=CSS3&logoColor=white">
          <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=Bootstrap&logoColor=white">
          <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=HTML5&logoColor=white">
          <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=Java&logoColor=white">
          <br/><img src="https://img.shields.io/badge/Javascript-F7DF1E?style=for-the-badge&logo=Javascript&logoColor=white">
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">
          <img src="https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=Spring&logoColor=white">
          <img src="https://img.shields.io/badge/Github-181717?style=for-the-badge&logo=Github&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=Git&logoColor=white"><br><br>
        ●&nbsp; Language : <code>JAVA(11)</code>,<code>JavaScript(1.5)</code><br>
        ●&nbsp; Database : <code>MySQL(8.0.36)</code><br>
        ●&nbsp; API : <code>네이버 API</code>, <code>구글 맵 API</code>, <code>포트 원 API</code>, <code>coolSMS</code>, <code>카카오 로그인 API</code><br>
        ●&nbsp; Library & Framework : <code>Spring(5.2.7)</code>, <code>Spring Security(5.2.7)</code><br>
          <br/></div><br>
         <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> :pushpin: 맡은 역할 </h2>
         <b>임재현(조장)</b><br>
         &nbsp;&nbsp;&nbsp;●&nbsp; DB설계, 메인페이지,헤더, 여행 일정 작성(캘린더, 일정 선택, 시간 설정)<br>
         &nbsp;&nbsp;&nbsp;●&nbsp; 마이페이지, 게시판을 제외한 페이지 전체CSS(로그인,회원가입...) <br><br>
         <b>이효빈</b><br>
         &nbsp;&nbsp;&nbsp;●&nbsp; 로그인, 회원가입, 아이디/패스워드 찾기, 카카오 로그인<br>
         &nbsp;&nbsp;&nbsp;●&nbsp; 여행 일정 작성(지도 좌표 표시, 루트 설정)DB 정보 삽입<br><br>
         <b>김정훈</b><br>
         &nbsp;&nbsp;&nbsp;●&nbsp; 게시판 페이지, 댓글, 마이페이지, CSS(게시판, 마이페이지)<br>
           <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> :white_check_mark: 주요 기능 </h2>
  <b>로그인</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 회원가입시 이메일 인증<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 카카오 로그인<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 인증을 통한 아이디 및 비밀번호 찾기<br><br>
  <b>일정 계획</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 여행 기간을 선택 후 날마다 명소 및 시간 상세설정<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 해당 지역에 맞는 명소 리스트 출력<br><br>
  <b>게시판</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 회원간의 여행지 정보 공유<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 여행지에 대한 후기 작성<br><br>
  <b>마이페이지</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 개인정보 수정<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 작성한 여행일정 열람 가능<br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 작성한 게시글 열람 가능<br><br>
  <b>일반회원</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 일정 계획 작성 페이지 열람 가능(저장X)<br><br>
  <b>유료회원</b><br>
           &nbsp;&nbsp;&nbsp;●&nbsp; 일정 계획 작성 가능(DB저장O)
              <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 💡 설계 및 기능구현 </h2>
         
|||
|---|----|
|<img src="https://github.com/user-attachments/assets/5f184f8e-7e92-4d63-8e29-cd05c7689cce" width="560" height="300">|<img src="https://github.com/user-attachments/assets/bf1dc95f-4f72-42d5-8d1c-12b75e5ed387" width="560" hieght="300">|
|<img src="https://github.com/user-attachments/assets/2a16f047-01ad-4a26-9ef5-940f141fed0d" width="560" height="300">|<img src="https://github.com/user-attachments/assets/03708244-dc69-4841-8d3f-6d64721ed46e" width="560" height="300">|
|<img src="https://github.com/user-attachments/assets/29d18e4c-277f-458d-9952-42209139b508" width="560" height="300">|<img src="https://github.com/user-attachments/assets/2dcd7b8c-c663-4061-a8a5-22d6899d0430" width="560" height="300">|
|<img src="https://github.com/user-attachments/assets/b90df163-1de2-459a-836d-c5d6616e791f" width="560" height="300">|<img src="https://github.com/user-attachments/assets/e7554605-d1c4-44e8-9e6a-8ff8b5165045" width="560" height="300">|
|<img src="https://github.com/user-attachments/assets/55bdecea-9fb8-47ac-86b3-ea2f75a4bb21" width="560" height="300">|<img src="https://github.com/user-attachments/assets/d2aaa93f-9602-475a-ab59-f58063f7d293" width="560" height="300">|

---
ER-다이어그램
---
<img src="https://github.com/user-attachments/assets/7d0794e4-0605-470d-b49f-b9b0ff95b78b" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/97a88f22-48ff-47a7-86cc-618dba452aaa" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/490b9df9-a446-4925-ad05-4224d9ce73c4" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/d549f808-cbe6-41a4-9d59-9c7a6f92f11c" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/c06aecf9-c6a7-4779-9413-475f35daac02" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/f3bf81db-6677-4c9b-8cc5-6dc9cea1c7cd" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/f7c2afa2-0160-4705-8956-3d3112db5dc5" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/2f3fea85-1383-4959-8519-d6e980e9cc5b" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/14c9e662-6df5-422d-97e1-e077d04b7530" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/f767ad28-3fd7-487b-be41-acbbd171577f" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/18b3d8ac-677a-4b48-a805-5fcfba763669" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/839a52ba-5bff-4d3f-a8b9-7f5c400a7557" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/35250b9b-3f7f-47f2-9236-31592244cc6e" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/99211f2c-271c-432b-b350-44843e0396d2" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/61966d03-7f92-4be2-801b-ae1862cfad2a" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/5b7d6e06-d2c7-4715-8d47-9d6ac76f770d" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/1780fca6-9cf9-4133-8dbc-45c6bdd7308c" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/5dfeb5e3-41ed-42b4-a805-13aa3feb09a9" width="1450" height="650">           

---
<img src="https://github.com/user-attachments/assets/00f3ba33-9444-422a-b965-b2c9ac79af4c" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/1879d32a-cd62-431b-afb4-0f2adcc1648e" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/9a4130f5-c0f0-4392-85c4-2be9e374065d" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/369645be-304b-479a-888b-8a8b706fe43c" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/1141eca8-d192-499d-8289-dc7ebdb4a039" width="1450" height="650">

---
<img src="https://github.com/user-attachments/assets/13e9b7e5-9f0e-4b36-8c72-ea14069b2019" width="1450" height="650">
<br>
<br>
    <h2 style="border-bottom: 1px solid #d8dee4; color: #282d33;"> 	:zap: 미구현 기능 </h2>
    <b>QNA페이지</b><br>
    <b>관리자 페이지</b><br>
    <b>여행계획 수정 페이지</b>
     


