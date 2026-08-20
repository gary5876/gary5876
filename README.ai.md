<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

# 안녕하세요, Junseo입니다

AI를 서비스로 만드는 쪽에 관심이 많습니다. 게임 AI 에이전트를 만들고 있고 LLM 기반 백엔드도 운영해 봤습니다. 바탕은 백엔드라서 API 설계와 DB, 테스트, 배포를 직접 합니다.

## 어디부터 보면 좋을지

### [vgc-ai](https://github.com/gary5876/vgc-ai) (Python)

IEEE CoG 2026 포켓몬 VGC AI 대회를 준비 중인 게임 AI입니다. 수업에서 열린 25명 리그전에서는 1위를 했습니다. 사실 에이전트 자체보다 실험 방식을 보여드리고 싶은 레포입니다. GCP VM에서 코딩에이전트가 전략을 제안하면 n=2000 자가대전 벤치의 95% 신뢰구간 하한을 통과해야만 채택됩니다. 실패한 실험도 지우지 않고 원인 분석과 함께 남겨뒀습니다. `policies/selection.py` 상단에 있습니다.

### [study-helper-backend](https://github.com/gary5876/study-helper-backend) (Python, FastAPI)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 API입니다. 외부 LLM API 세 곳을 연동하면서 장애를 서킷 브레이커로 격리했고 같은 PDF가 다시 오면 해시로 잡아 호출 비용을 줄였습니다. 혼자 만들었고 CI와 Cloud Run 배포 구성까지 직접 했습니다.

이 외에 RAG 서베이 논문을 정독하고 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes)와 데이터 품질 점수가 ML 모델 성능을 예측하는지 실증해 본 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 자격

AWS Certified Cloud Practitioner를 취득했습니다. study-helper-backend와 vgc-ai를 GCP에 올리면서 다진 클라우드 기본기의 연장선입니다.

## 배경

인공지능학부에서 공부했고 카카오테크캠퍼스 백엔드 과정을 수료했습니다. 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)에서는 지원서 제출 도메인과 통계, 공지, 이메일 알림을 맡았습니다.

주로 쓰는 것: Python, FastAPI, scipy, Java, Spring Boot, PostgreSQL, Docker, GCP
