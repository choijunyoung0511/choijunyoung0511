<h2>Junyoung Choi</h2>

<p>
Backend Developer · Java / Spring Boot · Cloud<br>
문제가 생기면 끝까지 파고들어 해결하는 개발자입니다.
</p>

<p>
<a href="mailto:yj766352@gmail.com"><img src="https://img.shields.io/badge/Email-yj766352@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white"/></a>
<a href="https://www.notion.so/Dashboard-1c780bd9fdde800a80b2c579ef4a61c6?pvs=4"><img src="https://img.shields.io/badge/Portfolio-Notion-000000?style=flat-square&logo=notion&logoColor=white"/></a>
<a href="https://from.it.kr"><img src="https://img.shields.io/badge/Live-from.it.kr-4285F4?style=flat-square&logo=googlechrome&logoColor=white"/></a>
</p>

---

### About

- 한국폴리텍대학 서울강서캠퍼스 빅데이터소프트웨어과
- Spring Boot 기반 백엔드 개발, 클라우드 환경(AWS · NCP · K-PaaS) 배포 경험
- 관심 분야: **Backend Architecture**, **Cloud Infrastructure**, **AI 서비스 연동**
- 목표: 트래픽과 장애를 이해하는 클라우드 기반 백엔드 엔지니어

---

### Tech Stack

| Category | Stack |
|:--|:--|
| **Language** | ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white) ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) |
| **Backend** | ![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-59666C?style=flat-square&logo=hibernate&logoColor=white) ![MyBatis](https://img.shields.io/badge/MyBatis-000000?style=flat-square) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) |
| **Database** | ![MariaDB](https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white) ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white) |
| **Infra** | ![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white) ![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white) ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) |
| **AI / API** | ![OpenAI](https://img.shields.io/badge/OpenAI_API-412991?style=flat-square&logo=openai&logoColor=white) ![Claude](https://img.shields.io/badge/Claude_API-D97757?style=flat-square&logo=anthropic&logoColor=white) ![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) |
| **Tools** | ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![IntelliJ](https://img.shields.io/badge/IntelliJ_IDEA-000000?style=flat-square&logo=intellijidea&logoColor=white) ![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white) ![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white) |

---

### Projects

#### FROM — AI 독서 지원 플랫폼 &nbsp; [![Live](https://img.shields.io/badge/Live-from.it.kr-4285F4?style=flat-square)](https://from.it.kr)

독서 기록을 남기면 AI가 독후감 작성을 돕고, 읽은 양에 따라 랭킹을 제공하는 서비스입니다. 기획부터 배포·운영까지 진행했습니다.

- Claude API를 활용한 AI 독후감 생성
- Redis Sorted Set 기반 실시간 독서 랭킹
- 알라딘 Open API 연동 도서 검색
- AWS S3 이미지 업로드 및 저장
- 정형 데이터(MariaDB)와 비정형 데이터(MongoDB) 분리 저장

`Spring Boot` `JPA` `MyBatis` `MariaDB` `MongoDB` `Redis` `AWS S3`

<br>

#### Märchand (메르핸드) — 동화 기반 수어 학습 서비스

> 🏆 ICT 한이음 드림업 프로젝트 **장려상**

청각장애 아동이 동화를 읽으며 수어를 배우고, 웹캠으로 직접 따라 하며 실습할 수 있는 교육 플랫폼입니다.

- 웹캠 모션 인식 + TensorFlow 모델 기반 수어 인식 (Flask 추론 서버 분리)
- ChatGPT API로 동화 생성, Leonardo.AI로 삽화 자동 생성
- 수어 퀴즈 및 학습 달성도 관리
- NCP Object Storage 기반 미디어 저장

`Spring Boot` `MariaDB` `Flask` `TensorFlow` `ChatGPT API` `NCP`

<br>

#### Agreeya — AI 국제 근로계약 위험 분석 플랫폼

> K-PaaS 공모전 출품작

근로계약서를 업로드하면 OCR로 텍스트를 추출하고, AI가 법적 위험 조항을 분석해 개선된 계약서 초안을 제안합니다.

- Google Vision OCR 기반 계약서 텍스트 추출
- GPT 기반 위험 조항 분석 및 계약서 초안 생성
- LangChain 기반 유사 계약 사례 검색, 법률 Q&A 챗봇
- AI 모의 협상 시뮬레이션, 다국어 분석·번역
- Kubernetes(K-PaaS) 환경 배포

`Spring Boot` `MySQL` `OpenAI API` `Google Vision OCR` `LangChain` `Kubernetes` `K-PaaS`

---

### Currently

- Spring Boot 아키텍처 및 데이터베이스 모델링 심화
- Kubernetes 운영 · 클라우드 인프라 설계 학습
- SQLD · 정보처리산업기사 준비 중

---

### GitHub Stats

<p>
  <img src="https://streak-stats.demolab.com/?user=choijunyoung0511&theme=github-dark-blue&hide_border=true" height="160"/>
</p>
