# Game's Cord: 게임 파티 매칭 및 결제 플랫폼

리그오브레전드, 오버워치 등 파티 게임 플레이어를 위한 유료 매칭 및 코인 결제 웹 서비스입니다.

## 🛠 Tech Stack
* **Backend**: Java, Spring Boot, Spring Security, OAuth2, REST API, Swagger
* **Frontend**: React, JavaScript, HTML/CSS
* **Database**: MySQL
* **DevOps/Collaboration**: Git, GitHub, Docker

## 👨‍💻 주요 담당 역할
* **OAuth2 소셜 로그인 구현**
    * Google OAuth2 인증 흐름을 설계하고 구현하여 사용자 편의성 증대[cite: 1].
    * 소셜 계정의 비밀번호 재설정 요청을 차단하는 보안 로직 적용[cite: 1].
* **게임 메이트 API 개발**
    * 게임 메이트 프로필 조회, 등록, 수정 기능을 위한 REST API 설계 및 구현[cite: 1].
    * 이용 가능 시간(start/end) 데이터 처리 로직 개발[cite: 1].
* **초기 프로젝트 환경 설정**
    * Spring Boot 환경 설정, 더미데이터 구성 및 클래스 다이어그램 작성 등 프로젝트 기반 설계 수행[cite: 1].

## 💡 주요 기능
* **회원/인증**: 소셜 로그인(OAuth2) 및 개인화 마이페이지 관리[cite: 1].
* **매칭/검색**: 게임 종류, 티어, 성별, 평점 기반의 다중 필터링 검색[cite: 1].
* **결제 시스템**: 코인 충전, 결제 및 24시간 이내 환불 처리 로직[cite: 1].
* **매칭 및 리뷰**: 매칭 요청/수락/거절 시스템 및 매칭 완료 후 평점/리뷰/신고 기능[cite: 1].
* **알림 시스템**: 브라우저 실시간 알림을 통한 매칭 상태 공유[cite: 1].

## 🔍 Trouble Shooting
* **인증 보안 강화**: 소셜 로그인 사용자가 별도의 비밀번호 변경을 시도할 경우 발생하는 예외 상황을 Spring Security 필터 체인을 통해 차단하여 보안성 확보[cite: 1].
* **API 설계 최적화**: Swagger를 도입하여 프론트엔드 팀과의 API 명세 공유 효율을 높이고, 테스트 과정을 간소화함[cite: 1].

## 👥 팀 구성
* **팀원**: 이택민, 조웅, **서상범(Backend)**, 우영민, 백유진, 이성진, 박기현[cite: 1].
