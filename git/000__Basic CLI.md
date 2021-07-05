# 00. Basic CLI

- `ls`: 목록 조회 (list)

  ```bash
  a.txt  b/  c.txt  d.txt  e.txt
  ```

  - `ls -al`: 상세 목록 조회

- `cd`: 폴더 변경 (change directory)
  - `cd`: `~` 폴더(Home 폴더)로 이동
  - `cd 폴더명`:`폴더명`으로 이동
    - `cd 폴더명/폴더명/폴더명`: 여러개의 폴더 한번에 이동
  - `cd ..`: 상위 폴더로 이동
- `mkdir`: 폴더 생성 (make directory)
  - `mkdir A`: `A`라는 이름의 폴더 생성
- `touch`: 빈 파일 생성
  - `touch a.txt`: `a.txt` 파일 생성 (빈 파일)
- `cp`: 파일/폴더 복사
  - `cp A B`: `A` 라는 파일/폴더를 복사하여 `B`를 생성
- `mv`: 파일/폴더 이동
  - `mv A.txt B/A.txt`: `A.txt` 파일을 `B` 폴더 안으로 이동
  - `mv A.txt C.txt`: `A.txt` 파일의 이름을 `C.txt`로 변경
- Tab: 자동완성
- 방향키 위, 아래: 명령어 기록 (History)