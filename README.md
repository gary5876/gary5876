# 안녕하세요, Junseo입니다

백엔드 개발자입니다. Java/Spring으로 팀 프로젝트를 했고 Python/FastAPI로 혼자 만들어서 배포까지 해본 것도 있습니다. 요즘은 코딩에이전트를 개발 과정에 끼워 넣는 실험을 하는 중인데 결과를 그냥 믿기보다 검증 게이트를 두고 통과한 것만 받는 쪽으로 하고 있습니다.

## [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)

동아리 모집·지원자 관리 서비스. 카카오테크캠퍼스에서 3명이 9개월째 만들고 운영 중입니다. 지원서 제출 도메인의 API와 DB를 맡았고 통계, 공지, 이메일 알림은 처음부터 혼자 만들었습니다. 이메일은 이벤트로 분리해서 비동기로 보내고 재시도 가능한 실패와 아닌 걸 나눠 처리했습니다. 조회 쿼리는 join fetch와 프로젝션으로 줄였고 Prometheus/Grafana/Loki 모니터링도 직접 구축했습니다. 테스트 290개.

## [vgc-ai](https://github.com/gary5876/vgc-ai)

IEEE CoG 2026 포켓몬 VGC AI 대회 준비용 게임 AI. 수업 리그전(25명)에서 1위. GCP VM에서 코딩에이전트가 전략을 제안하면 n=2000 자가대전으로 검증하고 95% 신뢰구간 하한을 못 넘으면 버립니다. 실패한 실험도 원인과 같이 `policies/selection.py`에 남겨뒀습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API. LLM 3곳을 연동하면서 서킷 브레이커로 장애를 격리했고 사용자가 키를 잘못 넣은 401은 장애로 안 셌습니다. 같은 PDF는 해시로 잡아서 다시 안 부릅니다. 레이트리밋, 요청 추적, 메트릭까지 붙였고 혼자 만들어서 Cloud Run에 올렸습니다.

그 외 RAG 서베이 논문을 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes), 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 코드리뷰 받으며 진행했고 그 인연으로 Team18_BE까지 이어졌습니다. 학부는 인공지능학부고 AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Java, Kotlin, Spring Boot, Python, FastAPI, MySQL, PostgreSQL, Redis, Docker, AWS, GCP
