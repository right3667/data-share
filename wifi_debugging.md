# iOS, Android WIFI 디버깅
 ## iOS WIFI 디버깅
 1. PC, iPhone device를 USB 연결 후 [Xcode > Window > Devices and Simulators] 이동<br>
 <image src="doc/wifi_build/devices_and_simulators.png" style="width: 800px;"><br><br><br>
 2. 'Devices' 에서 연결된 iPhone device 선택 후 'Connect via network' 옵션 확인<br>
 <image src="doc/wifi_build/uncheck_Connect_via_network.png" style="width: 800px;"><br><br><br>
 3. 'Connect via network' 체크 후 연결된 iPhone device 에 네트워크 표시됨을 확인<br>
 <image src="doc/wifi_build/check_Connect_via_network.png" style="width: 800px;"><br><br><br>
  
  
## Android WIFI 디버깅
 1. PC, Android device를 USB 연결 후 터미널에서 'adb devices' 명령어 입력하여 연결된 device 확인<br>
 <image src="doc/wifi_build/adb_devices_1.png" style="width: 800px;"><br><br><br>
 2. adb 에서 TCP/IP 연결을 하기위해 'adb tcpip 5555' 포트 열기<br>(5555 외 다른 포트 사용 가능)<br>
 <image src="doc/wifi_build/adb_tcpip.png" style="width: 800px;"><br><br><br>
 3. Android device의 IP주소에 연결을 위해 'adb connect <Android device IP주소>' 입력<br>
 <image src="doc/wifi_build/adb_connect.png" style="width: 800px;"><br><br><br>
 4. 'adb devices' 명령어 입력하여 네트워크로 연결된 device 확인<br>
 <image src="doc/wifi_build/adb_devices_2.png" style="width: 800px;"><br><br><br>
