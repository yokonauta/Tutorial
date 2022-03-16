# Tutorial

git init

1st time
git clone git@github.com:yokonauta/Tutorial.git
cd Tutorial

2nd times
git checkout git@github.com:yokonauta/Tutorial.git

Working...

git status

On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	images/           <-- New
	restaurant0.html  <-- New
	
git add .                 <-- All
git add restaurant0.html  <-- Just one

git commit -m "Some reason"
git push
