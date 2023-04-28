# Appium - iOS 연동
## 1. 준비 사항
  - Mac PC (맥북 또는 아이맥)
  - iPhone
  - 애플 개발자 계정
## 2. WebDriverAgent(WDA) 설정
  - WebDriverAgent는 iOS 기기를 조작할 수 있게 해주는 python library.
  - Facebook에서 테스트를 위해 만든 library, 오픈소스
  - Appium 에서 WebDriverAgent를 통해 iOS 기기를 제어하기 때문에 테스트 기기에 WDA 설치 필요
  - WebDriverAgent 적용
  2-1. Xcode에서 WDA 프로젝트 Clone
  - asd
  3. 
    <image src="doc/database_connect/unzip.png" style="width: 800px;"><br><br><br>

## 3. Build Path
  - JDBC 를 사용할 프로젝트 [우클릭 > Build Path > Configure Build Path] 이동
  - 'Properties for <프로젝트 명>' 화면에서 'Libraries' 탭 클릭
  - 'Add External JARs...' 버튼 클릭<br>
    <image src="doc/database_connect/add_external_jars.PNG" style="width: 800px;"><br><br><br>
  - 연동을 위해 아래의 파일들을 'Open' 합니다.<br>
  3-1. ojdbc11.jar<br>
  3-2. osdt_cert.jar<br>
  3-3. osdt_core.jar<br>
  3-4. oraclepki.jar<br>
    <image src="doc/database_connect/jar_open.PNG" style="width: 800px;"><br><br><br>
  - 추가 후 'Apply and Close' 버튼 클릭

 ## 4. DB 접속
 - java 파일 생성 후 코드 실행 시 db 연동 성공 메시지 출력<br>
    <image src="doc/database_connect/connect_database.PNG" style="width: 800px;"><br><br><br>

      
 ## 5. DB insert 실행
 - insert 코드 작성<br>
    <image src="doc/database_connect/test_insert.PNG" style="width: 800px;"><br><br><br>
 - DB 확인 시 insert 됨을 확인<br>
    <image src="doc/database_connect/confirm_database.PNG" style="width: 800px;"><br><br><br>
