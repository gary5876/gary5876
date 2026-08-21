<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

# 안녕하세요, Junseo입니다

AI를 서비스로 만드는 쪽에 관심이 많습니다. 게임 AI 에이전트를 만들고 있고 LLM 기반 백엔드도 혼자 설계해서 운영해 봤습니다. 바탕은 백엔드라서 API, DB, 장애 대응, 배포는 직접 합니다.

## [vgc-ai](https://github.com/gary5876/vgc-ai)

IEEE CoG 2026 포켓몬 VGC AI 대회를 준비하는 게임 AI입니다. GCP VM에 코딩에이전트를 올려서 전략을 제안하고 자가대전 2000판으로 검증한 뒤 신뢰구간 기준을 통과한 것만 merge하는 루프를 상시 돌립니다. 좋아 보이던 변경이 재검증에서 기각되는 경우도 그대로 기록해 둡니다. 수업에서 연 25명 리그전에서는 1위를 했습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. Claude·GPT·TimelyGPT 세 개 LLM API를 연동하면서 프로바이더별로 서킷 브레이커를 붙여 장애를 격리했고, 같은 PDF가 다시 오면 해시로 잡아서 LLM을 다시 안 부릅니다. 혼자 설계해서 Cloud Run에 키 없이 배포합니다.

그 외 RAG 서베이 논문을 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes), 데이터 품질 점수로 ML 모델 성능을 예측해본 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 배경

인공지능학부에서 공부했고 카카오테크캠퍼스 백엔드 과정을 수료했습니다. 6명(백엔드 3, 프론트 3) 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)에서는 지원서 제출 도메인의 API와 DB 모델링, 통계·공지·이메일 알림을 맡았습니다. AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Python, FastAPI, scipy, Java, Spring Boot, PostgreSQL, Docker, GCP
