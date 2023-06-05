# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git config --global user.name "unjoo31"
- git config --global user.email "unjoo31@gmail.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin https://github.com/unjoo31/HelloWorld.git
- git push origin master

## 다시 업로드 하는 법

- 소스코드 변경
- git add .
- git commit -m "변경내용적고"
- git push origin master
