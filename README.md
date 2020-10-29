# Mangchi-Project 
Spring Project - 우리 동네 대여 서비스 
<hr />

>가까운 동네 이웃들끼리 필요한 물건을 대여하고 물품을 나눔하는 매칭 서비스 플랫폼
>


<br>
<br>

### 기술 / 구조 

<hr />

- 웹 표준 

  `HTML5` `CSS3` `JavaScript` `jQuery` `Bootstrap4` `W3C`

- DBMS  - `MySQL`

- Spring Framework, Mybatis

- API 

   `Rest API` `kakao API` `kakao 주소 API` `kakao map API` `summernote` `socket API`

- RESTful API 구조

  서버와 클라이언트 통신을 위한 REST 인터페이스 구현

- WAS - `Tomcat8`

- AWS 배포 

  `EC2` `RDS`




<br>
<br>


### 주요 기능 및 담당 업무

<hr />

* 요청 게시판 CRUD 
  * Summernote를 활용하여 요청 글 작성 구현
  * 위도 경도 계산식을 활용하여 쿼리문 작성 후 거리 순으로 출력
  *  KaKao Map Api를 활용하여 사용자의 정확한 위치를 마커로 표시
  * Cookie 값을 활용하여 시간 별 매칭 상태 변경 조건 구현
  
* 후기 작성 
  * 사용자의 서비스 이용 후기 작성 구현

* 마이 페이지
  * 마이 페이지에 요청 글, 대여 글, 리뷰 출력
  



<br>
<br>



### 요청 게시판 & 후기 작성 설계 

<hr />

* DB - 전체 ERD

![최종ERD](https://user-images.githubusercontent.com/63032830/92091833-430a7b00-ee0c-11ea-92f5-b2bc9c01cfd0.png)



* 요청 게시판 후기 작성 프로세스 



![image-20201029151322209](https://user-images.githubusercontent.com/63437506/97536469-88a88600-1a00-11eb-8f54-bd8bcaa5ccb1.png)




<br>
<br>


### 구현 - 소스코드

<hr />

* 요청 게시판
  * [Controller](https://github.com/qkrwlsaud/Mangchi-Project/tree/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/controller)  [Service](https://github.com/qkrwlsaud/Mangchi-Project/tree/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/service) [Dao](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/dao/RequestDao.java) [View](https://github.com/seongMinS2/Mangchi-Final/tree/master/Mangch_Client/src/main/webapp/WEB-INF/views/request)

* 후기 작성
  * [Controller](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/review/controller/ReviewController.java) [Service](https://github.com/qkrwlsaud/Mangchi-Project/tree/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/review/service) [Dao](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/review/dao/ReviewDao.java) [View](https://github.com/seongMinS2/Mangchi-Final/tree/master/Mangch_Client/src/main/webapp/WEB-INF/views/review)

* 마이 페이지 
  * [Controller](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/mypage/controller/MypageRequestController.java) [Service](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/mypage/service/MyListService.java) [Dao](https://github.com/qkrwlsaud/Mangchi-Project/blob/main/FinalProject/Manch-RequestList/src/main/java/com/aia/rl/mypage/dao/MypageDao.java) [View](https://github.com/seongMinS2/Mangchi-Final/tree/master/Mangch_Client/src/main/webapp/WEB-INF/views/member)

* [클라이언트 소스코드 Link](https://github.com/seongMinS2/Mangchi-Final) 

  









