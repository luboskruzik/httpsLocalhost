# httpsLocalhost

Create a new repository on the command line
echo "# httpsLocalhost" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin git@github.com:luboskruzik/httpsLocalhost.git
git push -u origin master

Push an existing repository from the command line
git remote add origin git@github.com:luboskruzik/httpsLocalhost.git
git branch -M master
git push -u origin master