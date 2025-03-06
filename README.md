....or create a new repository on the command line 
echo "#fisenkovika">> README.md
git init 
git add README.md
GIT commit -m "first commit"
git branch -M main
git remote add oririgin https://github.com/fisenkovika/fisenkovika.git
git push -u origin main
