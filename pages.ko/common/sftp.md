# sftp

> 안전한 파일 전송 프로그램.
> SSH를 통해 호스트 간 파일을 복사하는 대화형 프로그램.
> 비대화형 파일 전송은 `scp` 또는 `rsync`를 참조하세요.
> 더 많은 정보: <https://manned.org/sftp>.

- 원격 서버에 연결하고 대화형 명령 모드로 진입:

`sftp {{원격_사용자}}@{{원격_호스트}}`

- 다른 포트를 사용하여 연결:

`sftp -P {{원격_포트}} {{원격_사용자}}@{{원격_호스트}}`

- 사전 정의된 호스트를 사용하여 연결 (`~/.ssh/config`에 설정된 경우):

`sftp {{호스트}}`

- 원격 파일을 로컬 시스템으로 전송:

`get {{/경로/원격_파일}}`

- 로컬 파일을 원격 시스템으로 전송:

`put {{/경로/로컬_파일}}`

- 원격 디렉토리를 로컬 시스템으로 재귀적으로 전송 (`put`에도 적용 가능):

`get -R {{/경로/원격_디렉토리}}`

- 로컬 컴퓨터의 파일 목록 보기:

`lls`

- 원격 컴퓨터의 파일 목록 보기:

`ls`