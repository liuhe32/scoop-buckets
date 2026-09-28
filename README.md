\## first



echo "# scoop-buckets" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M main

git remote add origin https://github.com/liuhe32/scoop-buckets.git

git push -u origin main



\## second

git remote add origin https://github.com/liuhe32/scoop-buckets.git

git branch -M main

git push -u origin main





\##

scoop bucket add mybucket https://github.com/liuhe32/scoop-buckets

scoop install mybucket/jdk6

