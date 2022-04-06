Task 1:
$mkdir “Directory_Name” 
$cd “Directory_Name”
$touch feature 1.txt and $touch feature2.txt
$ls => to verify 
Task 2: 
$git branch develop
$git branch feature1
$git branch feature2
$git status => to verify

Task 3: 
$git checkout develop
$touch develop.txt
$git status (to verify)

Task 4: 
$git stash -u 
$git checkout feature1
$git status (to verify)
Task 5: 
$touch new.txt
$ls (to verify)
$git add . 
$git commit -m “Commit_name”
$git status (to verify)
Task 6: 
$git checkout develop
$git stash pop
$git commit -m “Commit_Name”
$git status (to verify)
