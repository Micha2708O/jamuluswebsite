- `-d` 또는 `--discononquit` 종료 시 모든 클라이언트의 연결을 끊습니다. 일반적으로 서버가 중지되거나 다시 시작되면 서버가 다시 백업될 때 "연결 끊기" 단추를 사용하지 않은 클라이언트는 연결을 다시 설정합니다. 이 옵션을 사용하면 클라이언트가 서버에 대한 연결을 수동으로 다시 설정해야 합니다.
- `-e` 또는 `--directoryserver` 디렉터리에 서버를 등록합니다(예: 장르 설정(`-o` 참조)). 자세한 내용은 [서버 유형](Running-a-Server#server-types)을 참조하십시오.
- `--directoryfile` 디렉터리를 다시 시작해도 등록된 서버를 기억합니다. 디렉터리 서버만 해당됩니다. 자세한 내용은 [이 가이드](디렉터리)를 참조하십시오.
- `-f` 또는 `--listfilter` 화이트리스트 서버 목록에 등록된 서버는 'IP 주소 1[;ip 주소 2]' 디렉터리만 포맷합니다.
- `-F` 또는 `--fastupdate` 클라이언트가 "작은 네트워크 버퍼 활성화" 옵션으로 연결하는 경우 대기 시간을 줄입니다. 드롭아웃을 방지하기 위해 더 빠른 CPU와 활성화된 클라이언트에 더 많은 대역폭이 필요합니다.
- `-l` 또는 `--log` 로깅 활성화, 경로 및 파일 이름 설정
- `-L` 또는 `--licence` 사용자가 연결하기 전에 계약 창 표시
- `-m` 또는 `--htmlstatus` HTML 상태 파일 활성화, 경로 및 파일 이름 설정
- `-o` 또는 `--serverinfo` 형식의 위치 세부 정보: '[이름]; [도시]; [2자리 ISO 국가 코드로 된 국가 또는 Qt5 로케일]'([2자리 ISO 국가 코드](https://ko.wikipedia.org/wiki/ISO_3166-1_alpha-2#Officially_assigned_code_elements) 또는 [Qt5 로케일 값](https://doc.qt.io/qt-5/qlocale.html#Country-enum)) 등록된 서버만 해당)
- `-P` 또는 `--delaypan` 지연 패닝이 활성화된 상태에서 시작합니다. [참고](Running-a-Server#delay-panning)을 참조하십시오
- `-R` 또는 `--recording` 서버 녹음 디렉터리를 설정합니다. 서버는 세션이 기본적으로 활성 상태일 때 기록합니다. [옵션](서버 #옵션 실행)을 참조하십시오.
- `--norecord` 기본적으로 녹음되지 않도록 서버 설정 (예: `-R`을 통해 녹음이 구성된 경우)
- `-s` 또는 `--server` 서버 모드에서 시작
- `--serverbindip` 바인딩할 IP 주소를 지정합니다
- `-T` 또는 `--multithreading` 티스레딩을 사용하여 더 많은 클라이언트를 지원하기 위해 멀티 코어 CPU를 더 잘 사용합니다
- `-u` 또는 `--numchannels` 최대 채널 수 (클라이언트)
- `-w` 또는 `--welcomemessage` 연결 시 환영 메시지입니다. 문자열 또는 파일 이름으로 제공될 수 있으며 HTML을 포함할 수 있습니다.
- `-z` 또는 `--startminimized` 최소화된 시작
- `--serverpublicip` 동일한 NAT 뒤에 있는 디렉터리에 연결하는 경우 서버의 공용 IP 주소입니다. [디렉터리에 대한 참고 사항](Directories#points-to-note-about-directories)을 참조하십시오