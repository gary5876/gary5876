<!-- 백엔드 전용 변형. 사용법: cp README.backend.md README.md && git commit -am "profile: backend" && git push -->

# 안녕하세요, 백엔드 개발자 Junseo입니다 👋

**Java · Kotlin · Spring Boot** 중심의 백엔드 개발자입니다.
REST API 설계, DB 모델링, 계층별 테스트, 클라우드 배포·모니터링까지 — 서비스를 만들고 끝까지 운영하는 것을 좋아합니다.

## 🛠 주요 프로젝트

| 프로젝트 | 스택 | 내용 |
|---|---|---|
| [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE) | Java · Spring Boot · Redis | 대학 동아리 모집·지원자 관리 서비스 — 카카오테크캠퍼스 4인 팀 프로젝트(9개월). JWT 클레임 기반 동아리별 역할 인가(`@PreAuthorize` SpEL 커스텀 빈, 22개 엔드포인트), 단위·슬라이스·리포지토리·통합 4계층 테스트 290개, Prometheus·Grafana·Loki 모니터링 + 비즈니스 메트릭, ECR→EC2 배포·Flyway. 통계 도메인 설계·구현 담당 |
| BookStore *(공개 전환 준비 중)* | Kotlin · Spring Boot · GCP | P2P 전자책 마켓 — 서버와 Android 앱 단독 구현. Refresh 토큰 해시 저장+rotation, OAuth 계정 탈취 방어, 포트/어댑터 아키텍처, Testcontainers(MySQL 8.4) E2E 포함 테스트 241개, Cloud Run 배포 |
| [study-helper-backend](https://github.com/gary5876/study-helper-backend) | FastAPI · PostgreSQL · GCP | PDF → LLM 학습 콘텐츠 생성 API. 서킷 브레이커·지수 백오프 직접 구현, 해시 캐싱, 테스트 280개, CI(Trivy·ruff·codecov), Cloud Run 키리스(WIF) 배포 |

## ⚙️ 기술 스택

![Java](https://img.shields.io/badge/Java-007396?style=flat&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat&logo=redis&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat&logo=amazonwebservices&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat&logo=grafana&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## 📚 교육 · 경험

- **카카오테크캠퍼스** 백엔드 과정 — Spring 단계별 미션([spring-gift](https://github.com/gary5876/spring-gift-order) 시리즈)을 코드리뷰 받으며 완주 후, 팀 프로젝트 Team18_BE 수행
- 코딩에이전트·LLM을 개발 프로세스에 적극 활용 — [vgc-ai](https://github.com/gary5876/vgc-ai)에서 GCP VM 자율 실험 루프(제안→벤치→리뷰→머지) 운영
