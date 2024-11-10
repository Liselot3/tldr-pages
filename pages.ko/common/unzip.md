# unzip

> Zip 아카이브에서 파일/디렉토리를 추출.
> 같이 보기: `zip`.
> 더 많은 정보: <https://manned.org/unzip>.

- 특정 아카이브에서 모든 파일/디렉토리를 현재 디렉토리에 추출:

`unzip {{경로/대상/아카이브1.zip 경로/대상/아카이브2.zip ...}}`

- 아카이브에서 파일/디렉토리를 특정 경로로 추출:

`unzip {{경로/대상/아카이브1.zip 경로/대상/아카이브2.zip ...}} -d {{경로/대상/출력}}`

- 아카이브에서 파일/디렉토리를 추출하고 추출된 파일 이름과 함께 `stdout`으로 출력:

`unzip -c {{경로/대상/아카이브1.zip 경로/대상/아카이브2.zip ...}}`

- 비ASCII 문자(예: 중국어나 일본어 문자)를 포함한 파일 이름이 있는 Windows에서 생성된 아카이브를 추출:

`unzip -O {{gbk}} {{경로/대상/아카이브1.zip 경로/대상/아카이브2.zip ...}}`

- 특정 아카이브의 내용을 추출하지 않고 나열:

`unzip -l {{경로/대상/아카이브.zip}}`

- 아카이브에서 특정 파일 추출:

`unzip -j {{경로/대상/아카이브.zip}} {{경로/대상/아카이브_내_파일1 경로/대상/아카이브_내_파일2 ...}}`