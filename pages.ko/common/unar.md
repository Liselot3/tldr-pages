# unar

> 아카이브 파일의 내용을 추출.
> 더 많은 정보: <https://manned.org/unar>.

- 아카이브를 현재 디렉토리에 추출:

`unar {{경로/대상/아카이브}}`

- 아카이브를 지정된 디렉토리에 추출:

`unar -o {{경로/대상/폴더}} {{경로/대상/아카이브}}`

- 압축 해제할 파일이 이미 존재할 경우 강제로 덮어쓰기:

`unar -f {{경로/대상/아카이브}}`

- 압축 해제할 파일이 이미 존재할 경우 강제로 이름 변경:

`unar -r {{경로/대상/아카이브}}`

- 압축 해제할 파일이 이미 존재할 경우 강제로 건너뛰기:

`unar -s {{경로/대상/아카이브}}`