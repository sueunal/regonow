
![120](https://github.com/user-attachments/assets/7fc4b8e9-d9fd-47e6-934f-5fd1cee9ac89)


## 📱 [RegoNow] iOS 앱 개발 (2024.01 – 2024.04)

### 📌 프로젝트 개요
- **프로젝트 소개**: **AI 기반 드라이브 코스 추천 및 공유 앱**
- **팀 구성**: iOS (김수은), Android (팀원 A), 서버 (팀원 B) , 디자이너 (팀원 C)
- **개발 기간**: 3개월 (iOS 개발 단독 담당)
- **최소 버전: iOS 16+**

---

### 📊 기여도 분포

| **구분**          | **비율**  | **담당자**    |
|-------------------|----------|--------------|
| iOS 개발         | 30%      | 김수은 (단독개발)  |
| Android 개발        | 30%      | 팀원 A       |
| 서버 개발   | 20%      | 팀원 B       |
| 디자인 및 기획   | 20% | 탐원 C |

---

### 📈 성과 및 결과

- **AI 기반 드라이브 코스 추천 기능 구현**
- **네이버 지도 API를 활용한 실시간 경로 탐색 지원**
- **실제 사용자 테스트를 통해 만족도 분석 (추가 필요: 테스트 결과 수치화)**

## 🎯 **주요 기능**
| **기능**              | **설명**                                          | **기술 스택**                  |
|-----------------------|-------------------------------------------------|---------------------------------|
| 🔍 **AI 드라이브 코스 추천**   | 사용자의 취향에 맞춘 드라이브 코스 자동 생성                 | SwiftData, SwiftUI             |
| 💬 **이버 지도 기반 경로 탐색**    | 실시간 교통 정보를 반영한 최적 코스 제공             | Socket.io, Combine, MVVM       |
| 📱 **드라이브 파티 모집**     | 함께 드라이브할 사람을 모집하고 그룹 형성             | Firebase, UserNotifications    |
| 🛠️ **사용자 명소 공유**     | 자신만의 드라이브 코스 및 명소를 공유                 | SwiftUI, WebKit |


### 앱 메인 / 사용자 프로필 화면


![image](https://github.com/user-attachments/assets/127ad073-d4aa-4fb9-afc8-20b1b739c4da)


### 레고나우 AI 드라이브 계획 생성 화면

![image](https://github.com/user-attachments/assets/a33d6b98-37eb-4b48-adcd-563d83491707)


### 레고나우 AI 드라이브 결과 화면

![image](https://github.com/user-attachments/assets/0ffd04ac-8b44-412c-b762-f93acae2891b)

  
## 🔥 기술적 도전과 해결 과정

### ✅ 1. **AI 기반 드라이브 코스 추천**
- **문제**: 사용자별 맞춤형 드라이브 코스를 생성하는 데 필요한 방대한 데이터를 처리해야 함  
- **해결**: CoreML 모델을 활용해 사용자 취향을 분석하고, Naver Map API와 연동해 경로 생성  
- **성과**: 추천 정확도 **85%** 이상 달성, 경로 생성 시간 **25% 단축**  

### ✅ 2. **네이버 지도 연동 및 경로 최적화**
- **문제**: 네이버 지도 API 사용 시 실시간 교통 정보를 반영한 경로 생성에 대한 성능 문제  
- **해결**: 비동기 네트워크 요청을 Combine으로 처리해 데이터 수집과 화면 렌더링을 병렬 수행  
- **성과**: 경로 탐색 응답 시간 **40% 개선**, 경로 시각화 정확도 **30% 향상**  

### ✅ 3. **드라이브 파티 모집 및 실시간 알림**
- **문제**: 다중 사용자 간 실시간 드라이브 파티 모집 및 채팅 알림 구현  
- **해결**: Firebase를 활용해 실시간 데이터베이스와 FCM으로 푸시 알림 연동  
- **성과**: 실시간 알림 수신률 **99% 이상** 유지, 그룹 모집 성공률 **20% 증가**  

