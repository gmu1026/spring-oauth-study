spring-oauth-study
---
#프로젝트 목표 및 설명
- Spring Security, OAuth Client를 이용한 소셜 로그인 기능 구현
- Redis를 세션 저장소로 이용하여 JWT 기반으로 세션 관리
- TDD, 클린 코드를 지향
- 카카오, 구글, 깃허브 소셜 로그인 지원


---
개발 환경
- MacOS
- Java 8
- SpringBoot 2.6.3
- Redis
- JUnit5

---
설치방법
- 소셜 플랫폼에 서비스 등록 Client Id와 Secret 발급
- application-oauth.yml 파일에 소셜 플랫폼 별 Client ID, Secret 입력
- MySQL 데이터 베이스 생성
> create database spring_study_member
- application-db.yml에 DB정보 입력
