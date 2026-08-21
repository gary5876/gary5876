<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

# 안녕하세요, Junseo입니다

AI를 서비스로 만드는 쪽에 관심이 많습니다. 게임 AI 에이전트를 만들고 있고 LLM 기반 백엔드도 운영해 봤습니다. 바탕은 백엔드라서 API, DB, 테스트, 배포는 직접 합니다.

## [vgc-ai](https://github.com/gary5876/vgc-ai)

IEEE CoG 2026 포켓몬 VGC AI 대회 준비용 게임 AI입니다. GCP VM에서 코딩에이전트가 전략을 제안하면 자가대전 2000판으로 검증하고, 승률의 95% 신뢰구간 하한이 기존보다 높아야만 채택합니다. n=200에서 좋아 보였던 변경이 n=500 재검증에서는 기각된 적도 있고 그 기록도 코드에 그대로 남아 있습니다. 한번은 다섯 번의 튜닝 시도 내내 학습이 안 되는 줄 알았던 문제가 사실 추론 코드 한 줄의 버그였던 걸 찾아냈습니다. 수업에서 연 25명 리그전에서는 1위를 했습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. 한동안 세션이 끝나지 않고 계속 pending 상태로 남는 버그가 있었는데, 파이프라인 중간에서 실패해도 상태를 되돌리는 코드가 없어서였습니다. 실패 경로를 하나로 모아서 반드시 상태가 되돌아가게 고쳤습니다. LLM 프로바이더 3곳을 서킷 브레이커로 각각 격리했고 같은 PDF가 다시 오면 해시로 잡아서 다시 안 부릅니다. 혼자 만들어서 Cloud Run에 키 없이 배포합니다.

그 외 RAG 서베이 논문을 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes), 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 배경

인공지능학부에서 공부했고 카카오테크캠퍼스 백엔드 과정을 수료했습니다. 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)에서는 지원서 제출 도메인과 통계, 공지, 이메일 알림을 맡았습니다. AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

Python, FastAPI, scipy, Java, Spring Boot, PostgreSQL, Docker, GCP
