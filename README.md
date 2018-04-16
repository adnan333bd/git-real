### Git commands

## git help <any git command>
        -- git help config
git config --global user.name "golam chowdhury"
   git config --global user.email adnan333bd@gmail.com
   git config --global color.ui true

## git init

>  creates local repo

## git status

>  what is changed after last commit

## git add <filename>
 
>   for start tracking on the file and to add changes to staging

## git commit -m "updated README.txt with 5 commands"

> for committing the changed to `local repo` [staging to repo]

## git add --all

> adds all new or modified files to staging

    git add <list of files>
    git add -all
    git add *.txt
    git add docs/*.txt
    git add docs/
    git add '*.txt'

## git log

>  to show history

## git diff

> changes vs staging

## git diff --staged

> staging vs local repo

## git reset HEAD <file>
 
> to un-stage the file
(the version from time-line Head replaces the staging version)

## git checkout -- filename

> blow away all changes in this file since last commit

## git commit -a -m "Modify readme"

> To stage+commit same time, does not include new files [un-tracked]
 
## git reset --soft HEAD^

> reset into staging (rollback last commit)

## git commit --amend -m "message"

> this commit will merge with last commit and overwrite commit message

## git reset --hard HEAD^

> blow away last commit and all changes

## git reset --hard HEAD^^ 

> blow away last two commits and all changes

## git remote add origin https://aaaadfdfd.git

> adding remote 'origin'

## git remote add \<name> \<address>

> adding new remote

## git remote rm \<name>

> removing remote

## git push -u \<remote-name> \<local-branch-name>

> local branch to remote push [ if -u is used, next time only git push will work ]

## password caching

> https://help.github.com/articles/set-up-git

## git clone url

> local directory and repo and added remote 

## git branch feature2018

> creates a new branch

## git checkout f2018

> switches branch

## git branch

> shows branch list

## git merge f2018

> merges f2018 into current branch, its a fast forward merge if original branch was not modified meantime

## git branch -d f2018

> removing branch f2018

## git checkout -b feat

> created a branch named feat and checked it out

## git pull

> git fetch and then merges the origin/master to master

## git commit -a

> after resolving conflicts manually, to do merge commit





