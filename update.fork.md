git remote add fork git@github.com:cncamp/101.git
git remote -v

git fetch fork

git checkout master

git merge fork/master
git push origin master
