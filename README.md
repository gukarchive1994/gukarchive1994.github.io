# https://gukarchive1994.github.io
tmdb api의 인기 영화 3800건을 크롤링하여 만든 영화 소개 사이트입니다.

# https://github.com/gukarchive1994/guckflix_frontend
프론트엔드는 리액트, 상태관리를 위해 Redux를 사용합니다.

# https://github.com/gukarchive1994/guckflix_backend
AWS EC2 우분투 서버에 스프링부트 앱을 Docker로 배포합니다.  

로컬 테스트 DB는 h2, 운영 DB는 mysql을 사용하고 ORM으로 JPA를 사용했습니다.  

자주 요청하는 메인 페이지의 쿼리 결과를 캐시하기 위해 Redis를 사용했습니다.

깃허브 액션으로 main 브랜치의 변경 사항을 자동 배포합니다.  

배포하는 프론트엔드 서버(github pages)가 HTTPS를 사용하므로 CORS로 인해 백엔드도 HTTPS를 적용했습니다.

### logback을 이용한 예외 로깅
https://exuberant-savory-e0e.notion.site/Spring-logback-1296248714fb80deb137fde9d39803a4

### Slack API를 이용한 예외 알림 기능
https://exuberant-savory-e0e.notion.site/Spring-Slack-1296248714fb80c2ba68e608c160ccdc
