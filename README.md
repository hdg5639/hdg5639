<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:9BE15D,100:00E3AE&height=140&section=header" width="100%"/>
</div>

<div align="center">

# 한동균

### Backend · Platform · Infrastructure

**서비스를 만들고, 직접 운영하고, 끝까지 개선하는 개발자**

Java/Spring 기반 백엔드를 중심으로  
셀프호스팅 인프라, 자동 배포, 온라인 저지, AI 연동 서비스까지 직접 설계하고 운영합니다.

[![Email](https://img.shields.io/badge/Email-hdg5639@naver.com-007396?style=flat-square&logo=gmail&logoColor=white)](mailto:hdg5639@naver.com)
[![Blog](https://img.shields.io/badge/Blog-cod--ing.tistory.com-20C997?style=flat-square&logo=tistory&logoColor=white)](https://cod-ing.tistory.com/)

</div>

---

## 👋 About Me

- **계명대학교 컴퓨터공학과** 졸업
- **SSAFY** 교육 과정 진행 중
- 주력 분야는 **Java / Spring Boot 기반 Backend**
- 관심 분야는 **Platform Engineering, Cloud Infrastructure, Distributed Systems, Developer Tools**
- 기능 구현에서 끝내지 않고 **배포·운영·성능·실패 복구까지 직접 다루는 개발**을 선호합니다.

---

## 🌱 Main Project — GamjaBox

<p align="center">
  <a href="https://github.com/hdg5639/GJ-Cloud">
    <b>GamjaBox — Self-hosted IaaS / semi-PaaS Platform</b>
  </a>
</p>

> 개인 Proxmox 서버 위에 직접 구축한 셀프호스팅 클라우드 플랫폼  
> VM 생성부터 SSH, 도메인, 배포, 접근 제어까지 자동화하는 개인 인프라 프로젝트

**GamjaBox는 제가 가장 오래 만들고, 가장 애착을 가지고 운영하는 프로젝트입니다.**

단순한 VM 생성기를 넘어서,  
**“개발자가 인프라를 직접 만지지 않아도 서비스를 배포할 수 있는 환경”**을 만드는 것을 목표로 하고 있습니다.

### What I built

- Proxmox 기반 VM 생성 / 삭제 / 상태 관리
- Cloud-init 기반 초기 설정 자동화
- Cloudflare Tunnel + Zero Trust 기반 접근 제어
- SSH 서브도메인 자동 발급
- PUBLIC / PRIVATE 포트 관리
- 조직 / 권한 / 사용자 관리
- 웹 터미널 및 파일 브라우저
- Git 저장소 기반 배포 흐름
- Docker Compose / Caddy 자동 생성 및 검증
- SSE 기반 VM 상태 실시간 전달
- 서비스 간 audience-scoped 토큰 인증
- GitHub App 기반 CI/CD
- 운영 서비스 성능 개선 및 대규모 데이터 기준 DB 쿼리 최적화

### Architecture

**Spring Boot · PostgreSQL · Redis · Proxmox · Docker · Cloudflare Zero Trust · Next.js**

서비스를 단순 모놀리식으로 두지 않고  
**Auth / User / VM / Ops** 영역으로 나누어 신뢰 경계와 변경 주기에 맞게 설계했습니다.

🔗 **Repository**  
https://github.com/hdg5639/GJ-Cloud

🔗 **Live Service**  
https://gamjabox.cloud

---

## 🥔 Recent Major Project — GamjaOJ

<p align="center">
  <a href="https://github.com/hdg5639/GamjaOJ">
    <b>GamjaOJ — Coding Training & Online Judge Platform</b>
  </a>
</p>

> 문제를 풀고 끝나는 것이 아니라  
> **채점 → 분석 → 약점 파악 → 다음 훈련**까지 이어지는 알고리즘 학습 플랫폼

최근 가장 크게 진행하고 있는 개인 프로젝트입니다.

### Core Features

- Java 8 / C++17 / Python 3.12 온라인 채점
- Docker 기반 사용자 코드 실행 격리
- 실행 시간 / 메모리 사용량 수집
- 선택 진단 및 맞춤형 훈련 계획
- AI 풀이 분석 및 힌트
- 문제 자동 생성 / 검증 파이프라인
- GitHub / Notion 풀이 자동 기록
- CodeMirror 기반 브라우저 코드 에디터
- 사용자별 학습 기록 및 성장 분석

### Engineering Focus

- 장시간 작업을 HTTP 요청에서 분리한 Worker 구조
- DB 기반 작업 큐 및 재시도 처리
- 제출 코드 sandboxing
- AI 생성 문제의 정답 / 오답 코드 기반 자동 검증
- 운영 환경 PostgreSQL 마이그레이션 검증
- 브라우저 상태 / 비동기 요청 경합 문제 해결
- 실제 Runner 기반 문제별 시간 제한 검토

**Java 21 · Spring Boot 3.5 · PostgreSQL · Next.js 16 · React 19 · Python · Docker**

🔗 **Repository**  
https://github.com/hdg5639/GamjaOJ

🔗 **Live Service**  
https://gamjaoj.gamjabox.cloud

---

## 🧑‍🤝‍🧑 Team & Organization Projects

### 🎪 Eventory
> AI 기반 지역 맞춤형 행사 기획 서비스

- 2025 멋쟁이사자처럼 대학 13기 팀 프로젝트
- 지역 / 사용자 조건을 기반으로 행사 기획을 지원하는 서비스

🔗 https://github.com/Likelion-13th-EGSBI

---

### ♻️ 새로고침 (Refresh)

> 환경 보호와 자원 재활용을 중심으로 설계한 종합 플랫폼

- 환경 보호 의식 고취와 실천을 위한 통합 서비스
- 팀 기반 웹 서비스 설계 및 개발 경험

🔗 https://github.com/TEAM-CP6Q/Reload_F5

---

### 🥗 우리동네영양사

> 바쁜 현대인을 위한 건강한 도시락 정기 구독 서비스

- 멋쟁이사자처럼 12기 해커톤 프로젝트

🔗 https://github.com/dongsubnambuk/LikeLion-12th-Hackathon

---

### 🦁 계명대학교 멋쟁이사자처럼 13기 출결 관리 플랫폼

> 운영진과 교육생을 위한 출석 · 일정 · 교육자료 관리 서비스

- **Backend 담당**
- Spring 기반 인증 / 사용자 / 팀 / 출결 / 일정 관리
- 관리자 대시보드 및 통계 기능 지원
- 실제 동아리 운영에 사용

🔗 https://github.com/dongsubnambuk/likelion_att

---

## 🛠 Tech Stack

### Backend
<p>
  <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white"/>
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white"/>
  <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge"/>
</p>

### Database & Messaging
<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white"/>
</p>

### Infrastructure / DevOps
<p>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>
  <img src="https://img.shields.io/badge/Proxmox-E57000?style=for-the-badge&logo=proxmox&logoColor=white"/>
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=for-the-badge&logo=cloudflare&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
</p>

### Frontend
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black"/>
  <img src="https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white"/>
</p>

---

## 🎓 Experience

### SSAFY
**2026.06 ~ Present**

- Java 기반 알고리즘 및 소프트웨어 역량 강화
- BFS / DFS / Backtracking / DP / Graph / MST / Shortest Path 등 집중 학습
- 알고리즘 문제 풀이 및 스터디 진행
- 실전형 SW 역량 평가 대비

### 멋쟁이사자처럼 대학 13기
**운영진 · 2025.01 ~ 2025.12**

- 교육 운영 및 팀 프로젝트 참여
- 출결 관리 플랫폼 백엔드 개발

### 멋쟁이사자처럼 대학 12기
**아기사자 · 2024.01 ~ 2024.12**

---

## 🏆 Awards

- **2025 지역혁신 인재양성 연합 페스티벌** — AI · DX 산출물 부문 우수상
- **2025 코드 인사이트 챌린지** — PT 부문 우수상
- **2025 캡스톤디자인 작품발표회** — 우수상
- **AIDEA(AI+IDEA) 공모전** — 사랑상
- **한국정보기술학회 2025 하계종합학술대회 대학생논문경진대회** — 은상
- **2024 4차 산업혁명 인재양성 공유 협업 페스티벌** — ICT 솔루션(코딩) 부문 우수상
- **한국정보기술학회 2024 추계종합학술대회** — 우수논문상

---

## 📝 Publications

- **N-그램 및 임베딩 기반 표절 탐지 성능 비교**  
  2024 한국정보기술학회  
  [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12025335)

- **대학 챗봇 활용의 인식 및 효율성 평가**  
  2024 한국정보기술학회  
  [DBpia](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE12025346)

---

## 📜 Certification

- SQL Developer (**SQLD**)

---

<div align="center">

### I like building things that actually run.

아이디어를 코드로 만들고,  
코드를 서비스로 올리고,  
서비스가 실제로 돌아가게 만드는 과정까지 직접 다룹니다.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00E3AE,100:9BE15D&height=120&section=footer" width="100%"/>

</div>
