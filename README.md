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

## git checkout -- <file>

> blow away all changes in this file since last commit

## git commit -a -m "Modify readme"

> To stage+commit same time, does not include new files [un-tracked]
 
## git reset --soft HEAD^

> reset into staging (rollback last commit)

## git commit --amend -m "message"

> this commit will merge with last commit and overwrite commit message




