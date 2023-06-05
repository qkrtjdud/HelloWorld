# Git 명령어

## Git 로컬 컴퓨터에 사용자 등록하기

- git init
- git config --global user.name "qkrtjdud"
- git config --global user.email "qkrtjdudcjst@naver.com"

## Git 시작하기

- git init
- git add .
- git commit -m "최초 커밋"

## Github 업로드하기

- git remote add origin 주소
- git push origin master

## 다시 업로드 법

- 소스 코드 변경
- git add .
- git commit -m "변경내용 적고"
- git push origin master

## 잘 안될때 해결법

- git remote -v
- git remote rm origin

## GitHub 소스코드 다운로드 하는법

- git clone 주소
