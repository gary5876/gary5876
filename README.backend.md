<!-- 백엔드 전용 변형. 사용법: cp README.backend.md README.md && git commit -am "profile: backend" && git push -->

# 안녕하세요, Junseo입니다

백엔드 개발자입니다. Java/Spring으로 팀 프로젝트를 했고 Python/FastAPI로 혼자 만들어서 배포까지 해본 것도 있습니다. API 설계부터 DB, 테스트, 배포와 모니터링까지 끝까지 가져가는 걸 좋아합니다.

## [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)

동아리 모집·지원자 관리 서비스입니다. 카카오테크캠퍼스에서 3명이 9개월째 만들고 있고 지금도 운영 중입니다. 저는 지원서 제출 도메인을 맡았고 통계·공지·이메일 알림 기능은 혼자 처음부터 끝까지 만들었습니다. 인가 쪽에서 신경 쓴 부분이 하나 있는데, 권한 없는 사용자가 존재하지 않는 동아리에 접근하면 403 대신 404를 돌려줍니다. 그 동아리가 있는지 없는지조차 알려주지 않으려는 의도고 이유는 코드 주석에 남겨뒀습니다. 테스트는 계층별로 나눠서 290개를 쌓았고 모니터링은 Prometheus·Grafana·Loki를 팀에서 직접 붙여서 비즈니스 지표까지 확인합니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. 한동안 세션이 끝나지 않고 계속 pending 상태로 남는 버그가 있었는데, 파이프라인 중간에서 실패해도 상태를 되돌리는 코드가 없어서였습니다. 실패 경로를 하나로 모아서 반드시 상태가 되돌아가게 고쳤습니다. LLM 프로바이더 3곳을 서킷 브레이커로 각각 격리했고, 사용자가 키를 잘못 넣은 401까지 장애로 세면 브레이커가 엉뚱하게 열리니까 그건 카운트에서 뺐습니다. 혼자 만들어서 Cloud Run에 키 없이 배포하고 CI에는 테스트와 Trivy 스캔, 커버리지 리포트가 돕니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 코드리뷰 받으며 진행했고 그 인연으로 Team18_BE까지 이어졌습니다. 학부는 인공지능학부고 AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
