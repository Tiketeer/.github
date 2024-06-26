## Hi there 👋

<!-- # Tiketeer -->

안녕하세요! 환영합니다.

저희 팀은 **Java와 Spring 프레임워크를 기반으로 한 티켓 예매 웹사이트 구현**을 목표로 4명의 백엔드 개발자가 함께하고 있습니다.

## Before start 🧙

Tiketeer는 사용자와 판매자 모두를 위한 티켓 예매 플랫폼으로, **사용자는 편리하게 티켓을 예매하고, 판매자는 자신이 주최하는 행사를 등록하고 관리**할 수 있습니다.

사용자는 **간편한 결제 시스템**을 통해 손쉽게 티켓을 구매할 수 있으며, 판매자는 자신이 주최하는 이벤트를 사이트에 등록하고, 티켓 가격, 예매 가능 시간, 장소 등의 정보를 관리할 수 있습니다.

저희는 팀 논의를 통해 정의한 규칙과 가이드라인에 따라 공동으로 Tiketeer 프로젝트를 개발하며 다양한 문제 상황을 해결하기 위해 노력하고 있습니다.

팀 규칙은 [엔지니어링 가이드라인](https://www.notion.so/tiketeer/3d5542da41b145debf507f4aff7a45eb)에서 확인하실 수 있습니다.

## Build ⚙️

모든 서버의 빌드 순서입니다.
1. Tiketeer-Waiting repo의 docker image 빌드.
    - `docker build -t tiketeer-waiting .`
2. Tiketeer-FE repo의 docker image 빌드.
    - `docker build -t tiketeer-fe .` 
4. Tiketeer-be repo의 `docker-compose.prod.yml` 실행
    - `docker compose -f docker-compose.prod.yml up -d`

주의 사항
- Tiketeer-be repo resource 경로에 `application-prod.yml` 파일이 있어야 합니다.
  - `application-prod.yml` 파일은 `readme.md`를 참고하여 만들 수 있습니다.
- Tiketeer-Waiting repo resource 경로에 `application.yml`, `application-prod.yml` 파일이 있어야 합니다.
  - `application.yml`과 `application-prod.yml` 파일은 `readme.md`를 참고하여 만들 수 있습니다.

## Contanct 🌈

질문이나 제안사항이 있으시다면, dla0510@naver.com 으로 연락주세요.

👩‍💻 프로젝트에 관련된 자료는 [Tiketeer팀 노션 페이지](https://www.notion.so/tiketeer/4de780acc5a246dc9732e5541a00c47e?v=c259bdfa5ff24409825e70cbfba07f89)에서 확인할 수 있습니다
