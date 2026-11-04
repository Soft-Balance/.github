# Soft Balance

> **기술의 가능성과 실제 사용 경험 사이의 균형을 만드는 팀**

Soft Balance는 모바일 앱, 웹, 센서와 임베디드 기술을 연결해 일상에서 직접 사용할 수 있는 제품을 탐구합니다. 아이디어를 화면에 그치는 데서 끝내지 않고, 프로토타입을 만들고 실제 동작 범위와 아직 검증되지 않은 부분을 구분해 기록합니다.

## Featured Projects

| Project | Period | Description | Link |
| --- | --- | --- | --- |
| **BarSense** 🏆 | 2026 | 바벨의 기울기와 반복 횟수를 확인하고 세트·휴식·운동 기록을 관리하는 센서와 모바일 앱 | [Project Details](https://github.com/Soft-Balance/.github/blob/main/barsense/detail-barsense.md) |
| **K-Fitness** | 2023 | 교내 헬스장과 운동 정보를 제공하기 위해 제작한 웹 프로그래밍 프로젝트 | [Repository](https://github.com/Soft-Balance/K-Fitness) |

### BarSense

`MPU-6050 센서` → `Arduino Uno` → `HC-06` → `Android 앱`

- Android에서 Y/Z축 기울기와 누적 반복 횟수 수신
- 운동 선택, 수동 세트 종료, 휴식과 기록 관리 흐름 구현
- SwiftUI 기반 iOS 화면과 기록 흐름 구현
- 소형화 제품의 기구·PCB 배치 방향 설계
- **2026학년도 상명대학교 창업경진대회 우수상**

현재 실제 기능 검증 목업은 Arduino Uno, MPU-6050, HC-06과 Android 앱을 사용합니다. BLE 기반 iOS 센서 연결, 배터리, 자동 세트 종료와 소형 PCB는 후속 개발·검증 범위입니다. 개발 저장소는 내부 자료를 포함해 비공개로 운영하고 있습니다.

### K-Fitness

- 회원가입·로그인
- 운동 정보와 지도
- 문의·공지 게시판
- 마이페이지, 결제·라커 화면
- Node.js, Express, EJS, MySQL 기반 구현

현재 서비스 운영은 종료되었으며, 학습 과정과 최종 결과물을 공개 포트폴리오 저장소로 보존하고 있습니다.

## What We Build

- 센서와 모바일 앱을 연결하는 피지컬 컴퓨팅 프로토타입
- 실제 사용 흐름을 중심으로 한 Android·iOS 애플리케이션
- 제품 아이디어를 검증하기 위한 웹 서비스와 인터랙티브 데모
- 구현 결과, 한계, 후속 검증 항목을 함께 남기는 프로젝트 문서

## Technology

**Mobile**  
`Kotlin` `Jetpack Compose` `Swift` `SwiftUI`

**Embedded & Hardware**  
`Arduino` `MPU-6050` `HC-06` `Bluetooth` `KiCad`

**Web & Server**  
`JavaScript` `Node.js` `Express` `Python` `Flask` `MySQL` `SQLite`

## Working Principles

1. 실제로 구현한 기능과 향후 계획을 구분합니다.
2. 프로토타입의 한계와 추가 검증 항목을 함께 기록합니다.
3. 기술보다 사용자가 경험하는 전체 흐름을 먼저 설계합니다.
4. 하드웨어, 소프트웨어와 제품 기획을 하나의 시스템으로 연결합니다.

---

[Soft Balance repositories](https://github.com/orgs/Soft-Balance/repositories) · [Team lead profile](https://github.com/khyun-0123)
