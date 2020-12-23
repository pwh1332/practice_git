# practive_git
DSLAB 1주차_깃헙
git에 파일 저장하고 가져오고 commit하기


-----------------------------file----------------------------
git init
git remote add origin {git@github.com:pwh1332/practive_git.git}
git config --global user.email bluecuc4@gmail.com
git config --global user.name pwh1332

git add{n.file}
git add. #all
git commit -m"commit"
git push {} >>#커밋 파일을 git.hub에 실제로 등록

git fetch #git hub에서 local repository로 가져오기
git merge #컴퓨터와 깃의 repository 동일화 // branch에서 master branch로 병합
git pull #깃->컴 (동시에)
git push #컴->깃

git add #"스냅샷"에 새 파일 저장
git commit #변경후 저장소의 "스냅샷" 찍기 
git branch cats #가지치기 : 다른이름으로 저장하기 느낌

참조 : https://nolboo.kim/blog/2013/10/06/github-for-beginner/
