mkdir 504
cd 504
git init
echo "# 504" >> README.md
git add README.md
git commit -m "First commit"
git branch -M main
git remote add origin https://github.com/ma-kd/504.git
git push -u origin main
git remote add origin https://github.com/ma-kd/504.git
git branch -M main
git push -u origin main
echo "Dies ist ein Test" > git-test.txt
git status
git add git-test.txt
git commit -m "Füge git-test.txt hinzu"
git status

