# ⭐️ Portfolio - Almeal

<details>
<summary>Contents</summary>
<div markdown="1">       

  1. [개요](#-개요)
  2. [내용](#-내용)
  3. [구현 기능](#-구현-기능)
      + [공지사항 게시판]()
      + [스토어 게시판]()
      + [회원관리 게시판]()
      + [오시는길 게시판]()

</div>
</details>

# 📝 개요
+ 프로젝트 명 : Almeal
+ 일정 : 2022년 05월 ~ 2022년 06월
+ 인력 구성 : BE 5명 / FE 1명
+ 프로젝트 목적 : 팀 프로젝트로서 Spring과 MyBatis 활용능력을 기르기 위한 프로젝트
+ 프로젝트 내용 : 구독패키지와 일반 상품을 판매하는 웹페이지
+ 개발 환경
  + Server : Apache-tomcat-8.5
  + Java EE IDE : Eclipse
  + Database : Oracle SQL Developer
  + Programming Language : JAVA, CSS, JavaScript, SQL
  + Framework/flatform : Spring, mybatis, jQuery 3.5.1, Bootstrap v5
  + API : Kakao Login, Naver Login, CoolSMS
  + Version management : (https://github.com/wurstel/ITWill_team_Spring.git)
  

# 📝 내용
+ 구현 기능
  + 공지사항 게시판 
  + 스토어 게시판
  + 구독 게시판 
  + 고객센터 게시판
  + 관리자 기능

# 📝 ERD
## 상품과 회원을 기준으로 DB 설계
<img width="482" alt="image" src="https://user-images.githubusercontent.com/104810523/176326276-4815f960-7074-4d64-9d3f-80267836eaf6.png">


# 📝 구현 기능
## 공지사항 게시판
 ### 1. 공지사항 조회
 
 #### 사이트 내 공지사항 게시판 페이지
 

![공지사항 게시판](https://user-images.githubusercontent.com/104810523/175256261-88274a34-0088-4e69-94f9-bf5ff67c22ef.gif)

 + 구현 기능 설명
    + 공지사항 게시판 글 목록 조회
    + 페이징을 통해 게시글 목록 넘기기
    + 게시판 글 쓰기
    + 게시물 조회
    + 목록으로 이동

 ### 2. 공지사항 수정
 #### 공지사항 게시글 수정 페이지
 
 ![공지사항 수정](https://user-images.githubusercontent.com/104810523/175256760-ae502b73-b793-4520-a282-f7f2ec47b84b.gif)

 + 구현 기능 설명
    + 게시글 수정 시, DB에 등록된 게시글 제목, 내용 불러옴.
    + 수정 버튼 클릭 시 수정한 게시글 상세조회로 이동하게 됩니다.
   

 ### 3. 공지사항 삭제
 #### 공지사항 게시글 삭제 페이지
 
 ![공지사항 삭제](https://user-images.githubusercontent.com/104810523/175257025-a698f925-d306-48b8-83da-45adf624ed80.gif)

 + 구현 기능 설명
    + 삭제 버튼 클릭 게시물 삭제 


-------------------------------------
## 스토어 게시판 
### 1. 스토어 상품 조회
 #### 사이트 내 스토어 게시판 페이지
 + 구현 기능 설명
    + 마켓 제품 목록 페이지 구현
    + 수량에 따른 구매 페이지




### 2. 스토어 장바구니 
#### 장바구니 담기, 삭제 페이지
 + 구현 기능 설명
    + 장바구니 목록 페이지
    + 장바구니 담기 기능
    + 장바구니 삭제 기능
    + 로그아웃 상태에서 장바구니/주문하기 버튼 누르면 로그인 페이지로 이동


## 회원관리 게시판
 ### 1. 회원가입
 
 #### 사이트 내 회원가입 페이지
 + 구현 기능 설명
    + 아이디 중복 확인
    + 우편번호 찾기
    + 비밀번호 보안 단계별 확인
    + 비밀번호 일치 여부 판별




### 2. 로그인
 
 #### 사이트 내 로그인 페이지
 + 구현 기능 설명
    + 로그인 실패시 로그인 실패창 



## 오시는길 게시판
 ### 지도
 + 구현 기능 설명
    + 구글 API 로 위치 정보 출력



---------------------------------------
지금까지 읽어주셔서 감사합니다 :)
