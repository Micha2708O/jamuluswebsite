<!-- 참고: 이것은 클라이언트와 서버, 그리고 모든 운영 체제에 모두 적용되어야 합니다 -->

설치 및 실행이 완료되면 설정 복사본을 보관할 수 있습니다. 백업을하는 것은 항상 좋은 생각이며 설정 파일은 Jamulus 버전간에 이전
버전과 호환되지 않습니다. 따라서 이전 버전으로 돌아가려면 사용 중인 설정을 복원해야 합니다.

Windows에서 사용자의 설정 파일을 찾으려면 검색 창에 '%APPDATA%'를 입력하고 'Jamulus'라는 폴더를 찾습니다. 이
폴더에는 하나 이상의 '.ini'파일이 있습니다. 이제 Jamulus의 설정을 백업하십시오.

다른 모든 플랫폼의 경우 명령줄에서 다음을 실행하여 해당 플랫폼이 있는 위치를 찾고 파일을 다른 위치로 복사합니다:

`find ~ -name Jamulus.ini -ls`

'--inifile'매개 변수를 사용하여 inifile을 다른 위치에 저장했다면 이 파일도 백업하는 것을 잊지 마십시오.  **주의할
점들**

* Jamulus가 실행 중일 때 설정 파일을 백업하거나 복원하지 마십시오.
* 설정 파일을 수동으로 편집하는 것은 권장되지 않습니다(이를 위해 설계되지 않음).
* Jamulus를 닫은 후 설정 파일을 삭제하여 모든 설정을 기본값으로 되돌릴 수 있습니다.