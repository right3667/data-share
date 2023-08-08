# Appium - Mac OS 연동
## 1. 준비 사항
  - Mac PC (맥북 또는 아이맥)
## 2. appium-for-mac 설정
### 2.1. appium-for-mac 이란
  - Selenium/WebDriver 및 OS X Accessibility API를 사용하여 Mac 애플리케이션의 기본 사용자 인터페이스 제어<br>
  - Mac OS X 10.7 이상<br>
### 2-2. appium-for-mac 적용
  - appium-for-mac 최신 릴리즈 다운로드(zip 파일) 및 압축 해제<br>
    https://github.com/appium/appium-for-mac/releases<br>
    <image src="doc/Mac_connect/download.png" style="width: 400px;"><br><br><br>
  - 실행 및 개인정보 보호 및 보안 허용 설정<br>
    <image src="doc/Mac_connect/permit.png" style="width: 500px;"><br><br><br>
## 3. Appium 연동
  - Appium Inspector 실행하여 Capability 설정 후 'start session' 버튼 클릭<br>
    <image src="doc/Mac_connect/Capability.png" style="width: 800px;"><br><br><br>
  - 연동 완료<br>
    <image src="doc/Mac_connect/mac_appium_connect.png" style="width: 800px;"><br><br><br>
  - 엘리먼트 컨트롤 시 (fn) 키를 3초 이상 누를경우 AXpath 가 클립보드에 저장되어 코드 작성
    
