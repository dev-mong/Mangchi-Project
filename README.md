

# 우리 동네 대여 서비스 - Request & Review

> 가까운 동네 이웃들끼리 필요한 물건을 대여하고 
>
> 서로의 일상을 공유하고 물품을 나눔하는 매칭 서비스 플랫폼



#### 기술 / 구조 

------

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



#### 주요 기능 및 담당 업무

------

* 요청 게시판 CRUD 
  * Summernote를 활용하여 요청 글 작성 구현
  * 위도 경도 계산식을 활용하여 쿼리문 작성 후 거리 순으로 출력
  *  KaKao Map Api를 활용하여 사용자의 정확한 위치를 마커로 표시
  * Cookie 값을 활용하여 시간 별 매칭 상태 변경 조건 구현
* 후기 작성 
  * 사용자의 서비스 이용 후기 작성 구현



#### 요청 게시판 & 후기 작성 설계 

------

* DB - 전체 ERD

![최종ERD](https://user-images.githubusercontent.com/63032830/92091833-430a7b00-ee0c-11ea-92f5-b2bc9c01cfd0.png)



* 요청 게시판 후기 작성 프로세스 



![image-20201029151322209](https://user-images.githubusercontent.com/63437506/97536469-88a88600-1a00-11eb-8f54-bd8bcaa5ccb1.png)




#### 구현 - 소스코드

------



