<!-- 백엔드 전용 변형. 사용법: cp README.backend.md README.md && git commit -am "profile: backend" && git push -->

# 안녕하세요, Junseo입니다

백엔드 개발자입니다. Java/Spring으로 팀 프로젝트를 했고 Python/FastAPI로 혼자 만들어서 배포까지 해본 것도 있습니다. API 설계부터 DB, 테스트, 배포와 모니터링까지 끝까지 가져가는 걸 좋아합니다.

## [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)

동아리 모집·지원자 관리 서비스. 카카오테크캠퍼스에서 3명이 9개월째 만들고 운영 중입니다. 지원서 제출 도메인의 API와 DB를 맡았고 통계, 공지, 이메일 알림은 처음부터 혼자 만들었습니다. 이메일은 이벤트로 분리해서 비동기로 보내고 재시도 가능한 실패와 아닌 걸 나눠 처리했습니다. 조회 쿼리는 join fetch와 프로젝션으로 줄였고 Prometheus/Grafana/Loki 모니터링도 직접 구축했습니다. 테스트 290개.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API. LLM 3곳을 연동하면서 서킷 브레이커로 장애를 격리했고 사용자가 키를 잘못 넣은 401은 장애로 안 셌습니다. 레이트리밋, 요청 추적, 메트릭까지 붙였고 CI에는 테스트와 Trivy 스캔, 커버리지 리포트가 돕니다. 혼자 만들어서 Cloud Run에 올렸습니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 코드리뷰 받으며 진행했고 그 인연으로 Team18_BE까지 이어졌습니다. 학부는 인공지능학부고 AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
