# rinux-basic

| 명령어                  | 설명                 |
| -------------------- | ------------------ |
| `pwd`                | 현재 디렉토리 경로 확인      |
| `ls`, `ls -al`       | 디렉토리 내용 및 숨김 파일 보기 |
| `cd`, `cd ~`, `cd -` | 디렉토리 이동            |
| `mkdir`, `touch`     | 디렉토리 및 파일 생성       |
| `rm`, `rm -r`        | 파일 및 디렉토리 삭제       |
| `cp`, `mv`           | 파일 복사 및 이동         |
| `cat`                | 파일 내용 보기           |


# 디렉토리 탐색
- pwd
- cd /etc
- cd /var/log
- cd -

# 파일 및 폴더 생성/삭제
- **mkdir** testdir
- **cd** testdir
- **touch** test.txt   
- **echo** "Hello Linux!" > hello.txt
- **cat** hello.txt
- **cd** ..
- **rm** -r testdir

### cat,echo touch는 파일 내용을 다루는 기본 내용으로 자주 사용될듯    

# 파일 복사/이동/이름 변경
- **mkdir** folder1 folder2
- **touch** folder1/file.txt
- **cp** folder1/file.txt folder2/
- **mv** folder2/file.txt folder2/file_renamed.txt
