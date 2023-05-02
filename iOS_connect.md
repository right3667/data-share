# Appium - iOS 연동
## 1. 준비 사항
  - Mac PC (맥북 또는 아이맥)
  - iPhone
  - 애플 개발자 계정
## 2. WebDriverAgent(WDA) 설정
### 2.1. WebDriverAgent 이란
  - iOS 기기를 조작할 수 있게 해주는 python library.
  - Facebook에서 테스트를 위해 만든 library, 오픈소스
  - Appium 에서 WebDriverAgent를 통해 iOS 기기를 제어하기 때문에 테스트 기기에 WDA 설치 필요<br>
### 2-2. WebDriverAgent 적용
  - Xcode 실행 후 'Clone an existing project' 클릭
  - 'Enter repository URL' 에 복제할 WDA 프로젝트 URL 을 입력 후 'Clone' 클릭한다.<br> https://github.com/appium/WebDriverAgent.git

### 2-3. Xcode 개발자 계정 등록
  - [Xcode > Preferences > Accounts] 에서 애플 개발자 계정으로 로그인
  - Xcode 에서 Clone 했던 WDA 프로젝트의 'TARGETS' 항목들의 [Signing & Capabilities > all > Team] 을 로그인한 애플 개발자 계정으로 등록한다.
  - 동일한 WDA 프로젝트의 'TARGETS' 항목들의 [Signing & Capabilities > all > Bundle Identifier] 가 'com.facebook.WebDriverAgentLib' 로 적용됨을 확인한다.
## 3. WDA 빌드 및 인증서 등록
  - 
