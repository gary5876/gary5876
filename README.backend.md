<!-- 백엔드 전용 변형. 사용법: cp README.backend.md README.md && git commit -am "profile: backend" && git push -->

# 안녕하세요, Junseo입니다

카카오테크캠퍼스에서 Java/Spring으로 팀 프로젝트를 했고 Python/FastAPI로는 혼자 설계부터 배포까지 해봤습니다. 요즘은 API를 짜는 것보다 장애가 왜 났는지, 어떻게 하면 다시 안 나는지를 더 오래 들여다봅니다. 앞으로는 운영 경험을 더 쌓아서 트래픽이 큰 서비스도 다뤄보고 싶습니다.

## [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)

동아리 모집·지원자 관리 서비스 [Dongariu-um](https://github.com/kakao-tech-campus-3rd-step3/Team18_FE)의 백엔드입니다. 카카오테크캠퍼스에서 백엔드 3명, 프론트 3명이 1년째 만들고 있고 지금도 운영하고 있습니다. 저는 백엔드에서 지원서 제출 도메인의 API와 DB 모델링을 맡았고 통계와 공지는 처음부터 끝까지 혼자 만들었으며 이메일 알림도 대부분 제가 작성했습니다. 지원서 목록 조회가 느려서 join fetch와 프로젝션으로 쿼리를 줄였고, 이메일 발송은 이벤트로 분리해 재시도 가능한 실패와 아닌 실패를 나눠 처리했습니다. 장애를 바로 보려고 Prometheus·Grafana·Loki 모니터링을 팀에서 직접 붙였고, 테스트는 계층별로 299개를 쌓았습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. Claude·GPT·TimelyGPT 세 개 LLM API를 연동하면서 프로바이더별로 서킷 브레이커를 붙여 장애를 격리했고, 사용자가 키를 잘못 넣은 401까지 장애로 세면 브레이커가 엉뚱하게 열리길래 그건 카운트에서 뺐습니다. 같은 PDF가 다시 오면 해시로 잡아서 LLM을 다시 안 부르고, 레이트리밋과 요청 추적, 메트릭까지 붙였습니다. 혼자 설계해서 Cloud Run에 키 없이 배포하고 CI에는 테스트와 Trivy 스캔, 커버리지 리포트가 돕니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 코드리뷰 받으며 진행했고 그 인연으로 Team18_BE까지 이어졌습니다. 학부는 인공지능학부고 AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
