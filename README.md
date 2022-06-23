# ⭐️ Portfolio - Almeal

<details>
<summary>Contents</summary>
<div markdown="1">       

  1. [개요](#-개요)
  2. [내용](#-내용)
  3. [구현 기능](#-구현-기능)
      + [공지사항 게시판](https://github.com/hhje0232/Market/edit/main/README.md#%EA%B3%B5%EC%A7%80%EC%82%AC%ED%95%AD-%EA%B2%8C%EC%8B%9C%ED%8C%90)
      + [스토어 게시판](https://github.com/hhje0232/Market/edit/main/README.md#%EC%8A%A4%ED%86%A0%EC%96%B4-%EA%B2%8C%EC%8B%9C%ED%8C%90)
      + [회원관리 게시판](https://github.com/hhje0232/Market/edit/main/README.md#%ED%9A%8C%EC%9B%90%EA%B4%80%EB%A6%AC-%EA%B2%8C%EC%8B%9C%ED%8C%90)
      + [오시는길 게시판](https://github.com/hhje0232/Market/edit/main/README.md#%EC%98%A4%EC%8B%9C%EB%8A%94%EA%B8%B8-%EA%B2%8C%EC%8B%9C%ED%8C%90)

</div>
</details>

# 📝 개요
+ 프로젝트 명 : Almeal

+ 일정 : 2022년 05월 ~ 2022년 06월

+ 개발 목적 : 1인 가구를 위한 주류와 밀키트 구독 사이트

+ 개발 환경
  + Server : Apache-tomcat-8.5
  + Java EE IDE : Eclipse
  + Database : Oracle SQL Developer
  + Programming Language : JAVA, CSS, JavaScript, JSP, SQL
  + Framework/flatform : Spring, mybatis, jQuery 3.5.1, Bootstrap v5
  + API : Kakao Login, Naver Login, CoolSMS
  + Version management : Git
  

# 📝 내용
+ 구현 기능
  + 공지사항 게시판 
  + 스토어 게시판
  + 구독 게시판 
  + 고객센터 게시판
  + 관리자 기능

# 📝 구현 기능
## 공지사항 게시판
 ### 1. 공지사항 조회
 
 #### 사이트 내 공지사항 게시판 페이지
 + 구현 기능 설명
    + 공지사항 게시판 글 목록 조회
    + 페이징을 통해 게시글 목록 넘기기
    + 게시판 글 쓰기
    + 게시물 조회
    + 목록으로 이동



 ### 2. 공지사항 수정
 #### 공지사항 게시글 수정 페이지
 + 구현 기능 설명
    + 게시글 수정 시, DB에 등록된 게시글 제목, 내용 불러옴.
    + 수정 버튼 클릭 시 수정한 게시글 상세조회로 이동하게 됩니다.
   
![image](https://user-images.githubusercontent.com/104810523/174935520-31cfbe52-b04b-40fa-ac06-27e7c46ef237.png)

![image](https://user-images.githubusercontent.com/104810523/174935527-a39a7247-22e3-4af8-b7c7-831ddb8ad077.png)

![image](https://user-images.githubusercontent.com/104810523/174935539-c610b2ea-2c15-4928-b1c3-ff5708baa128.png)


 ### 3. 공지사항 삭제
 #### 공지사항 게시글 삭제 페이지
 + 구현 기능 설명
    + 삭제 버튼 클릭 시 비밀번호 판별을 하여 삭제 성공 및 실패 확인

![image](https://user-images.githubusercontent.com/104810523/174935881-69d32d5d-5beb-4444-9ccd-331dca127ce1.png)

![image](https://user-images.githubusercontent.com/104810523/174935905-ce2b8a09-30a4-4d34-bf12-1d0ffa620871.png)

![image](https://user-images.githubusercontent.com/104810523/174935853-afdc7d84-a873-468d-916c-d74901844fc0.png)

![image](https://user-images.githubusercontent.com/104810523/174935860-c2c41049-ed62-4401-adc8-1291f46563f2.png)

-------------------------------------
## 스토어 게시판 
### 1. 스토어 상품 조회
 #### 사이트 내 스토어 게시판 페이지
 + 구현 기능 설명
    + 마켓 제품 목록 페이지 구현
    + 수량에 따른 구매 페이지

![image](https://user-images.githubusercontent.com/104810523/174937033-437bce97-76dc-4543-87cd-40f3b1d1634e.png)

![image](https://user-images.githubusercontent.com/104810523/174937040-c876affc-5f14-46fd-a2a8-083071d9e406.png)




### 2. 스토어 장바구니 
#### 장바구니 담기, 삭제 페이지
 + 구현 기능 설명
    + 장바구니 목록 페이지
    + 장바구니 담기 기능
    + 장바구니 삭제 기능
    + 로그아웃 상태에서 장바구니/주문하기 버튼 누르면 로그인 페이지로 이동

![image](https://user-images.githubusercontent.com/104810523/174937044-0e2bbd6c-9cde-435c-a553-57a0a0f97656.png)

![image](https://user-images.githubusercontent.com/104810523/174937056-36b2ab4c-b960-4696-9873-bb33bebc5eab.png)

![image](https://user-images.githubusercontent.com/104810523/174937062-81407353-cb46-499c-bc4b-d90fda2c1a44.png)

![image](https://user-images.githubusercontent.com/104810523/174937069-fa53c112-8ee8-407e-a4cf-424744d5ea5a.png)

## 회원관리 게시판
 ### 1. 회원가입
 
 #### 사이트 내 회원가입 페이지
 + 구현 기능 설명
    + 아이디 중복 확인
    + 우편번호 찾기
    + 비밀번호 보안 단계별 확인
    + 비밀번호 일치 여부 판별


![image](https://user-images.githubusercontent.com/104810523/174937912-83ac9b6d-b4a2-4b10-869e-150315310a49.png)

![image](https://user-images.githubusercontent.com/104810523/174937921-3885fac6-3078-48e8-ae0a-e90cb79dc767.png)

![image](https://user-images.githubusercontent.com/104810523/174937930-5bf661ae-f20e-4ae8-8210-ac95eec0deaf.png)

![image](https://user-images.githubusercontent.com/104810523/174937935-2f0a6160-d3a5-4246-839b-9e509da0852b.png)

![image](https://user-images.githubusercontent.com/104810523/174937943-6f67a80c-081a-4a28-875a-8b8e4e3af5e5.png)

### 2. 로그인
 
 #### 사이트 내 로그인 페이지
 + 구현 기능 설명
    + 로그인 실패시 로그인 실패창 
 
![image](https://user-images.githubusercontent.com/104810523/174938057-0c5351b6-d382-489b-a618-c209241dc223.png)

![image](https://user-images.githubusercontent.com/104810523/174938765-7b786e12-626e-4047-9f53-59253476014a.png)

![image](https://user-images.githubusercontent.com/104810523/174938770-605964b4-b935-4943-acc5-8363f11a5f6b.png)

![image](https://user-images.githubusercontent.com/104810523/174938772-8639e1e3-583a-45b7-991d-07b8a13524b8.png)

## 오시는길 게시판
 ### 지도
 + 구현 기능 설명
    + 구글 API 로 위치 정보 출력

![image](https://user-images.githubusercontent.com/104810523/174938964-69f8822a-302a-4505-8286-53e732e0c8bc.png)

---------------------------------------
지금까지 읽어주셔서 감사합니다 :)
