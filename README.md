(A)Lehotay Bálint-(B)Farkas Gergő / Git dolgozat dokumentáció

A_balint: git init
A_balint: git remote add origin (url)
A_balint: git add .
A: git commit -m "A1"
A: git push origin master
B: git init
B: git remote add origin (url)
B: git fetch
B: git pull origin master 
B: git add .
B: git commit -m "B2"
B: git push origin master
A: git fetch 
A: git pull origin master 
A: git branch fejlesztes 
A: git checkout fejlesztes 
A: git add . 
A: git commit -m "A3" 
A: git push origin fejlesztes 
B: git fetch 
B: git pull origin master 
B: git add . 
B: git commit -m "B4" 
B: git push origin master 
B: git fetch 
B: git pull origin fejlesztes 
B: git add .
B: git commit -m "konflikt"
B: git checkout fejlesztes 
B: git add . 
B: git commit -m "B5" 
B: git push origin fejlesztes 
A: git fetch 
A: git pull origin master 
A: git checkout master 
A: git fetch 
A: git add . 
A: git commit -m "A6" 
A: git push origin master 
B: git fetch 
B: git pull origin master 
B: git add. 
B: git commit -m "B7" 
B: git push origin master 
B: git checkout fejlesztes 
B: git merge master 
A: git add .
A: git commit -m "A8" 
A: git push origin master
A végén annyira össze bonyolodott minden hogy fogalmunk sincs hogy hogyan jött létre a zöld ág,
és nem engedte össze merge-ölni az ágakat:
error: Merging is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
