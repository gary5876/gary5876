<!-- 백엔드 전용 변형. 사용법: cp README.backend.md README.md && git commit -am "profile: backend" && git push -->

<div align="center">

![header](https://capsule-render.vercel.app/api?type=waving&color=0:1B64DA,100:2698BA&height=200&section=header&text=Junseo%20Go&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Backend%20Engineer%2C%20verifying%20what%20AI%20agents%20build&descAlignY=55&descSize=18)

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=600&size=20&duration=3000&pause=1000&color=1B64DA&center=true&vCenter=true&width=700&lines=%EB%8F%99%EC%95%84%EB%A6%AC%EC%9B%80+%EC%8B%A4%EC%82%AC%EC%9A%A9%EC%9E%90+3%2C500%EB%AA%85%2C+1%EB%85%84%EA%B0%84+%EC%9A%B4%EC%98%81+%EC%A4%91;%ED%85%8C%EC%8A%A4%ED%8A%B8+299%EA%B0%9C%2C+Prometheus+Grafana+Loki+%EC%A7%81%EC%A0%91+%EA%B5%AC%EC%B6%95;Cloud+Run+%EB%B0%B0%ED%8F%AC%2C+CI%EC%97%90+Trivy+%EC%8A%A4%EC%BA%94%EA%B3%BC+%EC%BB%A4%EB%B2%84%EB%A6%AC%EC%A7%80)](https://gary5876.github.io/portfolio/)

[![Portfolio](https://img.shields.io/badge/Portfolio-gary5876.github.io%2Fportfolio-1B64DA?style=flat-square)](https://gary5876.github.io/portfolio/)
[![Email](https://img.shields.io/badge/Email-jerry0622%40naver.com-2698BA?style=flat-square&logo=gmail&logoColor=white)](mailto:jerry0622@naver.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-hi--d--357746213-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hi-d-357746213/)

</div>

---

카카오테크캠퍼스에서 Java/Spring으로 팀 프로젝트를 했고 Python/FastAPI로는 혼자 설계부터 배포까지 해봤습니다. 요즘은 장애가 났을 때 바로 보이게 만드는 쪽에 관심이 많아서 팀 프로젝트에 Prometheus, Grafana, Loki를 직접 붙였고, Temporal로 LLM 파이프라인 결과를 검증하는 과정도 자동화해봤습니다. 앞으로는 OpenTelemetry 같은 관측성 도구나 Celery 같은 분산 태스크 큐를 더 큰 트래픽에서 써보고 싶습니다.

## [Team18_BE](https://github.com/kakao-tech-campus-3rd-step3/Team18_BE)

동아리 모집, 지원자 관리 서비스 [Dongariu-um](https://github.com/kakao-tech-campus-3rd-step3/Team18_FE)의 백엔드입니다. 카카오테크캠퍼스에서 백엔드 3명, 프론트 3명이 1년째 만들고 있고 지금도 운영하고 있습니다. 저는 백엔드에서 지원서 제출 도메인의 API와 DB 모델링을 맡았고 통계와 공지는 처음부터 끝까지 혼자 만들었으며 이메일 알림도 대부분 제가 작성했습니다. 지원서 목록 조회가 느려서 join fetch와 프로젝션으로 쿼리를 줄였고, 이메일 발송은 이벤트로 분리해 재시도 가능한 실패와 아닌 실패를 나눠 처리했습니다. 장애를 바로 보려고 Prometheus, Grafana, Loki 모니터링을 팀에서 직접 붙였고, 테스트는 계층별로 299개를 쌓았습니다.

## [study-helper-backend](https://github.com/gary5876/study-helper-backend)

PDF를 올리면 LLM으로 학습 노트와 퀴즈를 만들어주는 서비스입니다. 백엔드(FastAPI)뿐 아니라 [웹](https://github.com/gary5876/study-helper-web)(Next.js)과 [모바일](https://github.com/gary5876/study-helper-mobile)(React Native) 클라이언트까지 세 레포 전부 혼자 만들었습니다. 백엔드는 Claude, GPT, TimelyGPT 세 개 LLM API를 연동하면서 프로바이더별로 서킷 브레이커를 붙여 장애를 격리했고, 사용자가 키를 잘못 넣은 401까지 장애로 세면 브레이커가 엉뚱하게 열리길래 그건 카운트에서 뺐습니다. Cloud Run에 키 없이 배포하고 CI에는 테스트와 Trivy 스캔, 커버리지 리포트가 돕니다.

## 배경

카카오테크캠퍼스 백엔드 과정을 수료했습니다. [spring-gift](https://github.com/gary5876/spring-gift-order) 미션을 코드리뷰 받으며 진행했고 그 인연으로 Team18_BE까지 이어졌습니다. 학부는 인공지능학부고 AWS Certified Cloud Practitioner와 AI Practitioner를 갖고 있습니다.

![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white)
![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white)

---

<div align="center">

![streak stats](https://streak-stats.demolab.com/?user=gary5876&theme=default&hide_border=true&background=FFFFFF00&ring=1B64DA&fire=2698BA&currStreakLabel=1B64DA)

</div>
