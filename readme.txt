111111
222222
333333
444444
test


apt-get install git
apt-get install git-doc git-svn git-email git-gui gitk

git config --global user.name "gitjjw"
git config --global user.email "jjwsenior@sina.com"

mkdir githome
git init

git add readme.txt
git commit -m "add readme.txt"
git status
git log

ssh-keygen -T rsa -C "jjwsenior@sina.com"
/root/.ssh/id_rsa.pub

ssh -T git@github.com
git remote add origin git@github.com:gitjjw/jjwtest.git 
git pull --rebase origin master
git push -u origin master
git clone git@github.com:gitjjw/jjwtest.git




