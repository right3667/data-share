# Appium - Windows OS 연동
## 1. 준비 사항
  - Windows10 PC<br><br><br>

## 2. windows10 설정
### 2.1. 개발자 모드 설정
  - [설정 > 업데이트 및 보안 개발자용] 개발자 모드 '켬' <br>
### 2-2. windowsApplicationDriver 설치
  - windowsApplicationDriver 최신 릴리즈 파일 다운로드 후 설치<br>
    https://github.com/microsoft/WinAppDriver/releases<br>
    <image src="doc/Windows_connect/WindowsApplicationDriver.PNG" style="width: 400px;"><br><br><br>
### 2-3. windows SDK 설치
  - windows SDK 최신 릴리즈 파일 다운로드 후 설치<br>
    https://developer.microsoft.com/ko-kr/windows/downloads/sdk-archive/<br>
    <image src="doc/Windows_connect/windowssdk.PNG" style="width: 400px;"><br><br><br>

## 3. Appium 설치
### 3.1. nodejs 설치
  - nodejs 최신 릴리즈 파일 다운로드 후 설치<br>
    https://nodejs.org/en<br>
    <image src="doc/Windows_connect/nodejs.png" style="width: 400px;"><br><br><br>
### 3.2. appium 설치
  - appium 설치 명령어를 입력하여 설치<br>
    npm install -global appium<br>
    <image src="doc/Windows_connect/appium_install.png" style="width: 400px;"><br><br><br>
  - windows 자동화 드라이버 명령어를 입력하여 설치<br>
    appium driver install windows<br>
    <image src="doc/Windows_connect/driver_install.png" style="width: 400px;"><br><br><br>
  - appium 명령어 입력하여 실행<br>
    appium<br>
    <image src="doc/Windows_connect/appium_start.png" style="width: 400px;"><br><br><br>
### 3.3. appium inspector 설치
  - appium inspector 최신 릴리즈 파일 다운로드 후 설치<br>
    https://github.com/appium/appium-inspector<br>
    <image src="doc/Windows_connect/inspector_install.png" style="width: 400px;"><br><br><br>

## 4. Appium 연동
  - Appium Inspector 실행하여 Capability 설정 후 'start session' 버튼 클릭<br>
    <image src="doc/Windows_connect/capability.png" style="width: 800px;"><br><br><br>
  - 연동 완료<br>
    <image src="doc/Windows_connect/windows_appium_connect.png" style="width: 800px;"><br><br><br>
    
