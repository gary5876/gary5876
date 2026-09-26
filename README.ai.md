<!-- AI 전용 변형. 사용법: cp README.ai.md README.md && git commit -am "profile: ai" && git push -->

<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1B64DA,100:2698BA&height=200&section=header&text=Junseo%20Go&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%2C%20verifying%20what%20AI%20agents%20build&descAlignY=55&descSize=18)

![AI 조사 검증](https://img.shields.io/badge/AI_위임_조사-6건_중_3건_오류_검증-1B64DA?style=for-the-badge)
![RAG 논문](https://img.shields.io/badge/RAG_서베이_논문-원문_정독-2698BA?style=for-the-badge)
![VGC 리그전 1위](https://img.shields.io/badge/VGC_교내_리그전-25팀_중_1위-1B64DA?style=for-the-badge)

[![Portfolio](https://img.shields.io/badge/Portfolio-gary5876.github.io%2Fportfolio-1B64DA?style=flat-square)](https://gary5876.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-jerry0622%40naver.com-2698BA?style=flat-square&logo=gmail&logoColor=white)](mailto:jerry0622@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hi--d--357746213-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hi-d-357746213/)
![Profile Views](https://komarev.com/ghpvc/?username=gary5876&color=1B64DA&style=flat-square&label=PROFILE+VIEWS)

</div>

---

카카오테크캠퍼스에서 백엔드를 배웠고 게임 AI 에이전트를 만들었고 LLM 기반 백엔드도 혼자 설계해서 운영해 봤습니다. 요즘은 Temporal로 LLM 파이프라인 결과를 검증하는 과정을 자동화하는 데 관심이 많습니다. 앞으로는 RAG 파이프라인을 실무 규모로 직접 구성해보고 싶습니다.

## 🎮 [vgc-ai](https://github.com/gary5876/vgc-ai)

IEEE CoG 2026 포켓몬 VGC AI 대회를 목표로 시작했지만 대회 제출은 하지 않은 게임 AI입니다. GCP VM에 코딩에이전트를 올려서 전략을 제안하게 하고, 자가대전 2000판으로 검증해 신뢰구간 기준을 통과한 것만 merge하는 방식으로 운영했습니다. 좋아 보이던 변경이 재검증에서 기각된 경우도 그대로 기록해 뒀습니다. 수업 내 25팀 리그전에서 1위를 했습니다.

## 📄 [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 서비스입니다. 백엔드(FastAPI)뿐 아니라 [웹](https://github.com/gary5876/study-helper-web)(Next.js)과 [모바일](https://github.com/gary5876/study-helper-mobile)(React Native) 클라이언트까지 세 레포 전부 혼자 만들었습니다. 백엔드는 Claude, GPT, TimelyGPT 세 개 LLM API를 연동하면서 프로바이더별로 서킷 브레이커를 붙여 장애를 격리했고, 같은 PDF가 다시 오면 해시로 잡아서 LLM을 다시 안 부릅니다. Cloud Run에 키 없이 배포합니다.

그 외 RAG 서베이 논문을 정리한 [rag-survey-notes](https://github.com/gary5876/rag-survey-notes), 데이터 품질 점수로 ML 모델 성능을 예측해본 캡스톤 [capstone-dsc](https://github.com/gary5876/capstone-dsc)가 있습니다.

## 🎓 배경

인공지능학부에서 공부했고 카카오테크캠퍼스 백엔드 과정을 수료했습니다. 6명(백엔드 3, 프론트 3) 팀 프로젝트 [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)에서는 지원서 제출 도메인의 API와 DB 모델링, 통계, 공지, 이메일 알림을 맡았습니다. AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

<img src="https://skillicons.dev/icons?i=python,fastapi,java,spring,postgres,docker,gcp&theme=dark" alt="tech stack" />

---

## 📈 활동

<div align="center">

<img height="185" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=gary5876&theme=nord_dark" alt="GitHub stats" />
<img height="185" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=gary5876&theme=nord_dark" alt="Most commit language" />
<img height="185" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=gary5876&theme=nord_dark&utcOffset=9" alt="Productive time" />

![commit grid](https://ghchart.rshah.org/1B64DA/gary5876)

<img src="profile-3d-contrib/profile-night-view.svg" width="96%" alt="3D contribution graph" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/gary5876/gary5876/output/github-contribution-grid-snake-dark.svg" />
  <img alt="snake" src="https://raw.githubusercontent.com/gary5876/gary5876/output/github-contribution-grid-snake.svg" width="96%" />
</picture>

</div>

![footer](https://capsule-render.vercel.app/api?type=rect&color=0:1B64DA,100:2698BA&height=4)
