# Appium-data
 ## Appium
 <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br>
 - 모바일 애플리케이션의 테스트 자동화를 가능하게 해주는 오픈소스 라이브러리
 - native, hybrid, mobile web 등 모든 타입의 모바일 애플리케이션의 테스트 자동화
 - WebDriver 프로토콜을 사용하여 iOS, Android 앱 구동
 - Java, Python, Javascript, Ruby, C# 언어 지원
 - Appium <a href="https://appium.io/" target="_blank">공식 페이지</a>
 - Appium <a href="https://github.com/appium" target="_blank">GitHub</a>
  
## Appium 구조
<image src="doc/structure_launch3.jpg" style="width: 150px;"><br>
- iOS 9.3 이상: Apple의 <a href="https://developer.apple.com/documentation/xctest" target="_blank">XCUITest</a>
- iOS 9.3 이하: Apple의 <a href="https://web.archive.org/web/20160425114149/https://developer.apple.com/library/ios/documentation/DeveloperTools/Reference/UIAutomationRef/" target="_blank">UIAutomation</a>
- Android 4.3 이상: Google의 <a href="https://developer.android.com/training/testing/ui-automator?hl=ko" target="_blank">UiAutomator/UiAutomator2</a>

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
  
