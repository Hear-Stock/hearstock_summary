<div align="center">
  <img width="200" alt="Hear-Stock Logo" src="https://github.com/user-attachments/assets/47e5b0c2-56ee-4af4-a43c-8e9b1118b804" />

  <h1>이어스톡 (Hear-Stock)</h1>

  <h3>사용자 의도 처리 및 비선형 그래프의 청각화를 통한<br/>저시력 투자자 접근성 향상 솔루션</h3>

  <p>
    <b>"주식의 흐름을 듣다, 투자의 눈을 뜨다"</b><br/>
    음성 기반 주식 정보 제공 및 청각적 시각화(Sonification) 플랫폼
  </p>

  <img src="https://img.shields.io/badge/Version-1.0.0-orange?style=flat-square" alt="Version">
  <img src="https://img.shields.io/badge/Platform-Mobile-blue?style=flat-square" alt="Platform">
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square" alt="License">

  <br/><br/>
</div>

## 🏆 수상 내역 (Awards)

<div align="center">

| 수상 일자 | 대회명 | 상격 | 주최/주관 |
|:---:|:---:|:---:|:---|
| 2025.08. | 제2회 전국대학 소프트웨어 성과 공유 포럼 | 부산광역시장상 (대상) | 부산시, 과기부, IITP / 동아대 |
| 2025.08. | 제2회 전국대학 소프트웨어 성과 공유 포럼 | 최우수상 | 부산시, 과기부, IITP / 동아대 |
| 2025.08. | 제2회 전국대학 소프트웨어 성과 공유 포럼 | 인기상 | 부산시, 과기부, IITP / 동아대 |
| 2025.11. | 동아대학교 SW중심대학사업 [2025 FairDay] | 최우수상 | 동아대학교 소프트웨어혁신센터 |
| 2025.11. | 대학생 논문 경진대회 | 장려상 | 한국 방송/미디어 공학회 |

<br/>

<table>
  <tr>
    <td align="center">
      <b>🎙️ 프로젝트 발표 영상</b><br/>
      <a href="https://youtu.be/UvgBBUuqRj4?t=17730">
        <img src="https://img.youtube.com/vi/UvgBBUuqRj4/mqdefault.jpg" width="300" alt="발표영상">
      </a>
    </td>
    <td align="center">
      <b>🗣️ 실제 사용자(시각장애인/저시력자) 인터뷰</b><br/>
      <a href="https://www.youtube.com/watch?v=2aX9ofm55pQ">
        <img src="https://img.youtube.com/vi/2aX9ofm55pQ/mqdefault.jpg" width="300" alt="인터뷰영상">
      </a>
    </td>
  </tr>
</table>

(프로젝트 발표 영상 초반에 Team Info가 '한미영미'로 잘못 표기되어 있습니다. -> '보이지 않는 손' 팀입니다.)

</div>

<br/>

## 🟠 프로젝트 소개
> **한 줄 소개**: 비선형 그래프의 청각화와 사용자 의도 처리를 통한 저시력자 투자자의 투자 접근성 향상 어플리케이션<br/>
> **문제 의식**: 시각 정보 중심의 주식 시장(차트, 호가창)에서 시각 장애인은 정보 격차를 겪고 있습니다.<br/>
> **해결 방안**: 주식 데이터를 '소리'로 변환(Sonification)하고, 음성 명령(STT)을 통해 복잡한 조작 없이 정보를 조회하는 시스템을 개발했습니다.

### 💡 개발 배경 및 목적
- 기존 스크린 리더(TalkBack)의 한계점 보완
- 복잡한 주식 차트의 비선형적 데이터를 청각적으로 직관화

### 💡 기대 효과
- **접근성 향상**: 시각적 제약 없는 평등한 금융 정보 제공
- **직관적 파악**: 소리의 높낮이와 공간 음향을 통한 주가 흐름 파악
- **사용자 경험(UX) 개선**: 음성 인터페이스(VUI)를 통한 편리한 조작

<br/>

## 🟠 주요 기능 (Key Features)

| 기능 (Function) | 설명 (Description) |
|:---:|---|
| **AI 기반 명령 처리 시스템** | Open AI를 활용한 의도 파악 및 JSON 형식 변환 처리 |
| **WCAG 2.1 표준** | 인식 가능, 이해 가능, 운용 가능, 견고성의 WCAG 4가지 표준을 지키는 디자인 |
| **음향 설정** | 저/고주파에서 더 쉬운 파악을 위한 Log Scale 적용과 공간적 인지성 강화를 위한 잔향 부여 |
| **가격/시간 3D 공간 좌표 매핑** | 최소가청각도(MAA)를 고려한 값, 날짜 정규화이후 데카르트 좌표계를 활용해 3차원 좌표 생성   |
| **HRTF/음상 외재화 적용** | Head-Related-Transfer-Function과 방향감, 끊김, 연속성을 고려한 외재화 적용 |
| **사용자설정 테마** | Flutter shared-preferences 라이브러리를 활용한 Protanopia, Deuteranopia, Tritanopia 전용 테마 |

<div align="center">
  <img src="https://github.com/user-attachments/assets/a14fe4bf-b05b-429d-a498-7ee0de86835c" width="45%">
  <img src="https://github.com/user-attachments/assets/d3281701-f842-4e5e-ad2d-5f02adbb263a" width="45%">
  <img src="https://github.com/user-attachments/assets/10ebbddb-9a87-4611-b20e-35025861e01c" width="45%">
  <img src="https://github.com/user-attachments/assets/e9ad5ef8-c039-467f-8b9d-ac618f6f3461" width="45%">
</div>

<br/>

## 🛠 기술 스택 (Tech Stack)

<div align="center">

<a href="https://github.com/msdio/stackticon">
  <img src="https://firebasestorage.googleapis.com/v0/b/stackticon-81399.appspot.com/o/images%2F1756453933282?alt=media&token=cd12d61f-c09b-448c-b0f4-b1df1dfcf74b" alt="stackticon" />
</a>

<br/>

| 구분 | 기술 (Skills) |
|:---:|---|
| **Frontend** | React, Flutter |
| **Backend** | FastAPI, redis |

</div>

### 📂 Repository
<div align="center">

| <img src="https://img.shields.io/badge/Frontend-3776AB?style=flat-square&logo=react&logoColor=white"> | <img src="https://img.shields.io/badge/Backend-29961D?style=flat-square&logo=springboot&logoColor=white"> | <img src="https://img.shields.io/badge/AI_&_Sound-CF770F?style=flat-square&logo=python&logoColor=white"> |
|:---:|:---:|:---:|
| [👉 Frontend Repo](https://github.com/Hear-Stock/hearstock-frontend) | [👉 Backend Repo](https://github.com/Hear-Stock/hearstock-backend) | [👉 Sound/AI Repo]() |

</div>

<br/>

## 🏗 시스템 아키텍처 (System Architecture)

### 🔄 서비스 흐름도
<div align="center">
  <img width="80%" alt="Service Flow" src="https://github.com/user-attachments/assets/07e359d3-64c5-4acf-995e-cc06cc41d36e" />
</div>

<br/>

## 📱 화면 구성 (Preview)

<div align="center">
  <img width="1704" height="685" alt="image" src="https://github.com/user-attachments/assets/d63194e9-bd54-442a-a7b5-52fd513177bd" />
</div>

<br/>

## 🚀 시작하기 (Getting Started)

이 프로젝트를 로컬 환경에서 실행하려면 다음 단계가 필요합니다.
(.env, 서버 상태에 따라 실행되지 않을 수 있습니다.)

```bash
# Repository 클론
$ git clone [https://github.com/Hear-Stock/hearstock-frontend.git](https://github.com/Hear-Stock/hearstock-frontend.git)

# 패키지 설치
$ npm install

# 실행
$ npm start
```
