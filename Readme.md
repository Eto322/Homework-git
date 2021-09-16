git add .

git commit -m "first part"

git push

git branch second_part

git checkout second_part

git add .

git commit -m "second part"

git push 

git checkout master

git merge --no-ff -m  "merge second part" master

git push