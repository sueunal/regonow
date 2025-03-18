
![image](https://github.com/user-attachments/assets/5d03dff3-e4d6-4ded-8a42-0ab154bd7e42)

## 📌 프로젝트 개요
- **🗓️ 프로젝트 기간: 2024. 01 ~ 2024 04 (4 개월)**
- 최소 버전: **iOS 16+**

REGOnow는 **운전자를 위한 AI 기반 드라이브 코스 추천 및 공유 앱**입니다.   
- 사용자는 **드라이브 코스를 추천받고, 자신만의 명소를 공유**할 수 있습니다.
- **네이버 지도 기반 경로 추천, AI 코스 생성, 실시간 파티 모집 기능**을 제공합니다.





## 📊 **성과 및 결과**
1. **AI 기반 드라이브 코스 추천 기능 구현**

2. **네이버 지도 API를 활용한 실시간 경로 탐색 지원**

3. **실제 사용자 테스트를 통해 만족도 분석 (추가 필요: 테스트 결과 수치화)**

## 🎯 **핵심 기능**

**AI 드라이브 코스 추천** – 사용자의 취향에 맞춘 드라이브 코스 자동 생성

**네이버 지도 기반 경로 탐색** – 실시간 교통 정보를 반영한 최적 코스 제공

**드라이브 파티 모집** – 함께 드라이브할 사람을 모집하고 그룹 형성

**사용자 명소 공유** – 자신만의 드라이브 코스 및 명소를 공유

### 앱 메인 / 사용자 프로필 화면


![image](https://github.com/user-attachments/assets/127ad073-d4aa-4fb9-afc8-20b1b739c4da)


### 레고나우 AI 드라이브 계획 생성 화면

![image](https://github.com/user-attachments/assets/a33d6b98-37eb-4b48-adcd-563d83491707)


### 레고나우 AI 드라이브 결과 화면

![image](https://github.com/user-attachments/assets/0ffd04ac-8b44-412c-b762-f93acae2891b)

  

## 🔥 **사용 기술 및 구현 방식**

**네트워크 및 데이터 처리**

- **Alamofire + REST API** – 서버와의 원활한 데이터 송수신
- **JWT 기반 인증** – UserDefaults에 Refresh Token 저장 후, Access Token을 통한 로그인 인증

**지도 & 위치 서비스**

- **네이버 지도 API** – 지도 상에 마커 표시 및 출발지-목적지 경로 탐색
- **카메라 이동 및 줌 기능** – 경로별 주요 포인트 자동 확대/축소

**iOS 클라이언트**

- **MVVM 아키텍처** – UI와 비즈니스 로직을 분리하여 유지보수성 강화
- **SwiftUI + GeometryReader** – 반응형 UI 구현 및 디바이스별 최적화

**푸시 알림 & 사용자 경험**

- **FCM (Firebase Cloud Messaging)** – 이벤트 및 공지사항 알림
- **UX 최적화** – 초기 설계 시 색상, 아이콘, 폰트 등의 일관된 디자인 적용

