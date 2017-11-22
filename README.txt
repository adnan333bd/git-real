Git commands

git help <any git command>
        -- git help config
git config --global user.name "golam chowdhury"
   git config --global user.email adnan333bd@gmail.com
   git config --global color.ui true

git init

>  creates local repo

git status

>  what is changed after last commit

git add <filename>
 
>   for start tracking on the file, or to add changes to staging

git commit -m "updated README.txt with 5 commands"

> for commiting the changed to local repo

git add --all

> adds all new or modilfiled files

    git add <list of files>
    git add -all
    git add *.txt
    git add docs/*.txt
    git add docs/
    git add '*.txt'

git log

>  to show history

git diff

> show difference unstaged 

git diff --staged

> show staged difference

git reset HEAD <file>
 
> to unstage

git checkout -- <file>

> blow away all changes since last commit

git commit -a -m "Modify readme"

> add and commit same time, not includes added files
 
git reset --soft HEAD^

> reset into staging (undeo last commit)

git commit --amend -m "message"




