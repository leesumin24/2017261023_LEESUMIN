> 2017261023_LEESUMIN

# git 명령어

### 전역 사용자명/이메일 구성하기
> git config - -global user.name “Your name”

> git config - -global user.email “Your email address”

### 저장소별 사용자명/이메일 구성하기 (해당 저장소 디렉터리로 이동 후)
> git config user.name “Your name”

> git config user.email “Your email address”

### 전역 설정 정보 조회
> git config - -global - -list

### 저장소별 설정 정보 조회
> git config - -list

### Git의 출력결과 색상 활성화하기
> git config - -global color.ui “auto”

### 새로운 저장소 초기화하기
> mkdir /path/newDir
> cd /path/newDir
> git init

### 저장소 복제하기
> git clone <저장소 url>

### 새로운 원격 저장소 추가하기
> git remote add <원격 저장소> <저장소 url>

**아래 명령어에서 [ ]는 선택적인 매개변수를 의미함**

### 새로운 파일을 추가하거나 존재하는 파일 스테이징하고 커밋하기
> git add <파일>
> git commit -m “<메시지>”

### 파일의 일부를 스테이징하기
> git add -p [<파일> [<파일> [기타 파일들…]]]



# markdown 문법
