mkdir -p ~/.config/mc

cd ~/.config/mc

git init

git remote add origin git@github.com:aftaa/mc-hotlist.git

git pull origin master

git branch --set-upstream-to=origin/master master
