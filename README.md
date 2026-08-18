# 👋 김영빈 (binkim00)

> 🚀 Backend Developer | Data & Flow | 상태와 정합성을 다루는 개발자
>
> 자연어 검색부터 상태 전이, 실시간 대기열과 외부 이벤트까지 직접 구현해 왔습니다.
>
> 기능을 빠르게 붙이는 것보다 **업무 흐름·데이터 상태·실패 경로를 먼저 정리하고 검증하는 방식**을 중요하게 생각합니다.
>
> [GitHub](https://github.com/binkim00) · [Email](mailto:k0b0301@naver.com)

---

## 🎯 About Me

```text
🎓 SSAFY 15기 | 💻 Backend Developer | 🔄 State · Data · Realtime
```

Java·Spring Boot를 중심으로 백엔드 개발을 공부하고 있으며, Django 기반 검색·추천 서비스와 Spring 기반 업무 시스템을 함께 경험했습니다.  
프로젝트에서는 **상태 전이, 트랜잭션 정합성, Redis 실시간 상태, 외부 이벤트 처리**처럼 서비스 흐름의 중심이 되는 로직을 주로 맡았습니다.  
최근에는 AI를 코드 생성 도구로만 쓰지 않고, 작업 의존성을 나누고 병렬 개발 결과를 통합·검증하는 방식에도 활용하고 있습니다.

---

## 🛠️ Tech Stack

<div align="center">
  <h3>🏆 Backend & Tech Stack</h3>
  <table border="0">
    <tr>
      <td align="center" width="44%">
        <p>🧭 Backend Focus</p>
        <p><b>State Transition</b></p>
        <p>상태 · 권한 · 변경 이력</p>
        <br />
        <p><b>Data Consistency</b></p>
        <p>Transaction · Inventory · History</p>
        <br />
        <p><b>Realtime Flow</b></p>
        <p>Redis · Lua Script · Webhook</p>
        <br />
        <p><b>AI Search</b></p>
        <p>Intent · Candidate · Validation</p>
      </td>
      <td align="center" width="56%">
        <p>☕ Languages</p>
        <p>
          <img src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
          <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
          <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
          <img src="https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
        </p>
        <p>🏗️ Backend</p>
        <p>
          <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
          <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
          <img src="https://img.shields.io/badge/JPA-59666C?style=for-the-badge">
          <img src="https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white">
          <img src="https://img.shields.io/badge/DRF-A30000?style=for-the-badge&logo=django&logoColor=white">
        </p>
        <p>🗄️ Data & Realtime</p>
        <p>
          <img src="https://img.shields.io/badge/MariaDB-003545?style=for-the-badge&logo=mariadb&logoColor=white">
          <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
          <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
          <img src="https://img.shields.io/badge/LiveKit-111111?style=for-the-badge">
        </p>
        <p>🎨 Frontend</p>
        <p>
          <img src="https://img.shields.io/badge/React-61DAFB?style=for-the-badge&logo=react&logoColor=black">
        </p>
        <p>⚙️ Infra & Tools</p>
        <p>
          <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
          <img src="https://img.shields.io/badge/Nginx-009639?style=for-the-badge&logo=nginx&logoColor=white">
          <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">
          <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
          <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white">
          <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white">
        </p>
      </td>
    </tr>
  </table>
</div>

---

## 🚀 Featured Projects

### 🗺️ **여기일지도** — 자연어 기반 생활 장소 추천

[![Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/binkim00/life-infra-map)

| 항목 | 내용 |
|------|------|
| 🎯 **문제** | 자유로운 자연어 요청을 실제 검색 가능한 조건과 장소 추천으로 연결 |
| 💻 **담당** | 자연어 검색 안정화, 추천 파이프라인, 후보 결합·검증, 평가 |
| ⚙️ **핵심 구현** | 위치·대상·상황·포함·제외 조건 구조화, DB·Kakao 후보 결합, 후속 요청 조건 병합 |
| ✅ **검증** | 위치 오해·제외 조건·결과 부족 등을 포함한 저장 평가셋 회귀 검증 |
| 🛠️ **스택** | Spring Boot, Django REST Framework, React, Kakao Local API, AI Search |
| 🧩 **구조** | Spring Boot와 Django의 역할을 분리한 Hybrid Backend |

---

### 📦 **RENTEX** — 상태 전이 기반 장비 대여 관리

[![Repository](https://img.shields.io/badge/GitHub-Repository-black?logo=github)](https://github.com/binkim00/rentex)

| 항목 | 내용 |
|------|------|
| 🎯 **문제** | 대여 요청부터 반납까지 역할별 업무 흐름과 연관 데이터 정합성 관리 |
| 💻 **담당** | 대여 상태 전이, 사용자·파트너·관리자 권한 검증, 재고·이력 관리 |
| 🔄 **상태 흐름** | `REQUESTED → APPROVED → SHIPPED → RECEIVED → RETURN_REQUESTED → RETURNED` |
| ⚙️ **핵심 구현** | 상태 검증·재고 변경·RentalHistory 저장을 트랜잭션 단위로 처리 |
| 💡 **설계 이유** | 현재 상태와 별도로 이전·이후 상태, 수행자, 사유를 기록해 운영 추적 근거 확보 |
| 🛠️ **스택** | Java 17, Spring Boot, JPA, MariaDB, React |

---

### 🎥 **Melly** — 실시간 영상 팬미팅 운영 플랫폼

![Repository](https://img.shields.io/badge/GitHub-Private_Repository-555555?logo=github)

| 항목 | 내용 |
|------|------|
| 🎯 **문제** | 응모·대기·호출·통화·종료를 하나의 실시간 운영 흐름으로 연결 |
| 💻 **담당** | 백엔드 API와 DB 상태 모델 중심, 인증 보안·Redis 대기열·LiveKit 상태 연동 |
| 🔐 **인증** | Access/Refresh 분리, Redis 단일 세션, Token Rotation, 로그아웃 블랙리스트 |
| ⚡ **실시간** | DB는 복구 기준, Redis는 실시간 순번·접속 상태, Lua Script는 원자적 선점·재정렬 |
| 🔗 **외부 이벤트** | LiveKit Webhook 이벤트 중복 방지와 CallSession 상태 동기화 |
| 🛠️ **스택** | Java 17, Spring Boot, Spring Security, JPA, MariaDB, Redis, Lua Script, LiveKit |

---

## 📚 Other Projects

| 프로젝트 | 설명 | 기술 스택 |
|---------|------|---------|
| **[Fitple](https://github.com/binkim00/250702_Fitple)** | 청년에게 필요한 채용·주거·정책 정보를 지역 기준으로 연결 | Spring Boot, JPA, MariaDB, Public Data API |
| **[IEUM](https://github.com/binkim00/IEUM)** | 공식 데이터 기반 국가유산 AI 해설·추천 서비스 기획 및 구현 | RAG, Metadata Filtering, TTS, Recommendation Flow |

---

## 💡 핵심 경험 & 강점

<div align="center">

| 🔄 | ⚡ | 🔗 | 🤖 |
|---|---|---|---|
| **상태 설계** | **실시간 처리** | **외부 연동** | **AI 활용** |
| 상태 전이 | Redis 대기열 | Kakao Local API | 자연어 의도 구조화 |
| 권한 검증 | Lua 원자 처리 | LiveKit Webhook | 검색 후보 검증 |
| 변경 이력 | 실패 시 복구 | 공공데이터 API | 작업 분해·통합 검증 |

</div>

### ✅ 주요 경험

- 🔄 **상태 전이 설계**: 업무 흐름을 상태·권한·이력으로 나누고 잘못된 요청 순서를 제한
- 🧾 **데이터 정합성**: 상태 변경과 재고·이력을 하나의 트랜잭션 단위로 처리
- ⚡ **실시간 대기열**: DB와 Redis의 역할을 나누고 Lua Script로 선점·재정렬을 원자적으로 처리
- 🔐 **인증 보안**: JWT와 Redis를 결합해 단일 로그인, Token Rotation, 블랙리스트 구현
- 🔗 **외부 이벤트 처리**: Webhook 중복과 실패를 전제로 내부 상태와 동기화
- 🧠 **자연어 검색**: 자연어를 구조화된 검색 조건으로 바꾸고 내부·외부 후보를 결합해 검증
- 🚀 **배포 운영**: Docker·Nginx·Jenkins·AWS 환경에서 빌드·컨테이너·로그까지 실제 반영 확인
- 🤖 **AI 기반 개발 운영**: 작업 범위·금지 파일·완료 조건·필수 테스트를 명시한 뒤 병렬 구현 결과를 통합 검증

---

## 🎓 Learning & Development

```text
📚 Backend                🗄️ Data / Realtime         ⚙️ Infra / Operation       🤖 AI
├─ Java / Spring Boot     ├─ MariaDB / MySQL         ├─ Docker                  ├─ Intent Planning
├─ Spring Security        ├─ JPA / Transaction       ├─ Nginx                   ├─ Candidate Validation
├─ Django / DRF           ├─ Redis                   ├─ Jenkins                 ├─ Search Evaluation
└─ REST API               └─ Lua / State Flow        └─ AWS                     └─ Work Decomposition
```

---

## 🧩 Development Principles

```text
요구사항을 기능 목록으로만 보지 않고, 상태와 데이터 흐름으로 연결하기
정상 동작뿐 아니라 중복 요청·실패·복구 경로까지 함께 확인하기
AI가 만든 코드도 직접 설명하고 검증할 수 있는 범위에서만 사용하기
구현 완료보다 통합·테스트·배포 반영 확인까지를 완료 기준으로 삼기
```

---

<div align="center">

### Backend · Data · Flow

**흐름을 이해하고, 상태를 정리하고, 실패까지 확인하는 개발자**

</div>
