<center><font size="5em" color="#0091ff">칼리리눅스part.1</font> </center>


<font size="3em" color="#0091ff">
<br>
<font size="4em" color="#0091ff">칼리리눅스part.1</font><br>
18_리눅스터미널<br><br>
칼리리눅스도 리눅스의 한 종류 요즘 윈도우처럼 GUI 즉<br> 그래픽 사용자 인터페이스 가 기본으로
지원하지만<br><br> CLI 즉 텍스트 기반 인터페이스 에서만 작동되는<br>
혹은 효율적인 요소들이 많아 주로 CLI 를 많이 쓴다 <br>
<br><br>

칼리리눅스 명령어 및 프로그램 정리<br>
- (칼리)리눅스 기본 : man, find, which, gedit, vi, nano, service, nc<br>
- 스캐닝 : theharvster, recon-ng, host, dnsenum, smtp-user-enum, nmap, nikto, sparta<br>
- 네트워크스니핑 : wireshark, arpspoof<br>
- 침투/포스트익스플로잇 : Metasploit*, sqlmap, davtest, msfvenom,<br> setoolkit, hydra, ncrack, john<br>


＊메타스플로잇의 경우, 각종 익스플로잇, 리버스쉘 핸들링,<br> 권한상승, 퍼시스턴스 등 다양한 모튤 사용<br>

- 기타 명령어 : touch, find / | grep 찾을대상<br>
<br><br>
터미널 에디터<br>
  - vi  : <br>
    - 실행 : vi 실행할 텍스트 파일 이름<br>
    -  i 를 눌러 편집모드 활성<br>
    -  esc를 눌러 편집모드 에서 나옴<br>
    -  파일 저장시 ':'을 눌러 wq 입력후 엔터<br>
  - nano : 
    - 바로 텍스트 입력가능<br>
    - '^'는 Ctrl를 의미<br>
    - 저장후 나갈려면 Ctrl+x 를 누르고<br> Y을 누르고 파일이름 작성후 종료<br>

service 명령어<br>

- service apache2 status : 실행되고 있는 웹서비스 확인<br>
- service apache2 start : 웹서버 실행<br>
- service --status-all : 다른 웹서버를 볼려면 <br>
</font>