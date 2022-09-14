![logo](https://user-images.githubusercontent.com/96946274/174237065-9722ad60-97ad-494a-b100-7ff799ee1692.png)
# OurTrip

#### 프로젝트 소개
- 항공권 숙박, 티켓, 투어, 액티비티 등을 예매할 수 있는 '마이리얼트립'을 모티브로 한 여행 예약 플랫폼 사이트 '아워트립' 제작
- 개발 기간 : 2022/06/07 ~ 2022/06/16 (10일)
- 시연 영상 : https://www.youtube.com/watch?v=n8d-xT8DhpA


# 팀원

**Front-end**
|손가영|유하은|윤경연|최현민
|---|---|---|---|
|<img src="https://user-images.githubusercontent.com/96946274/174240493-1cfec6ab-792a-4c0a-8971-5943c2339be3.png" width=100px>|<img src="https://user-images.githubusercontent.com/96946274/174240826-5ad95862-9744-4315-ab3b-32b0a2c9fb54.png" width=100px>|<img src="https://user-images.githubusercontent.com/96946274/174240948-089eaf31-0c99-4c2e-a84e-95c0dc4cbd33.png" width=100px>|<img src="https://user-images.githubusercontent.com/96946274/174241448-6d768383-2589-4273-ad6d-0b942d98927f.png" width=90px>|

**Back-end**
|정병휘|최바다
|---|---|
|<img src="https://user-images.githubusercontent.com/96946274/174241508-8505d072-8289-461e-a178-89283323e66a.png" width=100px>|<img src="https://user-images.githubusercontent.com/96946274/174241538-48573a90-4cb4-463c-ac35-ae12cffda43a.png" width=100px>|

# 기술 스택

**Front-end**
- HTML5
- Styled-Component
- JavaScript(ES6)
- React.js
- react-router
- slick (*library*)

**Back-end**
- Python
- Django
- MySQL
- Bcrypt
- pyjwt
- RESTful

**Collaboration Tools**
- Git
- GitHub
- Slack
- Trello

# 구현 페이지

- 메인 페이지
- 로그인 페이지
- 로딩 페이지
- 항공편 리스트 페이지
- 결제 페이지

# 내가 구현한 페이지
||Nav|
|------|---|
|설명|- useLocation을 사용하여 페이지 변화할 때마다 nav 스타일링이 변화 하도록 구현 <br> - token 유/무에 따라 변화하는 nav bar 상단 바 구현 <br>|

||Footer|
|------|---|
|설명|-ourtrip의 반복되는 카테고리를 상수데이터로 만들어 map함수를 적용<br>|

||마이 페이지|
|------|---|
|설명|-세가지의 카테고리는 useState에 저장해서 onClick 했을 때 어떤 컴포넌트를 보여줄 것인지 적용 <br> -항공권을 예매하면 바로 마이페이지로 연결해 예정된 여행으로 보여줄 수 있도록 구현|

||예약 상세 페이지|
|------|---|
|설명|- useParams가 id값을 가져와 엔드포인트 뒤에 붙여줘 원하는 데이터를 백엔드에서 원하는 데이터를 요청 <br> - 여행에 따라 다른 예약 상세페이지가 보여질 수 있도록 구현<br>|

---

# Reference
- 이 프로젝트는 마이리얼트립 사이트를 참조하여 학습목적으로 만들었습니다.
- 실무수준의 프로젝트이지만 학습용으로 만들었기 때문에 이 코드를 활용하여 이득을 취하거나 무단 배포할 경우 법적으로 문제될 수 있습니다.
