# 이클립스 - 오라클 DB 연동
## 1. 오라클 JDBC 다운로드
  - JDBC(Java Database Connectivity)는 자바에서 데이터베이스에 접속할 수 있도록 하는 자바 API
  - 설치되어있는 Java 버전에 맞게 JDBC 다운로드
  - JDBC 다운로드: https://www.oracle.com/kr/database/technologies/appdev/jdbc-downloads.html<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>  
## 2. 오라클 JDBC 워크스페이스에 압축 해제
  - 이클립스에서 작업하는 프로젝트가 있는 폴더에 JDBC 를 압축 해제<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>

## 3. Build Path
  - JDBC 를 사용할 프로젝트 [우클릭 > Build Path > Configure Build Path] 이동
  - 'Properties for <프로젝트 명>' 화면에서 'Libraries' 탭 클릭
  - 'Add External JARs...' 버튼 클릭<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>
  - 연동을 위해 아래의 파일들을 'Open' 합니다.<br>
  3-1. ojdbc11.jar<br>
  3-2. osdt_cert.jar<br>
  3-3. osdt_core.jar<br>
  3-4. oraclepki.jar<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>
  - 추가 후 'Apply and Close' 버튼 클릭

 ## 4. DB 접속
 - java 파일 생성 후 코드 실행 시 db 연동 성공 메시지 출력<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>

      
 ## 5. DB insert 실행
 - insert 코드 작성<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>
 - DB 확인 시 insert 됨을 확인<br>
    <image src="doc/appium-logo-sauce-white.png" style="width: 150px;"><br><br><br>
