# SignBell : AI 기반 실시간 수어 학습 플랫폼

<p align="center">
  <img src="img/logo.png" alt="SignBell 로고" width="300" />
</p>

<p align="center"><b>SignBell - 손끝으로 울리는 정답의 순간</b></p>
<p align="center">AI 기술로 배우고, 게임으로 함께 즐기는 실시간 양방향 수어 학습 플랫폼</p>

<p align="center">
  <b>TEAM</b> SynergySign
</p>

---

## 목차

- [프로젝트 정보](#프로젝트-정보)
- [Getting Started](#getting-started)
- [프로젝트 비전](#프로젝트-비전)
    - [SignBell이 해결하는 문제](#signbell이-해결하는-문제)
    - [SignBell의 철학](#signbell의-철학)
    - [플랫폼 차별성](#플랫폼-차별성)
- [주요 기능](#주요-기능)
- [사용자 페르소나](#사용자-페르소나)
- [팀 구성](#팀-구성)
- [개발 기간](#개발-기간)
- [기술 스택](#기술-스택)
- [시스템 아키텍처](#시스템-아키텍처)
- [대표 문서](#대표-문서)
    - [전체 문서 폴더](#전체-문서-폴더)
    - [협업 규칙 & 기여 문서](#협업-규칙--기여-문서)
- [향후 업데이트 계획](#향후-업데이트-계획)
- [문의](#문의)

---

##  프로젝트 정보

| 항목 | 내용                                                                                                         |
| --- |------------------------------------------------------------------------------------------------------------|
| **팀명** | **SynergySign** — *기술과 수어가 만나 시너지를 창출하고, 팀원 간의 협력을 통해 수어 소통의 새로운 가능성을 열어가는 팀*                              |
| **프로젝트명** | **SignBell** — *손끝으로 울리는 정답의 순간*                                                     |
| **플랫폼명** | **SignBell** — *Sign(수어) + Bell(골든벨). 누구나 자연스럽고 안전하게 수어를 배우는 AI 기반 학습 플랫폼*                                 |
| **버전** | v1.0.0                                                                                                     |
| **Base URL** | `http://localhost:8443/` (Backend), `http://localhost:5173` (Frontend), `https://localhost:8000` (FastAPI) |

---

##  Getting Started

- [백엔드 및 프론트엔드 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-App/blob/dev/README.md)
- [FastAPI 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-FASTAPI/blob/dev/README.md)
- [머신 러닝 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-ML)
- [API 스펙 명세서](https://github.com/SynergySign/SignBell-Docs/tree/dev/03_Specifications)
- [시스템 아키텍처](https://github.com/SynergySign/SignBell-Docs/blob/dev/02_Architecture/SignBell%20%EC%8B%9C%EC%8A%A4%ED%85%9C%20%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.md)

---

##  프로젝트 비전

SignBell은 단순한 수어 교육 앱이 아니라, **대화 불안을 해결하고 청인과 농인 사이의 소통 장벽을 허무는 AI 기반 학습 플랫폼**입니다.

### SignBell이 해결하는 문제

- **대화 시작의 어려움**: 수어 통역사가 없는 상황에서 농인과의 소통에 어려움을 겪으며 깊은 대화를 나누지 못하는 안타까움
- **학습 피드백 부재**: 온라인 강의를 보며 수어를 따라 해보지만, 정확한 피드백이 없어 학습에 한계를 느끼는 답답함
- **학습 동기 부족**: 단순 암기 위주의 학습 방식에 쉽게 지루함을 느끼고 중도에 포기하게 되는 경험

### SignBell의 철학

* **AI 기반 개인화 학습**:
  사용자의 수어 동작을 실시간으로 분석하여 정확도를 피드백해주는 '거울 모드'를 통해 혼자서도 효과적으로 학습할 수 있습니다.

* **게이미피케이션을 통한 즐거움**:
  WebRTC 기반의 실시간 영상통화 방에서 다른 학습자들과 함께 퀴즈를 풀며 경쟁하고 소통하는 재미를 제공합니다.

* **데이터 기반 성장**:
  사용자의 학습 데이터(동의 시)를 통해 AI 모델이 스스로 성능을 개선하는 선순환 구조를 만듭니다.

* **포용적 사회 기여**:
  누구나 차별 없이 소통할 수 있는 사회를 만드는 데 기여하는 소셜 임팩트를 창출합니다.

### 플랫폼 차별성

SignBell의 목표는 "수어가 소수만의 언어가 아닌, 누구나 쉽게 배울 수 있는 또 하나의 언어"로 만드는 것입니다.

| 구분 | 기존 수어 학습 앱 | **SignBell** |
| --- | --- | --- |
| **핵심 경험** | 일방향 영상 시청 | **AI 피드백 + 실시간 퀴즈 대결** |
| **AI 역할**| 없음 또는 단순 번역 | **실시간 동작 분석 + 정확도 피드백 + 개인화 학습** |
| **학습 방식** | 혼자 반복 학습 | **개인 학습 + 멀티플레이 퀴즈** |
| **피드백** | 없음 | **실시간 AI 피드백 및 유사도 점수** |
| **사용자 경험** | 지루한 암기 | **게임처럼 즐기는 학습** |

> SignBell은 수어 학습을 넘어, **기술을 통해 마음과 마음이 통하는 세상**을 만드는 데 집중합니다.

---

##  주요 기능

### 개인 수어 학습 (거울 모드)
- **AI 기반 실시간 피드백**: MediaPipe를 활용한 손/얼굴/포즈 랜드마크 추출 및 CNN+BiLSTM+Attention 모델을 통한 수어 동작 인식
- **정확도 분석**: 사용자의 수어 동작과 정답 동작의 유사도를 실시간으로 계산하여 점수 제공
- **학습 콘텐츠 관리**: 수어 단어 목록 조회, 카테고리별 분류, 키워드 검색 기능
- **학습 데이터 제공**: 사용자 동의 기반 학습용 수어 영상 데이터 수집 및 AI 모델 개선에 기여

### 실시간 수어 퀴즈 게임
- **WebRTC 화상 통신**: Janus Gateway를 활용한 실시간 4인 멀티플레이 화상 퀴즈
- **게임 진행 시스템**: 턴 기반 도전자 시스템, 준비/사인 타이머, 실시간 점수 집계
- **게임방 관리**: 방 생성/입장/퇴장, 무한 스크롤 방 목록, 방장 권한 관리
- **WebSocket 실시간 동기화**: STOMP 프로토콜 기반 게임 상태 실시간 브로드캐스트

### 인증 및 사용자 관리
- **카카오 소셜 로그인**: OAuth2 기반 간편 로그인 및 JWT 토큰 발급
- **마이페이지**: 프로필 이미지 업로드(S3 연동), 닉네임 변경, 학습 기록 조회
- **약관 동의**: 필수/선택 약관 동의 관리 및 개인정보 보호

---

## 사용자 페르소나

### 주요 타겟

| 페르소나 | 연령/직업 | 주요 니즈 | 사용 시나리오 |
| --- | --- | --- | --- |
| **문화 공감형 학습자** | 26세, 대학생 | 쉽고 재미있게 수어를 배우고 싶음 | AI 피드백으로 정확도 확인, 거울 모드로 시각적 비교 |
| **소통 실천형 학습자** | 32세, 직장인 | 농인 동료와 원활한 소통 | 실용 수어 습득, 실시간 퀴즈로 반복 학습 |
| **전문 성장형 학습자** | 28세, 사회복지사 | 업무에서 정확한 수어 사용 | 실시간 피드백 기반 학습, 진도 관리 |
| **경쟁·협력형 학습자** | 21세, 대학생 | 친구들과 즐기며 수어 배우기 | WebRTC 실시간 퀴즈 대결, 랭킹 시스템 |

---

## 팀 구성

| 역할 | 이름 | 주요 담당 기능                                                        | 회고록 |
| --- | --- |-----------------------------------------------------------------| --- |
| 팀장 | [신동준](https://github.com/sdj3959) | Frontend Lead, UI/UX 디자인, 인프라 구축 (AWS EC2/S3/RDS, Kubernetes)   | [신동준 회고록](https://github.com/sdj3959/my-retrospectives/tree/0093a56859893ab975c26f259728a52fc0b5aca0/projects/202509SignBell) |
| 팀원 | [고동현](https://github.com/rhehdgus8831) | Backend Lead (게임 로직), Frontend Janus WebRTC 연동, 시스템 아키텍처 설계     | [고동현 회고록](https://github.com/rhehdgus8831/Project-retrospective/tree/main/signbell) |
| 팀원 | [백승현](https://github.com/sirosho) | AI/ML Lead, FastAPI 서버 구축, 개인 학습 페이지 개발                         | [백승현 회고록](https://github.com/Sirosho/project-memoir) |
| 팀원 | [송민재](https://github.com/songkey06) | Backend (인증/인가), 카카오 SSO, 마이페이지, DevOps 지원                      | [송민재 회고록](https://github.com/songkey06/memories/tree/main/SignBell) |
| 팀원 | [강관주](https://github.com/Kanggwanju) | Full-Stack (대기방/게임방),Frontend Janus WebRTC 연동, 무한 스크롤, 전역 예외 처리 | [강관주 회고록](https://github.com/Kanggwanju/SynergySign-project-notes/tree/main/retrospective) |

---

##  개발 기간

**2025.10.07 ~ 2025.10.28**

| **Phase** | **기간** | **주요 내용** |
|:--------------------------------| :--- | :--- |
| **1. 기획 및 설계**                  | 9월 29일 ~ 10월 3일 | 프로젝트 주제 선정, MVP 정의, 핵심 문서 작성 (요구사항, 유저플로우, DB/아키텍처 설계), ML 리서치 |
| **2. 초기 개발 (AI/ML/Frontend)**   | 10월 4일 ~ 10월 12일 | AI 모델 개발 착수, 학습 데이터 수집, 프론트엔드 와이어프레임 및 기본 UI 작업 |
| **3. 핵심 기능 개발 (Backend/AI/ML)** | 10월 13일 ~ 10월 19일 | 백엔드 API (WebSocket, REST, JWT 인증) 개발, 국립국어원 API 연동, ML 모델 개발 지속 |
| **4. 기능 고도화 (Frontend)**        | 10월 20일 ~ 10월 28일 | Janus WebRTC 연동, 백엔드 API 연동(fetch), 전반적인 UI/UX 보강 |
| **5. 통합, 배포 및 테스트**             | 10월 29일 ~ 10월 30일 | 전 파트(FE/BE/AI) 기능 통합 테스트, 발견 버그 수정, AWS 배포, 문서 최신화 |
| **6. 안정화 및 발표 준비**              | 10월 31일 ~ 11월 2일 | 배포 환경에서의 최종 버그 픽스 및 서비스 안정화, PPT 등 발표 자료 준비 |
| **7. 최종 발표**                    | 11월 3일 | 프로젝트 결과물 최종 발표 |


---

##  기술 스택

| 구분 | 기술 |
| --- | --- |
| **언어** | ![Java](https://img.shields.io/badge/Java-17-007396?logo=openjdk&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-F7DF1E?logo=javascript&logoColor=black) ![Python](https://img.shields.io/badge/Python-3.10+-3776AB?logo=python&logoColor=white) |
| **프레임워크** | ![Spring Boot](https://img.shields.io/badge/Spring%20Boot-3.5.6-6DB33F?logo=springboot&logoColor=white) ![Spring Validation](https://img.shields.io/badge/Spring%20Validation-6DB33F?logo=spring&logoColor=white) ![React](https://img.shields.io/badge/React-19.1.1-61DAFB?logo=react&logoColor=black) ![FastAPI](https://img.shields.io/badge/FastAPI-0.110.0-009688?logo=fastapi&logoColor=white) ![Uvicorn](https://img.shields.io/badge/Uvicorn-0.29.0-009688?logo=python&logoColor=white) |
| **프론트엔드** | ![Sass](https://img.shields.io/badge/Sass-1.93.2-CC6699?logo=sass&logoColor=white) ![Vite](https://img.shields.io/badge/Vite-7.1.7-646CFF?logo=vite&logoColor=white) ![Framer Motion](https://img.shields.io/badge/Framer%20Motion-12.23.24-0055FF?logo=framer&logoColor=white) ![Font Awesome](https://img.shields.io/badge/Font%20Awesome-7.1.0-528DD7?logo=fontawesome&logoColor=white) |
| **상태 관리** | ![Zustand](https://img.shields.io/badge/Zustand-5.0.8-000000?logo=zustand&logoColor=white) |
| **라우팅** | ![React Router](https://img.shields.io/badge/React%20Router-7.9.4-CA4245?logo=reactrouter&logoColor=white) |
| **HTTP 클라이언트** | ![Axios](https://img.shields.io/badge/Axios-1.12.2-5A29E4?logo=axios&logoColor=white) |
| **보안/인증** | ![Spring Security](https://img.shields.io/badge/Spring%20Security-6.4.2-6DB33F?logo=springsecurity&logoColor=white) ![Spring Security Messaging](https://img.shields.io/badge/Security%20Messaging-6DB33F?logo=springsecurity&logoColor=white) ![JWT](https://img.shields.io/badge/JWT-0.12.3-000000?logo=jsonwebtokens&logoColor=white) ![Python-Jose](https://img.shields.io/badge/Python%20Jose-3.3.0-000000?logo=python&logoColor=white) ![OAuth2](https://img.shields.io/badge/OAuth2-Kakao-FFCD00?logo=kakao&logoColor=black) |
| **AI/ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-2.2.0-EE4C2C?logo=pytorch&logoColor=white) ![MediaPipe](https://img.shields.io/badge/MediaPipe-0.10.11-0097A7) ![OpenCV](https://img.shields.io/badge/OpenCV-4.9.0-5C3EE8?logo=opencv&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-1.26.4-4D77CF?logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-1.7.2-F7931E?logo=scikitlearn&logoColor=white) ![Pillow](https://img.shields.io/badge/Pillow-10.3.0-306998?logo=pillow&logoColor=white) |
| **데이터베이스** | ![MariaDB](https://img.shields.io/badge/MariaDB-11.6-003545?logo=mariadb&logoColor=white) ![JPA](https://img.shields.io/badge/JPA-3.4.1-59666C?logo=hibernate&logoColor=white) ![QueryDSL](https://img.shields.io/badge/QueryDSL-5.0.0-1C8D73) ![Spring Data JDBC](https://img.shields.io/badge/Spring%20Data%20JDBC-6DB33F?logo=spring&logoColor=white) |
| **실시간 통신** | ![WebSocket](https://img.shields.io/badge/WebSocket-STOMP-010101) ![StompJS](https://img.shields.io/badge/StompJS-7.1.1-F05032?logo=javascript&logoColor=white) ![WebRTC](https://img.shields.io/badge/WebRTC-Janus-333333?logo=webrtc&logoColor=white) |
| **환경 변수** | ![Dotenv](https://img.shields.io/badge/Dotenv-4.0.0-ECD53F?logo=dotenv&logoColor=black) |
| **빌드/의존성** | ![Gradle](https://img.shields.io/badge/Gradle-8.11-02303A?logo=gradle&logoColor=white) ![npm](https://img.shields.io/badge/npm-10.x-CB3837?logo=npm&logoColor=white) |
| **테스트** | ![JUnit5](https://img.shields.io/badge/JUnit5-5.10-25A162?logo=junit5&logoColor=white) ![Mockito](https://img.shields.io/badge/Mockito-5.x-78C257) ![Spring Security Test](https://img.shields.io/badge/Spring%20Security%20Test-6DB33F?logo=springsecurity&logoColor=white) ![httpx](https://img.shields.io/badge/httpx-0.27.0-000000?logo=python&logoColor=white) |
| **개발 도구** | ![Lombok](https://img.shields.io/badge/Lombok-1.18.30-9B2C2C?logo=lombok&logoColor=white) ![Devtools](https://img.shields.io/badge/Spring%20DevTools-6DB33F?logo=spring&logoColor=white) ![p6spy](https://img.shields.io/badge/p6spy-1.9.1-DB0000) ![ESLint](https://img.shields.io/badge/ESLint-9.x-4B32C3?logo=eslint&logoColor=white) ![Vite mkcert](https://img.shields.io/badge/Vite%20mkcert-1.17.9-646CFF?logo=vite&logoColor=white) |
| **인프라** | ![AWS EC2](https://img.shields.io/badge/AWS_EC2-FF9900?logo=amazon-ec2&logoColor=white) ![AWS S3](https://img.shields.io/badge/AWS_S3-569A31?logo=amazon-s3&logoColor=white) ![AWS RDS](https://img.shields.io/badge/AWS_RDS-527FFF?logo=amazon-rds&logoColor=white) ![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?logo=kubernetes&logoColor=white) |
| **CI/CD** | ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=github-actions&logoColor=white) ![Jenkins](https://img.shields.io/badge/Jenkins-D24939?logo=jenkins&logoColor=white) ![Terraform](https://img.shields.io/badge/Terraform-7B42BC?logo=terraform&logoColor=white) |
| **협업 도구** | ![Git](https://img.shields.io/badge/Git-F05032?logo=git&logoColor=white) ![GitHub](https://img.shields.io/badge/GitHub-181717?logo=github&logoColor=white) ![Discord](https://img.shields.io/badge/Discord-5865F2?logo=discord&logoColor=white) |
| **개발 환경** | ![IntelliJ IDEA](https://img.shields.io/badge/IntelliJ%20IDEA-000000?logo=intellijidea&logoColor=white) ![Kiro](https://img.shields.io/badge/Kiro-4A90E2) ![Cursor](https://img.shields.io/badge/Cursor-000000) |

---

##  시스템 아키텍처

### 전체 아키텍처 개요

```mermaid
flowchart TD
    subgraph User["사용자"]
        A["웹 브라우저 (React)"]
    end

    subgraph Frontend["Frontend Layer"]
        B["React SPA"]
        C["WebRTC Client (Janus)"]
        D["WebSocket Client (STOMP)"]
    end

    subgraph Backend["Backend Layer (Spring Boot)"]
        E["REST API Controller"]
        F["WebSocket Handler"]
        G["Service Layer"]
        H["Repository Layer"]
        I[("MariaDB (RDS)")]
    end

    subgraph AIServer["AI Server (FastAPI)"]
        J["WebSocket Handler"]
        K["Landmark Extractor (MediaPipe)"]
        L["ML Model (PyTorch)"]
        M["Predictor"]
    end

    subgraph ExternalServices["외부 서비스"]
        N["Kakao OAuth2"]
        O["AWS S3"]
        P["Janus WebRTC Gateway"]
    end

    A --> B
    B --> C
    B --> D
    B -->|"REST API"| E
    D -->|"WebSocket (STOMP)"| F
    C -->|"WebRTC"| P
    E --> G
    F --> G
    G --> H
    H --> I
    G -->|"OAuth2"| N
    G -->|"파일 업로드"| O
    
    B -->|"WebSocket"| J
    J --> K
    K --> L
    L --> M
    M -->|"추론 결과"| J
```

### 주요 데이터 흐름

1. **개인 수어 학습 (거울 모드)**
    - 사용자가 웹캠으로 수어 동작 수행
    - React에서 MediaStream을 FastAPI 서버로 WebSocket 전송
    - MediaPipe로 랜드마크 추출 (147차원 특징 벡터)
    - PyTorch 모델로 수어 동작 인식 및 유사도 계산
    - 실시간 피드백 및 점수를 클라이언트로 반환

2. **실시간 수어 퀴즈 게임**
    - 사용자가 게임방 생성/입장
    - Janus Gateway를 통한 4인 WebRTC 화상 연결
    - Spring Boot WebSocket으로 게임 상태 실시간 동기화
    - 도전자가 수어 동작 수행 시 FastAPI로 전송하여 정답 판정
    - 점수 집계 및 게임 결과를 MariaDB에 저장

-----

##  대표 문서

### 기획 및 요구사항
- [프로젝트 개요](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/SignBell_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EA%B0%9C%EC%9A%94.md)
- [기획 배경 및 동기](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/SignBell_%EA%B8%B0%ED%9A%8D%20%EB%B0%B0%EA%B2%BD%20%EB%B0%8F%20%EB%8F%99%EA%B8%B0.md)
- [사용자 페르소나](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/SignBell_%EC%82%AC%EC%9A%A9%EC%9E%90%20%ED%8E%98%EB%A5%B4%EC%86%8C%EB%82%98.md)
- [역할분담 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/SignBell_%EC%97%AD%ED%95%A0%EB%B6%84%EB%8B%B4%20%EB%AA%85%EC%84%B8%EC%84%9C.md)

### 시스템 설계 및 명세
- [시스템 아키텍처](https://github.com/SynergySign/SignBell-Docs/blob/dev/02_Architecture/SignBell%20%EC%8B%9C%EC%8A%A4%ED%85%9C%20%EC%95%84%ED%82%A4%ED%85%8D%EC%B2%98.md)
- [기술 스택](https://github.com/SynergySign/SignBell-Docs/blob/dev/02_Architecture/SignBell_%EA%B8%B0%EC%88%A0%20%EC%8A%A4%ED%83%9D.md)
- [개념 ERD 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/02_Architecture/SignBell%20-%20%EA%B0%9C%EB%85%90%20ERD%20%EB%AA%85%EC%84%B8%EC%84%9C.md)
- [논리 ERD 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/02_Architecture/SignBell-%20%EB%85%BC%EB%A6%AC%20ERD%20%EB%AA%85%EC%84%B8%EC%84%9C.md)
- [API 명세서 (REST)](https://github.com/SynergySign/SignBell-Docs/blob/dev/03_Specifications/SignBell%20-%20API%20%EB%AA%85%EC%84%B8%EC%84%9C.md)
- [WebSocket API 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/03_Specifications/SignBell_%EC%8B%A4%EC%8B%9C%EA%B0%84%20%EC%88%98%EC%96%B4%20%ED%80%B4%EC%A6%88%20Web%20socket%20API%20%EB%AA%85%EC%84%B8%EC%84%9C.md)
- [기능 요구사항 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/SignBell_%EA%B8%B0%EB%8A%A5%20%EC%9A%94%EA%B5%AC%EC%82%AC%ED%95%AD%20%EB%AA%85%EC%84%B8%EC%84%9C.md)

### 개발 가이드
- [백엔드 및 프론트엔드 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-App/blob/dev/README.md)
- [FastAPI 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-FASTAPI/blob/dev/README.md)
- [머신 러닝 설치 및 실행 가이드](https://github.com/SynergySign/SignBell-ML)
- [수어인식 서버 기술 명세서](https://github.com/SynergySign/SignBell-Docs/blob/dev/03_Specifications/SignBell%20-%20%EC%88%98%EC%96%B4%EC%9D%B8%EC%8B%9D%EC%84%9C%EB%B2%84%20%EA%B8%B0%EC%88%A0%EB%AA%85%EC%84%B8%EC%84%9C.md)
- [클라이언트-수어인식 파이프라인](https://github.com/SynergySign/SignBell-Docs/blob/dev/03_Specifications/SignBell%20-%20%ED%81%B4%EB%9D%BC%EC%9D%B4%EC%96%B8%ED%8A%B8%20-%20FAST%20API%20%ED%8C%8C%EC%9D%B4%ED%94%84%EB%9D%BC%EC%9D%B8.md)

### 정책 및 약관
- [서비스 필수 이용약관](https://github.com/SynergySign/SignBell-Docs/blob/dev/05_Policies/SignBell%20-%20%EC%84%9C%EB%B9%84%EC%8A%A4%20%ED%95%84%EC%88%98%20%EB%8F%99%EC%9D%98%20%EC%95%BD%EA%B4%80.md)
- [서비스 선택 이용약관](https://github.com/SynergySign/SignBell-Docs/blob/dev/05_Policies/SignBell%20-%20%EC%84%9C%EB%B9%84%EC%8A%A4%20%EC%84%A0%ED%83%9D%20%EB%8F%99%EC%9D%98%20%EC%95%BD%EA%B4%80.md)
- [법적 리스크](https://github.com/SynergySign/SignBell-Docs/blob/dev/05_Policies/legal/SignBell_%EB%B2%95%EC%A0%81%20%EB%A6%AC%EC%8A%A4%ED%81%AC.md)

### 전체 문서 폴더
- [01_Planning](https://github.com/SynergySign/SignBell-Docs/tree/dev/01_Planning) - 프로젝트 기획 문서
- [02_Architecture](https://github.com/SynergySign/SignBell-Docs/tree/dev/02_Architecture) - 시스템 아키텍처 및 설계 문서
- [03_Specifications](https://github.com/SynergySign/SignBell-Docs/tree/dev/03_Specifications) - 프로젝트 세부 스펙 문서
- [04_Guides](https://github.com/SynergySign/SignBell-Docs/tree/dev/04_Guides) - 프로젝트 내부 규칙 및 개발 가이드
- [05_Policies](https://github.com/SynergySign/SignBell-Docs/tree/dev/05_Policies) - 프로젝트 정책 관련 문서
- [06_meeting-notes](https://github.com/SynergySign/SignBell-Docs/tree/dev/06_meeting-notes) - 프로젝트 회의록
- [07_troubleShooting](https://github.com/SynergySign/SignBell-Docs/tree/dev/07_troubleshooting) - 팀,개인 트러블 슈팅
- [08_ml-development](https://github.com/SynergySign/SignBell-Docs/tree/dev/08_ml-development) - 수어 인식 모델 개발 과정

### 협업 규칙 & 기여 문서
- [문서 버전 관리 규칙](https://github.com/SynergySign/SignBell-Docs/blob/dev/04_Guides/collaboration/doc-versioning-rules.md)
- [Git 워크플로우 규칙](https://github.com/SynergySign/SignBell-Docs/blob/dev/04_Guides/collaboration/git-workflow.md)

-----

##  향후 업데이트 계획

### Phase 1 (v1.1.0) — AI 모델 고도화 및 UX 개선

* **AI 모델 성능 향상**
    * 더 많은 수어 단어 데이터셋 확보 및 학습
    * 모델 경량화를 통한 추론 속도 개선
    * 실시간 피드백 정확도 향상

* **사용자 경험 개선**
    * 학습 진도 추적 및 통계 대시보드
    * 오답 노트 및 복습 기능
    * 다크 모드 지원

### Phase 2 (v1.2.0) — 소셜 기능 및 콘텐츠 확장

* **소셜 기능**
    * 친구 추가 및 학습 기록 공유
    * 리더보드 및 랭킹 시스템
    * 팀 대항전 모드

* **콘텐츠 확장**
    * 문장 단위 수어 학습
    * 상황별 수어 회화 학습
    * 수어 스토리텔링 콘텐츠

### Phase 3 (v2.0.0) — 멀티 플랫폼 및 글로벌 확장

* **멀티 플랫폼**
    * 모바일 앱 (iOS/Android)
    * 태블릿 최적화
    * PWA 지원

* **글로벌 확장**
    * 다국어 수어 지원 (ASL, BSL 등)
    * 다국어 UI/UX
    * 글로벌 커뮤니티 구축

> 자세한 내용은 [프로젝트 로드맵](https://github.com/SynergySign/SignBell-Docs/blob/dev/01_Planning/%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8%20%EB%A1%9C%EB%93%9C%EB%A7%B5%20%EB%AA%85%EC%84%B8%EC%84%9C.md) 문서를 참고 바랍니다.

---

##  문의

> 궁금한 점은 언제든 GitHub Issue를 통해 문의 바랍니다.

**문의:** GitHub Issues 또는 Pull Request

**프로젝트 관리:** [Team SynergySign](https://github.com/SynergySign)

**레포지토리:**
- [signbell-app](https://github.com/SynergySign/signbell-app) - Frontend & Backend
- [signbell-docs](https://github.com/SynergySign/signbell-docs) - 프로젝트 문서
- [signbell-fastapi](https://github.com/SynergySign/signbell-fastapi) - AI 추론 서버
- [signbell-ml](https://github.com/SynergySign/signbell-ml) - ML 모델 개발
