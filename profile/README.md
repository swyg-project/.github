# 🎁 맞춤형 선물 고르기 서비스 : 요고어때
<br>

  <img src="https://github.com/swyg-project/.github/assets/65762430/735cfc35-b74c-4b50-b640-67450252b585">


<br>
<br>
  해당 서비스를 통해 선물을 받는 사람을 생각하며 주고 싶은 가격대, 종류에 맞는 선물을 골라 리스트를 만든 후 이를 전송할 수 있습니다. <br>
  선물을 받는 사람이 어떤 것을 원할지 감이 잡히지 않는다면, 유형테스트를 통해 선물을 받는 사람을 생각하며 질문에 답을 하고, 테스트 결과로 추천 선물 리스트를 제공 받을 수 있습니다.


<br>
<br>

[👉 요고어때 바로가기](https://yogotte.swygbro.com/)

<br>


## 개발 환경
- Front : HTML, React, styled-components, React-Redux
- Server : Firebase, 11번가 API
- 버전 및 이슈관리 : Github
- 협업 툴 : Discord, Slack, KakaoTalk, Swyg
- 서비스 배포 환경 : SWYG
- 디자인 : XD

<br>

## 개발 목표
- 실제 판매하는 상품 정보
  - 11번가 API 이용
- 사용자가 접근 용이하고 간편하게 사용
  - 회원가입/로그인 없이 URL에 정보를 담아서 공유
  - URL 단축
- 맞춤형 선물 추천 기능
  - 유형테스트를 통한 선물 추천
<br>

## 개발 기간

- 전체 개발 기간: 2023-09-09 ~ 2023-10-22
- 기획: 2023-09-09 ~ 2023-09-30
- 디자인: 2023-09-30 ~ 2023-10-17
- 기능 구현: 2023-09-30 ~ 2023-10-22
  
<br>

## 팀원 구성


<div align="center">
  
|백민지|원동건|장은혜|최수영|
|:---:|:---:|:---:|:---:|
|<img src="https://github.com/swyg-project/.github/assets/65762430/35e8ea1d-cd39-471d-a724-97559bcb23b5" width= 150 >|<img src="https://github.com/swyg-project/.github/assets/65762430/9a127f77-4441-4349-9d78-894ee599cec7" width= 150>|<img src="https://github.com/swyg-project/.github/assets/65762430/08e29f52-4ea0-4639-8de5-6a8e4eccb8ee" width= 150 >|<img src="https://github.com/swyg-project/.github/assets/65762430/33557a20-9882-4b43-bf66-80a0b3a66510" width= 150 >|
|기획자|개발자|개발자|디자이너|
|qoralswl623@naver.com|same666@naver.com|dmsgp220@naver.com|chltndud0601@gmail.com|

</div>





<br>


## 페이지 및 기능

### [홈화면]
- 두 가지 페이지로 분기 (선물 리스트, 유형 테스트)
- 링크 공유하기 클릭시 사이트 url 클립보드에 복사

![image](https://github.com/swyg-project/.github/assets/65762430/4b55f10a-d992-41ad-89bf-5d6c834df881)

<br>

### [유형테스트] 
- 로고를 누르면 홈화면으로 이동
- 질문과 답변으로 구성, 답변 선택시 다음 문항으로 자동 이동
- 뒤로가기 버튼을 누르면 이전 문항으로 이동
  
![image](https://github.com/swyg-project/.github/assets/65762430/12d33215-e0c7-4d68-a3c0-68e285fad95a)

<br>

### [유형테스트 결과]
- 받는 사람의 mbti별 추천 선물을 보여줌
- 선물 고르러 가기 버튼을 누르면 선물리스트 화면으로 이동
  
![image](https://github.com/swyg-project/.github/assets/65762430/fc9c84ae-dc69-415d-80da-d5c04c2d79bf)

<br>

### [선물리스트]
- 카테고리 클릭시 해당 카테고리 목록 출력
- 상품의 하트 버튼 클릭시 선물함에 추가
- 오른쪽 상단의 선물함 버튼으로 선물함으로 이동

![image](https://github.com/swyg-project/.github/assets/65762430/7f76a35d-9deb-4bb6-afe2-99a9656ebe56)

<br>

### [선물함]
- 더 담으러 가기 : 선물 리스트로 이동
- 완료하기 : 편지쓰기로 이동
- 목록의 x 클릭시 선물함에서 해당 선물 삭제

![image](https://github.com/swyg-project/.github/assets/65762430/bb95c499-c01b-4806-9c77-a03a910d00f1)

<br>

### [편지 쓰기]
- 선물을 줄 대상에게 편지쓰기 
- 친구에게 보내기 : 선물 목록과 편지를 URL에 담아 클립보드에 복사

![image](https://github.com/swyg-project/.github/assets/65762430/2326c001-350b-4efa-9a6d-cc7375ae5b8d)

<br>


### [받는 사람 - 홈화면]
- 단축 url에서 원본 url로 리다이렉트
- url 쿼리스트링 값을 받아 받는사람, 주는사람의 이름을 보여줌
- 버튼 클릭 시 선물 고르기 페이지로 이동

![image](https://github.com/swyg-project/.github/assets/65762430/b8c2b694-b7dd-47bb-a137-083b2f440b6f)

<br>

### [받는 사람 - 선물고르기]
- 쿼리스트링으로 편지내용과 상품ID리스트 받고 보여줌
- 상품ID로 11번가 API를 이용해 상품 정보(상품이름, 가격, 이미지)를 받아옴
- 이미지 클릭 시 11번가 상품 페이지로 이동
- 하트를 누르면 원하는 선물 선택 가능함 (중복가능)
- 친구에게 고른 선물 알려주기 버튼 클릭 시, URL 단축과 링크 복사

![image](https://github.com/swyg-project/.github/assets/65762430/aab96e77-410b-4470-95f6-fbfba1236117)

<br>

### [마지막 화면]
- 받는 사람이 고른 선물을 보여줌

![image](https://github.com/swyg-project/.github/assets/65762430/05d17a98-1fcf-4a53-b0a3-e75ccf9f39d7)


<br>

### [URL 단축] 
- 고유ID 생성 후 BASE62 인코딩
- 원본 URL과 단축URL을 필드에 저장
- short으로 시작하는 경로면, 원본 url로 리다이렉트
  
![image](https://github.com/swyg-project/.github/assets/65762430/ab50488b-a2cb-4f91-b1a8-01c2f9ea16c0)

<br>


