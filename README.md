<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=2F5D50&height=190&section=header&text=Kim%20Yeongbin&fontSize=44&fontColor=F7F9F8&animation=fadeIn&fontAlignY=36&desc=Backend%20Developer&descAlignY=58&descSize=18" width="100%" />

### 상태와 데이터 흐름으로 복잡한 요구사항을 구조화하는 백엔드 개발자

자연어 검색부터 상태 전이, 실시간 대기열과 외부 이벤트까지  
**문제를 흐름으로 나누고, 실패 경로까지 확인하며 구현합니다.**

[![GitHub](https://img.shields.io/badge/GitHub-binkim00-1F2937?style=flat-square&logo=github&logoColor=white)](https://github.com/binkim00)
[![Email](https://img.shields.io/badge/Email-k0b0301%40naver.com-2F5D50?style=flat-square&logo=naver&logoColor=white)](mailto:k0b0301@naver.com)

</div>

<br />

## Core Focus

<table>
  <tr>
    <td align="center"><b>상태 · 정합성</b><br/>역할별 상태 전이 · 트랜잭션 · 변경 이력</td>
    <td align="center"><b>실시간 · 동시성</b><br/>Redis · Lua Script · Webhook · 복구 흐름</td>
    <td align="center"><b>AI 검색 · 검증</b><br/>자연어 의도 구조화 · 후보 결합 · 회귀 검증</td>
  </tr>
</table>

- SSAFY 15기에서 백엔드 개발을 중심으로 학습하고 있습니다.
- 기능 목록보다 **업무 흐름, 상태 변화, 데이터 구조**를 먼저 정리하려고 합니다.
- 로컬 구현에서 끝내지 않고 **통합 테스트와 배포 반영 확인**까지를 완료 기준으로 두고 있습니다.

<br />

## Featured Projects

### 1. [여기일지도](https://github.com/binkim00/life-infra-map) — 자연어 기반 생활 장소 추천

> 자연어 요청을 검색 가능한 조건으로 구조화하고, DB와 Kakao Local API 후보를 결합해 근거와 함께 추천하는 서비스

- 자연어 입력을 **위치 · 대상 · 상황 · 포함 조건 · 제외 조건**으로 분리해 검색 계획으로 변환
- 자체 DB와 Kakao Local API 후보를 결합하고 조건·거리·데이터 품질을 기준으로 검증·정렬
- 후속 요청은 이전 검색 조건에 변경 사항만 병합하도록 구성
- 프로젝트 평가셋을 이용해 위치 오해·제외 조건·결과 부족 케이스 회귀 검증
- **Tech:** Spring Boot · Django REST Framework · React · Kakao Local API · AI Search
- **Architecture:** Spring Boot와 Django의 역할을 분리한 Hybrid Backend

---

### 2. [RENTEX](https://github.com/binkim00/rentex) — 상태 전이 기반 장비 대여 관리

> 렌탈 요청부터 승인·배송·수령·반납까지의 업무 흐름을 상태와 이력으로 관리하는 서비스

- `REQUESTED → APPROVED → SHIPPED → RECEIVED → RETURN_REQUESTED → RETURNED` 상태 흐름 구현
- 사용자·파트너·관리자의 수행 가능 작업과 권한을 서비스 계층에서 검증
- 상태 변경·재고 반영·이력 저장을 하나의 트랜잭션 단위로 처리
- `RentalHistory`에 이전 상태·이후 상태·수행자·사유를 기록해 운영 추적 근거 확보
- **Tech:** Java 17 · Spring Boot · JPA · MariaDB · React

---

### 3. Melly — 실시간 영상 팬미팅 운영 플랫폼

> 팬미팅의 응모·대기·호출·통화·종료를 하나의 실시간 운영 흐름으로 연결한 서비스

- 백엔드 API와 DB 상태 모델을 중심으로 담당
- JWT·Redis 기반 단일 로그인, Refresh Token Rotation, 로그아웃 블랙리스트 구현
- DB는 상태 이력과 복구 기준, Redis는 실시간 순번·접속 상태 조회로 역할 분리
- Lua Script로 대기열 선점·재정렬·해제를 원자적으로 처리
- LiveKit Webhook 중복 이벤트 방지와 통화 세션 상태 연동
- **Tech:** Java 17 · Spring Boot · Spring Security · JPA · MariaDB · Redis · Lua Script · LiveKit
- **Repository:** Private

<br />

## Tech Stack

### Backend · Data

<p>
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Django%20REST%20Framework-092E20?style=flat-square&logo=django&logoColor=white" />
  <img src="https://img.shields.io/badge/JPA-59666C?style=flat-square" />
  <img src="https://img.shields.io/badge/MariaDB-003545?style=flat-square&logo=mariadb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

### Realtime · Infra

<p>
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/LiveKit-111111?style=flat-square" />
  <img src="https://img.shields.io/badge/WebRTC-333333?style=flat-square&logo=webrtc&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" />
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
</p>

### Frontend · Tools

<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=222222" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=222222" />
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
</p>

<br />

## Other Projects

### [Fitple](https://github.com/binkim00/250702_Fitple)
청년에게 필요한 채용·주거·정책 정보를 지역 기준으로 연결한 서비스  
`Spring Boot · JPA · MariaDB · Public Data API`

### [IEUM](https://github.com/binkim00/IEUM)
공식 데이터 기반 국가유산 AI 해설·추천 서비스 기획 및 구현 경험  
`RAG · Metadata Filtering · TTS · Recommendation Flow`

<br />

## Development Principles

```text
요구사항을 기능 목록으로만 보지 않고, 상태와 데이터 흐름으로 연결하기
정상 동작뿐 아니라 중복 요청·실패·복구 경로까지 함께 확인하기
AI가 만든 코드도 직접 설명하고 검증할 수 있는 범위에서만 사용하기
구현 완료보다 통합·테스트·배포 반영 확인까지를 완료 기준으로 삼기
```

<br />

<div align="center">

### Backend · Data · Flow

<img src="https://capsule-render.vercel.app/api?type=waving&color=2F5D50&height=100&section=footer" width="100%" />

</div>
