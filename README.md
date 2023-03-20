# 데이터 공유
 ## java(eclipse) - database 연동 
 - https://github.com/right3667/data-share/blob/main/database_connect.md
  
## Appium - iOS 연동
- Android 4.3 이상: Google의 

## Appium 동작
### - 제품 적용
<image src="doc/launch_flow.jpg" style="width: 150px;"><br>
1. Test Case 의 '시험 절차'와 '시험 결과' 의 스크립트 작성<br>
 사용 언어: Java<br>
 주요 라이브러리: <br>
  AndroidDriver(https://appium.github.io/java-client/io/appium/java_client/android/AndroidDriver.html)
  IOSDriver(https://appium.github.io/java-client/io/appium/java_client/ios/IOSDriver.html)
2. 테스트 구동 및 결과 확인
3. 유지보수 진행

### - 업무 흐름
<image src="doc/project_flow.png" style="width: 150px;"><br>

### - 자동화 시연
 <image src="doc/demonstrate.gif" style="width: 150px;"><br>

1. 시연 환경
 - device: Galaxy S10 5g(Android 10)
 - App: SecureGuard VPN V2.0 (2.0.0.6.10), SecureGuard OTP Lite 2.0.3
 
 2. 시연 과정
  - 버전 확인
  - 설정 저장 테스트
  - ID, PW 로그인 테스트
  - ID, PW, OTP 로그인 테스트
  - '서버 접속 정보 저장' 옵션 테스트
  
