# 💚Eatgather💚
(같은 곳에 중복된 배달로 인해 유발되는 배달수단의 공기오염이 불필요하다고 느끼는 사람들)을 위한 
       (여러 개의 배달주문을 지도를 통해 쉽게 합칠 수 있는 방식)의 
            (직관적인 UI와 쉬운 접근성이라는 차별점)을 가지는 플랫폼 입니다📗
            
   [💫발표자료 보러가기💫](https://docs.google.com/presentation/d/1VQFQYDtbdfcwvtTlgpvH2kdix3yz8mI-GJ9qeJY9nfQ/edit?usp=sharing)
   
   [🌈Figma 보러가기🌈](https://www.figma.com/file/RVGVr0oUeiGsf5GCT6SIkv/Eatgather?node-id=0%3A1)

## 🛣아이디어 도출 배경🛣

- 환경부와 국토교통부의 자료에 의하면 코로나 시대를 맞아 배달 앱이 인기몰이를 하며 오토바이 수가 빠르게 증가함과 동시에 대기배출오염물질 배출량 또한 함께 늘어났습니다.
    - 환경부 자료에 의하면 50cc 미만 이륜차 1대는 소형승용차 대비 CO 23배, VOC(휘발성유기화합물) 279배, 그리고 미세먼지는 2배 수준으로 더 많이 배출한다고 합니다.
- 또한, 코로나로 인해 시민들이 집에서 머무르는 시간 등이 증가하자, 배달수요가 급증하면서 동시에 배달비도 급등하기 시작했습니다.
    - 배달 업계에 따르면, 올해 들어 다수의 배달대행 업체들이 1월부터 배달대행 수수료를 500~1000원 인상한 것으로 나타났습니다.
    - 지난해 평균 3300원이었던 수도권 기본 배달대행료는 4400원 수준으로 1년 만에 30% 정도 오른 것으로 알려졌고, 심지어는 시간과 지역에 따라 배달비가 1만7000원인 곳까지 등장했다고 합니다.
    - 또한, 배달 최소 주문 금액이 존재하여 원하지도 않는 음식을 금액을 맞추기 위해 시키는 경우도 많이 발생하고 있습니다.

➡️ 따라서, 오토바이 운행량을 줄여 대기 오염물질 배출량을 줄이고 소비자의 부담을 덜어주기 위해 Eatgather 을 개발하게 되었습니다!

## 🥇Eatgather 기대효과🥇

- Eatgather 을 이용하면 오토바이 운행량을 줄일 수 있습니다.
    - 근처에 있는 사람들을 모아서 한번에 주문을 시키므로, 오토바이 운행량을 왕복 n 번에서 1번으로 줄일 수 있습니다. 그만큼 오토바이에서 나오는 대기오염물질 배출량이 줄어들게 되므로 엄청난 기후변화 대응 효과를 누릴 수 있을것으로 예상됩니다.
- 소비자들은 비싼 배달료를 혼자 부담하지 않아도 됩니다.
    - 급등하고 있는 배달료를 더이상 혼자 부담하지 않아도 되고, 배달 최소 주문 금액을 맞추기 위해 원하지 않는 음식을 억지로 시킬 필요도 없습니다.
- 자영업자들이 내는 배달부담액도 줄일 수 있습니다.
    - 현재 자영업자들에게 붙는 배달 수수료는 건당으로 매겨지기 때문에 Eatgather 을 사용하면 계산금액은 커지는 대신 자영업자들이 부담해야 하는 배달 수수료는 상대적으로 줄어들게 됩니다.

## ✅주요 기능✅
- 카카오 로그인, 구글 로그인으로 로그인 (구현 완료)

![스플래시](https://user-images.githubusercontent.com/55349553/152625093-04d2a4ca-196a-46d9-9c38-bf68db2c8dee.png)

- 같이 배달시키고 싶은 주문을 실시간으로 등록하는 기능 (구현 완료)

![주문등록](https://user-images.githubusercontent.com/55349553/152625127-a18b8434-9661-451f-95f1-95b99b79ba22.png)
![상세주문](https://user-images.githubusercontent.com/55349553/152625143-ccd3c687-d611-4b41-be42-d5eb673e7788.png)

- 지도에 등록된 정보들을 핀으로 표시하고 현재 위치에서 거리순으로 recycler view에 보여주는 기능 (구현 완료)

![홈화면](https://user-images.githubusercontent.com/55349553/152625111-d7fcb9f8-4ef6-4c5a-b424-aa9e1e02a540.png)
- 등록한 주문 중에서 같이 하고 싶은 주문자와 채팅 기능 (구현 완료)

- 등록한 주문 중에서 같이 하고 싶은 주문자에게 오픈카톡 연결 기능 (구현 중)

## 💯Google 관련 기능💯
- 구글 로그인을 지원합니다
- 구글에서 제공하는 firebase 를 사용하여 유저관리, 게시물 등록 및 읽어오기 를 수행하고 있습니다.
- 구글에서 제공하는 geocoder 를 이용하여 배달지 주소를 위﹒경도로 전환하여 지도에 표기하였습니다.

## 🌱Eatgather의 확장성🌱
- 배달 주문까지 바로 갈 수 있도록 연결한다면 불필요한 중복된 배달을 줄여 노동력과 비용, 환경보호까지 더 쉽게 이어질 수 있습니다.
- 더 나은 앱 사용환경을 위해 신고 및 평가 기능을 추가 할 예정입니다.

## ✅사용 기술✅
- Ktor: 웹 서버 프레임워크
- Exposed: SQL ORM 프레임워크
- AWS RDS
- AWS EC2
- Firebase Realtime Database
- Google API (OAuth2)
- Kakao SDK
- Naver Map SDK
- Android
- Retrofit
