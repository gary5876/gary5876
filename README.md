# 안녕하세요, Junseo입니다

백엔드 개발자입니다. Java와 Spring으로 팀 프로젝트를 했고 Python과 FastAPI로 혼자 만들어 배포한 서비스도 있습니다. 요즘은 코딩에이전트로 개발 과정을 자동화하는 실험을 하고 있습니다. 시켜놓고 믿는 방식이 아니라 검증 게이트를 두고 통과한 것만 받는 방식입니다.

## 어디부터 보면 좋을지

### [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE) (Java, Spring Boot)

대학 동아리 모집과 지원자 관리를 해주는 서비스입니다. 카카오테크캠퍼스에서 3명이 9개월 동안 만들었고 저는 커밋 403개를 쌓았습니다. 지원서 제출 도메인을 주로 맡았고 통계와 공지, 이메일 알림 기능은 처음부터 끝까지 제가 만들었습니다. 코드를 보신다면 지원서 제출 흐름(`domain/application`)과 계층별로 나눠 쌓은 테스트 290개를 봐주세요. Prometheus와 Grafana, Loki로 모니터링 환경도 팀에서 직접 구축해 운영했습니다.

### [vgc-ai](https://github.com/gary5876/vgc-ai) (Python)

IEEE CoG 2026 포켓몬 VGC AI 대회를 준비 중인 게임 AI입니다. 수업에서 열린 25명 리그전에서는 1위를 했습니다. 사실 에이전트 자체보다 실험 방식을 보여드리고 싶은 레포입니다. GCP VM에서 코딩에이전트가 전략을 제안하면 n=2000 자가대전 벤치의 95% 신뢰구간 하한을 통과해야만 채택됩니다. 실패한 실험도 지우지 않고 원인 분석과 함께 남겨뒀습니다. `policies/selection.py` 상단에 있습니다.

### [study-helper-backend](https://github.com/gary5876/study-helper-backend) (Python, FastAPI)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. 혼자 만들었고 CI와 Cloud Run 배포 구성까지 직접 했습니다. LLM 프로바이더 3곳의 장애를 각각 서킷 브레이커로 격리했는데 사용자가 API 키를 잘못 넣은 경우까지 실패로 세면 안 되니까 401은 카운트에서 뺐습니다. 같은 PDF가 다시 올라오면 해시로 알아채서 LLM을 다시 부르지 않습니다.

이 외에 RAG 서베이 논문을 정독하고 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes)와 데이터 품질 점수가 ML 모델 성능을 예측하는지 실증해 본 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 단계별로 코드리뷰 받으며 진행했고 그 과정이 위의 Team18_BE 팀 프로젝트로 이어졌습니다. 학부는 인공지능학부입니다.

주로 쓰는 것: Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
