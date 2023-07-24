# github_test

git toole

terminal
gitdasktop
sourcetree
gitkraken

git commend

git --version
git config --list
git config --global -e


#편집툴 연결
git config --global core.editor "code"
git config --global core.editor "code --wait"
git config --global -e

#사용자 설정, 이메일 설정
git config --global user.name "kbkim"
git config --global user.email "kbkim@bbtree.co.kr"

git config user.name
git config user.email

#윈도우 사용자 : true, 맥사용자 : input 
# text \r\n line feed carriage-return <- 윈도우
# text \n line feed <- 맥
git config --global core.autocrlf true

#깃 생성
git init

#깃 상태
git status

#깃 명령어 단추하기 
git config --global alias.st status
git st

git config --h

#git use to track
git add
git add .
git add a.txt
git add *.txt

#use to unstage
git rm --cached <file>...

git rm --cached a.txt

git status -s

#변경내용 확인
git diff
git diff -h
git diff --staged
git diff --cached

#git commit
git commit
git commit -m "meg"
git commit -am "add meg"

git log
git log --all
git log --all --oneline

#시간여행 
git checkout 12321456
git checkout master

#리모트서버 확인
git remote -v 
#리모트서버 삭제
git remote remove origin 
#리모트서버 추가
git remote add origin https://github.com/bbtree-dev/bbtree_homepage.git

#리모트서버 확인
PS D:\www\project\bbtree_homepage> git remote -v 

#리모트서버 github main이 마스터여서 master 변경
git push -u origin master

#로그인 안될때 access tokens 로그인 하기
https://wotres.tistory.com/entry/Github-%EC%97%90%EB%9F%AC-%ED%95%B4%EA%B2%B0%EB%B2%95-Authentication-failed-for-use-a-personal-access-token-instead

#git pull 가 안먹을때
https://www.todaymart.com/812

$git branch --set-upstream-to=origin/master master
