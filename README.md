# Shop
#### ⚪ About Project
* ##### NodeJS로 쇼핑몰의 기본 기능 구현, admin 페이지 구현
* ##### Passport(local, google), cookie-session 인증
* ##### 상품 불러오기, 생성, 수정, 삭제 / 카테고리 불러오기, 생성, 삭제
* ##### 파일 업로드 + dropzone을 이용한 세부 이미지 생성 / 장바구니 불러오기, 추가, 수정, 초기화, PG결제(테스트)

- - -

#### ⚪ Running Screen || Video
<p align ="center">
  <a href="https://www.youtube.com/watch?v=VNUQ4d3GX4Q"><img src ="https://img.shields.io/badge/youtube-FF0000.svg?&style=for-the-badge&logo=youtube&logoColor=white"/></a>
  </br>
  <img src="https://github.com/MpqM/NodeJS_Shop/assets/79093184/d8bf6416-b917-4ef9-ac0a-664fa5a4e024">
</p>

- - -

#### ⚪ Built With
<p align ="center">
  <img alt="HTML5" src ="https://img.shields.io/badge/HTML5-E34F26.svg?&style=for-the-badge&logo=HTML5&logoColor=white"/> <img altt="CSS3"src="https://img.shields.io/badge/CSS-1572B6?style=for-the-badge&logo=CSS3&logoColor=white"> <img src ="https://img.shields.io/badge/ejs-B4CA65.svg?&style=for-the-badge&logo=ejs&logoColor=white"/> <img alt="javascript" src ="https://img.shields.io/badge/javascript-F7DF1E.svg?&style=for-the-badge&logo=javascript&logoColor=white"/> <img alt="nodedotjs" src ="https://img.shields.io/badge/nodejs-339933.svg?&style=for-the-badge&logo=nodedotjs&logoColor=white"/> <img alt="express" src ="https://img.shields.io/badge/express-339933.svg?&style=for-the-badge&logo=express&logoColor=white"/> <img alt="mongodb" src ="https://img.shields.io/badge/mongodb-339933.svg?&style=for-the-badge&logo=mongodb&logoColor=white"/>
</p>

- - -

#### ⚪ Getting Started
```bash
# Prerequisites: npm, node, MongoDB Connection URL, Google Oauth Client, PortONE(PG)
# execution
git clone https://github.com/MpqM/NodeJS_Shop
npm install
npm start
```

- - -

#### ⚪ Description
* ##### Admin
    * ##### 인증 미들웨어를 통해 유저 데이터의 admin필드가 1인경우에 관리자 페이지에 접근 가능
    * ##### 카테고리 생성 및 삭제, 카테고리별 상품 페이지 조회 가능
    * ##### 상품 생성, 수정, 삭제, 이미지 업로드로 대표이미지 생성 및 드랍존스크립트로 크기 조절된 세부 이미지 생성
* ##### Cart
    * ##### 장바구니 불러오기, 추가, 수정, 초기화
    * ##### 장바구니에서 수량 증가, 감소, 삭제를 쿼리($action)를 통해 업데이트
    * ##### 클라이언트에서 PG결제 로직 처리(임시)
* ##### Product(View)
    * ##### 전체 조회 및 카테고리별 상품 렌더링(대표이미지, 가격, 장바구니 추가, 자세히)
    * ##### 상품에 대한 자세한 정보 확인 페이지 렌더링(상품의 전체 필드 정보)
* ##### Else
    * ##### dropzone 스크립트를 이용해 상품 세부 이미지들 생성
    * ##### Passport.isAuthenticated()를 이용한 미들웨어로 관리자, 리소스, 라우팅 비인가 접근 보호
    * ##### 미들웨어로 페이지 이동시 오류, 성공 메시지를 보이기 위해 flash 사용 및 res.locals 객체에 user, cart 정보 저장

- - -

#### ⚪ Writer
<p align ="center">
  <img src ="https://img.shields.io/badge/gmail-EA4335.svg?&style=for-the-badge&logo=gmail&logoColor=white"/></a> <a href = "https://github.com/MpqM"><img src ="https://img.shields.io/badge/GitHub-181717.svg?&style=for-the-badge&logo=GitHub&logoColor=white"/></a> <a href = "https://MpqM.tistory.com/"> <img src ="https://img.shields.io/badge/tistory-000000.svg?&style=for-the-badge&logo=Tistory&logoColor=white"/></a>
</p>

- - -
