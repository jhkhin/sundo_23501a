# connection

- 진행 기간 : 2023.12.1 ~ 2023.1.4 (5주간) <br/>
- 프로젝트 명 : 수자원 종합관리 플랫폼

## 팀원 소개
 - 팀장 : 이광현 <p>
 - 팀원 : 강준우, 이진희, 조미혜, 황인정 <br>

## 기술 스택
- <img src="https://img.shields.io/badge/Framework-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"><img src="https://img.shields.io/badge/2.7.0-515151?style=for-the-badge"> <img src="https://img.shields.io/badge/eGovframe-512BD4?style=for-the-badge&logoColor=white"><img src="https://img.shields.io/badge/4.1-515151?style=for-the-badge">
- <img src="https://img.shields.io/badge/Build-%23121011?style=for-the-badge">![Apache Maven](https://img.shields.io/badge/Apache%20Maven-C71A36?style=for-the-badge&logo=Apache%20Maven&logoColor=white)<img src="https://img.shields.io/badge/4.0-515151?style=for-the-badge">
- <img src="https://img.shields.io/badge/Language-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/java-%23ED8B00?style=for-the-badge&logo=openjdk&logoColor=white"><img src="https://img.shields.io/badge/11-515151?style=for-the-badge">
- <img src="https://img.shields.io/badge/DATABASE-%23121011?style=for-the-badge">![Postgres](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white) <img src="https://img.shields.io/badge/postgis-68BC71?style=for-the-badge&logoColor=white">
- <img src="https://img.shields.io/badge/front-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white"> <img src="https://img.shields.io/badge/css-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white"> <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E"> <img src="https://img.shields.io/badge/jquery-%230769AD.svg?style=for-the-badge&logo=jquery&logoColor=white"> <img src="https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white">

- <img src="https://img.shields.io/badge/Library-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/OpenLayer-FFFF66.svg?style=for-the-badge&logoColor=white">
- <img src="https://img.shields.io/badge/software-%23121011?style=for-the-badge"><img src="https://img.shields.io/badge/GoServer-23C8D2.svg?style=for-the-badge&logoColor=white">

## 기획배경
 - 수자원 통합 관리 정보 시스템 구축 (수자원 관리 효율성 및 체계 강화)
 - 체계적인 수자원 정보 관리 실현 (다양한 정보를 통합해 관리하는 GIS 기반의 시스템 구축) <br>

## 프로젝트 소개
 - 한강 유역의 수문을 지도 서비스와 연동하여 관측소 위치 및 시설물을 편리하게 볼 수 있습니다.
 - 수자원 시설물 관리시스템을 통해 점검결과 및 이력 조회, 고장/조치 결과 보고서를 작성 할 수 있습니다.<p>
 
### 프로젝트 프로세스
 - 관리자 시스템 : 사용자, 운영, 시스템 관리
 - 실시간 수문 정보 : 지도 (관측소, 시설물, 레이어, 북마크), 목록(관측소, 수자원등의 조회, 등록, 수정, 삭제)
 - 수자원 시설물관리 시스템 : 점검이력결과 작성, 조회, 통계 및 고장/조치 보고서<p>
<img src="image/process.png" width="80%">

### 주요 기능
 - 지도
 - 
 <img src="png/intro.png" width="80%"> 
 <br>
 
## 나의 구현 기능

 ### 프로젝트 생성<p>
  - 프로젝트 팀장의 반 학생들을 목록화하여 선택할 수 있습니다.
  <img src="png/proejct_create.png" width="80%">
  <img src="png/create_page.png" width="80%"> 
  
 ### 프로젝트 단계 프로파일<p>
  <img src="png/step_proecess.png" width="80%">
  <img src="png/step_proecess_2.png" width="80%">
  <img src="png/update.png" width="80%"> <p>
   - 프로젝트 승인시 단계가 자동으로 생성되며 추가 및 삭제 가능하고 프로젝트 단계를 설정 할 수 있습니다.
  <img src="png/add.png" width="80%">
  <img src="png/portfolio.png" width="80%">
  
 ### 프로젝트 승인<p>
  - 프로젝트 승인 시 멤버, 프로젝트 번호를 순차적으로 동시에 진행하며 프로세스 단계를 생성하게 됩니다.
  - 프로젝트 삭제 시 프로젝트 번호, 멤버를 순차적으로 동시에 진행하여 프로세스를 삭제하게 됩니다. <p>
  <img src="png/admin.png" width="80%">
  <img src="png/admin_page.png" width="80%">
  
 ### 통합검색<p>
  <img src="png/search.png" width="80%">
  <img src="png/search_page.png" width="80%">
  <br>
  
## 프로젝트 소감
학원에서 배운 내용을 어떻게 실제상황에서 접할지 막막했었습니다.
이번 프로젝트의 가장 어려웠던 점은 어떤 프로세스를 토대로 프로그램을 만들어야 될지 많이 고민 했었습니다.
또한 여러 작업을 동시다발적으로 한번에 진행해야되서 서로 고민이 많았던것 같습니다.
팀장의 역할을 맡아 어깨가 무거웠지만 팀원들의 도움으로 서로 의견을 내고 도와주면서 잘 마무리 지었고 개발자로서 한걸음 다가갈수 있는 기회가 되었습니다.
