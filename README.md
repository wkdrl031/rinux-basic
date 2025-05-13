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
- **mkdir** testdir&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# testdir 디렉토리 생성
- **cd** testdir
- **touch** test.txt&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# test.txt라는 빈 파일 생성
- **echo** "Hello Linux!" > hello.txt&nbsp;&nbsp;# 내용 있는 파일 만들기
- **cat** hello.txt&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 파일 내용 보기
- **cd** ..                              
- **rm** -r testdir&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 디렉토리와 내부 파일 삭제

### cat,echo touch는 파일 내용을 다루는 기본 내용으로 자주 사용될듯    

# 파일 복사/이동/이름 변경
- **mkdir** folder1 folder2
- **touch** folder1/file.txt
- **cp** folder1/file.txt folder2/&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 파일 복사
- **mv** folder2/file.txt folder2/file_renamed.txt&nbsp;&nbsp;&nbsp;# 파일 이름 변경 (이동)
