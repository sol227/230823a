## 230823 ## 
1. 로컬 저장소 생성 
`code($ git init)`
2. README.md 파일 생성
$ touch README.md
$ git add README.md or git add .
$ git commit -m "README.md 파일 생성"

3. 온라인 저장소 생성
$ git remote add origin https://github.com/sol227/230823a.git
$ git push -u origin main

4. README.md 파일 온라인 저장소에 업로드
$ git commit -am "README.md 파일 수정"