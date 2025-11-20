# 깃 리눅스



깃 리눅스 명령어

$ pwd
Print Working Directory
현재 폴더 표시

$ cd
Change Directory

$ mkdir
Make Directory

$ ls
Fire or folder list
-l : 파일의 상세정보
-a : 숨김 파일 표시
-al : 위 두개를 조합


파일 생성

$ touch fname


빈파일 fname 생성

결과 표시
$ echo git bash
$ echo 'print()'

$ cat fname
파일 내용 보이기

$ cp a b
파일 a를 b로 복사

$ mv f1 f2
파일 f1을 f2로 이름 수정

$ rm fname
파일 fname 삭제

$ rm -rf dname
하부에 서브폴더와 파일이 있어도 폴더 삭제, 옵션 사용
-f 강제로 파일이나 디렉토리를 삭제
-r 디렉토리 내부의 모든 내용 삭제

$ git log -- graph 
문자 그림으로 로그 이력 그리기

$ git log -- reverse 
오래된 커밋부터 표시 --graph와 함께 사용할 수 없음

'' --all
모든 브랜치의 로그 확인

'' -n
최근 n개

% git config --global alias.co checkpoint

![wave](https://capsule-render.vercel.app/api?type=wave&color=auto&height=200&text=WAVE)

