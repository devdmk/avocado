# Github 시작하기

## Setting
1. Git Download

2. Git 저장소 생성

3. Visual Studio Code `설정(ctrl + ,)`에 아래 내용 넣기
```
"terminal.integrated.shell.windows": "C:\\Program Files\\Git\\bin\\bash.exe",
"git.autofetch": true
```

4. VScode 터미널에서 bash로 설정 

4. VScode 파일 - 작업 영역에 폴더 추가

5. 터미널에 `cd d:`로 이동 후 `$ git init`

5. 로컬 저장소를 복제(clone)
`$ git clone /로컬/저장소/경로`

6. 저장소 생성 `$ git init`

7. d: .git 폴더 삭제

---

## Command
 * status (상태) `$ git status`
 * add (파일추가) `$ git add * or $ git add <파일이름>`
 * rm (파일삭제) `$ git rm <파일이름>`
 * commit `$ git commit -m "설명"`
 * push (서버에 올리기) `$ git push or $ git push origin master`
 * remote
```
$ git remote add origin https://github.com/dhmkchs/__defaults.git
$ git remote -v
```