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
  4. 보완할 점

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
  + 회원가입 및 로그인
  + 상품 리스트 및 결제
  + 구독 정기결제
  + 마이페이지 구현
  + 관리자 페이지 구현

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
## 회원가입 및 로그인
### 1. 회원가입
 #### 사이트 내 회원가입 페이지
![회원가입](https://user-images.githubusercontent.com/104810523/176335393-d3bdfc9e-fd4a-4dfd-aafe-778cfca39d87.gif)
#### 회원가입을 위한 메일 인증
![회원가입메일인증](https://user-images.githubusercontent.com/104810523/176335413-b24cedf7-de35-45af-8004-9a59a77884c8.gif)
#### 메일 인증 완료 후 로그인
![회원가입후로그인](https://user-images.githubusercontent.com/104810523/176335422-9e5ad4bf-83c0-40a0-96d9-f625921ce1f5.gif)

 + 구현 기능 설명
    + 아이디 중복 체크
    + 비밀번호 정규표현식, 일치 여부 판별
    + 다음 우편번호 API
    + 비밀번호 암호화
    + 메일 인증 후 회원가입 완료

### 2. 로그인
 
 #### 사이트 내 로그인 페이지
 ![회원가입후로그인](https://user-images.githubusercontent.com/104810523/176335720-5c0d03b3-3a07-47fd-9286-5750438b10c5.gif)
 #### 카카오 로그인
![로그인](https://user-images.githubusercontent.com/104810523/176335734-683cf90f-8d61-4f60-9327-20765a3f988e.gif)
#### 네이버 로그인
![네이버로그인](https://user-images.githubusercontent.com/104810523/176335740-ef8359e8-6f92-41c2-8e90-3efe2128a66e.gif)

### 3. 아이디, 비밀번호 찾기
 #### SMS 인증으로 아이디 찾기
 #### 인증번호 확인 후 아이디 찾기 완료
![아이디찾기완료](https://user-images.githubusercontent.com/104810523/176338796-25d914b3-1abb-44ca-bd6b-a651ea4a7c7d.gif)

#### 메일 인증으로 비밃번호 찾기
![비밀번호찾기](https://user-images.githubusercontent.com/104810523/176338835-e6511276-416a-4242-9b6c-6655644a9f3e.gif)
#### 메일 인증 완료 
 ![비밀번호찾기메일인증](https://user-images.githubusercontent.com/104810523/176338891-4591e183-227b-4a73-9fc1-528ed36775e9.gif)
#### 인증 완료 후 비밀번호 변경
![비밀번호변경](https://user-images.githubusercontent.com/104810523/176338922-6b4ff867-7a91-4be2-923b-81b5d8f498bd.gif)
#### 비밀번호 변경 후 로그인
![비밀번호변경후로그인](https://user-images.githubusercontent.com/104810523/176338949-34acdd08-fa4f-4db3-a259-bcf25d8290f7.gif)

 
 + 구현 기능 설명
    + 일반로그인
    + 카카오로그인
    + 네이버로그인
    + 아이디 찾기를 위한 SMS 인증
    + 비밀번호 찾기를 위한 SMS, 메일 인증
----------------------------------------------------------------

## 상품 리스트 및 결제
### 1. 상품 메인 페이지
#### 상품 페이징 처리
![페이징처리](https://user-images.githubusercontent.com/104810523/176339625-b4c34c79-1965-49fc-9805-9bf38671aa74.gif)
#### 상품 정렬
![상품리스트](https://user-images.githubusercontent.com/104810523/176339105-2fde425f-be68-420d-a129-c75786280061.gif)
+ 구현 기능 설명
    + 상품 정렬 (최신순, 평점순, 낮은 가격순, 높은 가격순)
### 2. 상품 상세 페이지
#### 리뷰 평점, 신상품, beat상품 아이콘
![image](https://user-images.githubusercontent.com/104810523/176340599-6760c52a-62a1-4053-a4da-c834c138c9f3.png)
+ 구현 기능 설명
    + 상품 등록 후 2주동안 new 아이콘 뜨기
    + 평점 4점 이상 best 아이콘 뜨기
    + 리뷰 정렬(최신순, 평점순)
#### 장바구니 담기
![장바구니담기](https://user-images.githubusercontent.com/104810523/176340736-a2b8b226-1a8d-4b26-a81a-4ce1da7e00d2.gif)
+ 구현 기능 설명
    + 수량 변경 후 장바구니 담기
### 3. 상품 결제
#### 즉시 주문하기 
![주문하기이동](https://user-images.githubusercontent.com/104810523/176340773-f6de2b85-d5e1-4e63-bd46-e9ff14eeb653.gif)
#### 주문 완료 후 마이페이지 주문 조회로 이동
![일반결제](https://user-images.githubusercontent.com/104810523/176340811-17d9c0f4-7337-4cd5-9d28-ac097b557a4d.gif)
 + 구현 기능 설명
    + 주문 완료 후 장바구니에서 내역 삭제
    + 로그아웃 상태에서 장바구니/주문하기 버튼 누르면 로그인 페이지로 이동
### 4. 상품 검색
#### 상품 키워드로 검색
![상품검색](https://user-images.githubusercontent.com/104810523/176637921-efcc7cf9-cb97-44ab-8038-4028de4ab962.gif)
 + 구현 기능 설명
    + 상품 이름에 포함된 키워드를 입력하면 키워드를 포함한 상품이 검색됨
    + 검색된 총 상품 갯수 구현
---------------------------------------------------------------------
## 구독 정기결제
### 1. 구독 페이지
![구독](https://user-images.githubusercontent.com/104810523/176347323-f5607949-7e5e-4b8c-8656-99c854addbd9.gif)
 + 구현 기능 설명
    + 스탠다드, 프리미엄 선택

#### 정기 결제
![정기결제](https://user-images.githubusercontent.com/104810523/176638297-49f8525b-362e-45e3-a9ad-855c6a604b17.gif)

 + 구현 기능 설명
    + 카카오 결제로 정기 결제 
    
    
## 마이페이지 구현
 ### 1. 회원정보 수정
 ![회원정보수정](https://user-images.githubusercontent.com/104810523/176638517-fd6345df-8515-430b-b081-fde4cd2966d0.gif)
 + 구현 기능 설명
    + 이메일, 전화번호, 주소 정보 변경
### 2. 회원 탈퇴
 + 구현 기능 설명
    + 비밀번호 확인 후 회원 탈퇴
### 3. 장바구니
#### 장바구니 수량 변경
![장바구니수량](https://user-images.githubusercontent.com/104810523/176639038-10caf7a4-749c-44eb-8fc1-68bb0b4c55c8.gif)
#### 장바구니 삭제
![장바구니삭제](https://user-images.githubusercontent.com/104810523/176639195-62e60931-c4d0-4b43-859b-85966f96da5c.gif)
 + 구현 기능 설명
    + 수량 변경 및 삭제 시 alert 창으로 한번 더 확인
### 4. 주문 조회
#### 리뷰 쓰기

--------------------------------------------------------------    
## 관리자페이지 구현
### 1. 상품 관리
#### 관리자 상품 등록


#### 관리자 상품 삭제
![관리자상품삭제](https://user-images.githubusercontent.com/104810523/176639683-b623524e-3439-4663-889c-bcacb7cc7e07.gif)
+ 구현 기능 설명
    + 삭제 시 한번 더 확인
### 2. 회원 관리
#### 관리자 회원 삭제
![관리자회원삭제](https://user-images.githubusercontent.com/104810523/176639800-24583631-e4a9-48ae-b902-9094c84e1177.gif)
+ 구현 기능 설명
    + 삭제 시 한번 더 확인
### 3. 고객 센터
#### 고객센터 답글
![고객센터답글](https://user-images.githubusercontent.com/104810523/176639883-f270c8b8-757e-463d-8e20-df83d543dbf4.gif)
+ 구현 기능 설명
    + Re: 제목에 표시 

---------------------------------------
# 📝 보완할 점
+ 정기 결제 후 멤버십 관리
+ 관리자 대쉬보드 (매출 현황 차트 구현)
+ 전체적인 오류 확인

지금까지 읽어주셔서 감사합니다 :)
