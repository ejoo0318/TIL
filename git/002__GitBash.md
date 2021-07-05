# Git Bash 명령어

1. cd

>- cd[폴더이름] : 해당 디렉토리(폴더)로 이동
>- cd ..  : 상위폴더로 이동
>- cd : home(~)로 이동

2. pwd : 현재 위치 알려줌
3. mkdir[폴더이름] : 새로운 폴더 생성
4. touch[파일이름] : 새로운 파일 생성
5. ls

> - ls : 모든 폴더 목록 보여줌
> - ls-al : 폴더를 세부적으로 보여줌

6. cp [파일이름1] [파일이름2] : 파일1과 같은 파일을 파일2의 이름으로 복사
7. mv

> - mv a.txt B/a.txt : a.txt파일을 B폴더 안으로 이동
> - mv a.txt c.txt : a.txt파일의 이름을 c.txt로 변경

8. git init : git 저장소 생성 -> (marster) 브랜치가 생성됨
9. git status : 로컬 저장소의 현재 상태를 보여줌
10. add

> - work space에서 git index로 추가하는 명령어
> - git add [파일이름] : 파일을 추가
> - git add . : 파일 내 모든 파일을 추가

11. git commit -m '메세지작성' : 추가한것에 대한 간단한 메세지를 작성
12. git log :  로컬 저장소의 commit이력을 조회

> - git log : 로컬 저장소의 commit이력을 상세조회
> - git log --onw line : 타이틀 메세지만 commit 이력 조회
> - git log --oneline --graph : 그래프로 commit 이력 조회

13. git diff :  변경된 이력을 조회
14. git config --global --list: 현재 git 프로그램에 설정된 값들을 확인
15. git remote
> -  로컬저장소와 원격저장소를 연결
> -  git remote add origin [자신의 GitHub 원격저장소 주소 -https]    
> -  git remote -v : 연결된 저장소 확인

16. git push

> - git push -u origin master :  원격 저장소로 저장 (올리기, 깃허브로 동기화)
> - -u origin = 별칭 /  master = 브랜치명
> - (-u : --set-upstream) 한 번 성공하면 git push만 해도 같은 origin에 master 브랜치를 전송

17. git pull 

> - 별칭으로부터 브랜치를 로컬 저장소로 저장 (내려받기, 내컴퓨터로 동기화)

18. git clone 

> - git clone [자신의 GitHub 원격저장소 주소 -https] 
> - 원격저장소에 있는 정보(Repository)를 내컴퓨터로 가져옴

