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
  - Xcode 실행 후 'Clone an existing project' 클릭<br>
    <image src="doc/iOS_connect/Clone_project.png" style="width: 500px;"><br><br><br>
  - 'Enter repository URL' 에 복제할 WDA 프로젝트 URL 을 입력 후 'Clone' 클릭<br>https://github.com/appium/WebDriverAgent.git<br>
    <image src="doc/iOS_connect/WebDriverAgent_Clone.png" style="width: 500px;"><br><br><br>
### 2-3. Xcode 개발자 계정 등록
  - [Xcode > Preferences > Accounts] 에서 애플 개발자 계정으로 로그인<br>
    <image src="doc/iOS_connect/developer_account.png" style="width: 500px;"><br><br><br>
  - Clone 했던 WDA 프로젝트 'TARGETS' 항목들의 [Signing & Capabilities > all > Team] 을 로그인한 애플 개발자 계정으로 등록하고,<br>
    Bundle Identifier 가 'com.facebook.WebDriverAgentLib' 로 적용됨을 확인<br>
    <image src="doc/iOS_connect/Targets_dev_identifier.png" style="width: 800px;"><br><br><br>
## 3. WDA 빌드 및 인증서 등록
  - Xcode 상단에서 'WebDriverAgentRunner' 및 Mac PC와 연결된 테스트 기기를 선택한 뒤 빌드<br>
    <image src="doc/iOS_connect/WebDriverAgentRunner_build.png" style="width: 800px;"><br><br><br>
  - [Product > Test] 으로 Test 빌드하여 연결된 테스트 기기에 앱 설치<br>
    <image src="doc/iOS_connect/Product_Test.png" style="width: 800px;"><br>
    <image src="doc/iOS_connect/app_install.PNG" style="width: 400px;"><br><br><br>
## 4. Appium 연동
  - Appium Inspector 실행하여 Capability 설정<br>
    <image src="doc/iOS_connect/Appium_inspector.PNG" style="width: 800px;"><br><br><br>
  - 연동 완료<br>
    <image src="doc/iOS_connect/ios_appium_connect.PNG" style="width: 800px;"><br><br><br>
