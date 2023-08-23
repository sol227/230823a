## 230823 ## 
### 사용 방법 ###
1. 로컬 저장소 생성 <br> 
`code($ git init)`

2. README.md 파일 생성 <br>
$ touch README.md
$ git add README.md or git add .
$ git commit -m "README.md 파일 생성"

3. 온라인 저장소 생성 <br>
$ git remote add origin https://github.com/sol227/230823a.git
$ git push -u origin main

4. README.md 파일 온라인 저장소에 업로드 <br>
$ git commit -am "README.md 파일 수정"
$ git push

### github에서 내려 받기 ###
`$ git pull origin main`

1. clone : 로컬에 저장소가 없는 경우. 저장소 자체 복사
2. pull : 로컬에 저장소가 있는 경우. 저장소 안에 있는 파일 내려받기

### 충돌(conflict)시 해결 방법 ###
