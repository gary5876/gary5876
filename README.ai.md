<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

# 안녕하세요, Junseo입니다 👋

**AI를 서비스로 만드는 개발자**입니다 — 게임 AI 에이전트, LLM 기반 백엔드, 코딩에이전트 자동화 파이프라인까지.
탄탄한 백엔드 기본기(API 설계 · DB · 테스트 · 클라우드 배포) 위에 AI를 얹습니다.

## 🛠 주요 프로젝트

| 프로젝트 | 스택 | 내용 |
|---|---|---|
| [vgc-ai](https://github.com/gary5876/vgc-ai) | Python · scipy · GCP | IEEE CoG 2026 VGC AI 대회 준비 중인 게임 AI — 휴리스틱 평가함수 + LP-minimax(Nash 혼합전략) 팀빌딩. **GCP VM에서 코딩에이전트가 전략을 제안→자가대전 벤치→리뷰→머지하는 자율 실험 루프를 상시 운영**, n=2000 벤치의 95% 신뢰구간 하한을 통과한 변경만 채택. mypy strict · 테스트 345개. 교내 대회 1위(25명) |
| [study-helper-backend](https://github.com/gary5876/study-helper-backend) | FastAPI · LLM API | PDF → LLM(Claude/GPT) 학습 콘텐츠 생성 서비스. 3개 LLM 프로바이더에 서킷 브레이커·지수 백오프 직접 구현, 해시 캐싱으로 중복 LLM 호출 제거, 테스트 280개, Cloud Run 배포 |
| [rag-survey-notes](https://github.com/gary5876/rag-survey-notes) | RAG | RAG 서베이 논문(arXiv:2312.10997) 정독 노트 — 요약·다이어그램·실무 적용 가이드 |
| [capstone-dsc](https://github.com/gary5876/capstone-dsc) | Python · Jupyter | 데이터 품질 점수(DSC)가 ML 모델 성능을 예측하는가 — 3개 데이터셋 × 5종 오염 주입 × 5개 모델 실증 분석 (캡스톤) |

## ⚙️ 기술 스택

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat&logo=googlecloud&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat&logo=githubactions&logoColor=white)

## 📚 교육 · 경험

- **인공지능학부** — 캡스톤 프로젝트 수행
- **카카오테크캠퍼스** 백엔드 과정 완주 — Spring 단계별 미션 코드리뷰 + 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)
