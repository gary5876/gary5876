<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

# 안녕하세요, Junseo입니다

AI를 서비스로 만드는 쪽에 관심이 많습니다. 게임 AI 에이전트를 만들고 있고 LLM 기반 백엔드도 운영해 봤습니다. 바탕은 백엔드라서 API, DB, 테스트, 배포는 직접 합니다.

## [vgc-ai](https://github.com/gary5876/vgc-ai)

IEEE CoG 2026 포켓몬 VGC AI 대회 준비용 게임 AI. 수업 리그전(25명)에서 1위. GCP VM에서 코딩에이전트가 전략을 제안하면 n=2000 자가대전으로 검증하고 95% 신뢰구간 하한을 못 넘으면 버립니다. 실패한 실험도 원인과 같이 `policies/selection.py`에 남겨뒀습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API. LLM 3곳을 연동하면서 서킷 브레이커로 장애를 격리했고 같은 PDF는 해시로 잡아서 다시 안 부릅니다. 혼자 만들어서 Cloud Run에 올렸습니다.

그 외 RAG 서베이 논문을 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes), 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 배경

인공지능학부에서 공부했고 카카오테크캠퍼스 백엔드 과정을 수료했습니다. 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)에서는 지원서 제출 도메인과 통계, 공지, 이메일 알림을 맡았습니다. AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Python, FastAPI, scipy, Java, Spring Boot, PostgreSQL, Docker, GCP
