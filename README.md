# Baedo-stock-program

<h1>1. 요구사항 분석</h1>

1) 실시간 주식 시세 제공 <br>
   프로그램은 사용자에게 실시간으로 주식 시세를 제공해야 합니다. 이를 위해서는 주식 시장에서 주식 가격과 거래량을 실시간으로 가져와야 합니다.

2) 주식 차트 및 그래프 표시
   사용자가 특정 주식의 가격 동향을 시각적으로 파악할 수 있도록 주식 차트나 그래프를 표시해야 합니다. 이를 통해 사용자는 주식의 변동성과 추세를 파악할 수 있습니다.

3) 주식 거래 기능
   사용자가 주식을 매수하거나 매도할 수 있는 거래 기능이 제공되어야 합니다. 사용자는 거래 화면에서 주식을 선택하고 거래를 실행할 수 있어야 합니다.

계정 및 포트폴리오 관리: 사용자는 개인 계정을 생성하고 포트폴리오를 관리할 수 있어야 합니다. 포트폴리오에는 사용자가 보유한 주식의 종류와 수량, 현재 시세 등이 포함되어야 합니다.

알림 기능: 프로그램은 사용자에게 중요한 이벤트나 정보를 알릴 수 있는 알림 기능이 있어야 합니다. 예를 들어, 사용자가 관심 있는 주식의 가격이 특정 기준을 넘어설 때 알림을 받을 수 있어야 합니다.

보안 및 규정 준수: 주식 거래와 관련된 프로그램은 보안과 규정 준수에 매우 민감합니다. 따라서 프로그램은 사용자의 개인 정보와 자산을 안전하게 보호하고, 금융 규정에 준수해야 합니다.

거래 기록 및 보고서: 사용자는 자신의 거래 기록과 포트폴리오 성과를 확인할 수 있는 기능이 제공되어야 합니다. 이를 통해 사용자는 자신의 거래 활동을 분석하고 향후 전략을 계획할 수 있습니다.


2. 기술 스택 선택
프론트엔드: React

React를 사용하여 사용자 인터페이스를 개발합니다.
주식 가격과 관련된 정보를 보여주는 대시보드를 구현합니다.
주식 거래를 위한 주문 화면 및 포트폴리오 관리 화면을 디자인합니다.

백엔드: Node.js, Java(Spring Boot)

Spring Boot를 사용하여 RESTful API를 개발합니다.
주식 데이터베이스를 관리하고 주식 시장의 상태를 조회합니다.
주식 거래에 필요한 주문 관리, 포트폴리오 관리 및 사용자 인증과 관련된 기능을 구현합니다.

서버 (Node.js):

Node.js를 사용하여 클라이언트와 서버 간의 통신을 관리합니다.
주식 시세 업데이트 및 실시간 데이터 전송을 처리합니다.

데이터베이스: MySQL
3. 프로젝트 구조 설계
클라이언트-서버 아키텍처 설계

RESTful API 정의 (백엔드)
UI 디자인 및 레이아웃 구성 (프론트엔드)

4. 백엔드 개발
주식 거래, 주가 조회, 포트폴리오 관리 등의 API 구현
데이터베이스 모델링 및 스키마 설계
API 보안 및 인증 설정

5. 프론트엔드 개발
주식 시세 조회, 거래 화면, 포트폴리오 관리 등의 UI 개발
백엔드 API와의 통신을 위한 클라이언트 코드 작성

6. 테스트 및 디버깅
유닛 테스트, 통합 테스트를 통해 프로그램의 안정성과 신뢰성을 검증합니다.
버그를 수정하고 코드 품질을 향상시킵니다.

7. 배포 및 유지보수
프로그램을 서버에 배포하고 사용자에게 공개합니다.
사용자 피드백을 수집하고 필요한 경우 업데이트를 수행합니다.
