# 안녕하세요, Junseo입니다

백엔드 개발자입니다. Java와 Spring으로 팀 프로젝트를 했고 Python과 FastAPI로 혼자 만들어 배포한 서비스도 있습니다. 요즘은 코딩에이전트로 개발 과정을 자동화하는 실험을 하고 있습니다. 시켜놓고 믿는 방식이 아니라 검증 게이트를 두고 통과한 것만 받는 방식입니다.

## 어디부터 보면 좋을지

### [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE) (Java, Spring Boot)

대학 동아리 모집과 지원자 관리를 해주는 서비스입니다. 카카오테크캠퍼스에서 3명이 9개월 동안 만들어 운영했습니다. 저는 지원서 제출 도메인의 API 설계와 DB 모델링을 맡았고 통계, 공지, 이메일 알림은 처음부터 끝까지 만들었습니다. 이메일 발송은 이벤트로 분리해 비동기 처리하고 실패를 재시도 가능한 것과 아닌 것으로 분류해 대응했습니다. 지원서 조회 쪽은 join fetch와 프로젝션으로 불필요한 쿼리를 줄였습니다. 모니터링은 Prometheus와 Grafana, Loki를 팀에서 직접 구축했고 비즈니스 지표를 등록해 Discord 알림까지 연결했습니다. 테스트는 계층별로 나눠 290개를 쌓았습니다.

### [vgc-ai](https://github.com/gary5876/vgc-ai) (Python)

IEEE CoG 2026 포켓몬 VGC AI 대회를 준비 중인 게임 AI입니다. 수업에서 열린 25명 리그전에서는 1위를 했습니다. 사실 에이전트 자체보다 실험 방식을 보여드리고 싶은 레포입니다. GCP VM에서 코딩에이전트가 전략을 제안하면 n=2000 자가대전 벤치의 95% 신뢰구간 하한을 통과해야만 채택됩니다. 실패한 실험도 지우지 않고 원인 분석과 함께 남겨뒀습니다. `policies/selection.py` 상단에 있습니다.

### [study-helper-backend](https://github.com/gary5876/study-helper-backend) (Python, FastAPI)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. 외부 LLM API 세 곳을 연동하면서 장애를 서킷 브레이커로 격리했고 사용자가 API 키를 잘못 넣은 401은 장애로 세지 않도록 분류했습니다. 같은 PDF가 다시 오면 해시로 잡아 호출 비용을 줄였고 레이트리밋과 요청 추적, 메트릭 같은 운영 장치도 붙였습니다. 혼자 만들었고 CI와 Cloud Run 배포 구성까지 직접 했습니다.

이 외에 RAG 서베이 논문을 정독하고 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes)와 데이터 품질 점수가 ML 모델 성능을 예측하는지 실증해 본 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 자격

AWS Certified Cloud Practitioner와 AWS Certified AI Practitioner를 취득했습니다. study-helper-backend와 vgc-ai를 GCP에 올리면서 클라우드 쪽 기본기를 다졌고 그 연장선입니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 단계별로 코드리뷰 받으며 진행했고 그 과정이 위의 Team18_BE 팀 프로젝트로 이어졌습니다. 학부는 인공지능학부입니다.

주로 쓰는 것: Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
