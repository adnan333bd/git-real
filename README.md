### Git commands

## git help <any git command>
   git help config
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
(the version from time-line Head replaces the staging version, but the file changes are there in local file system)

## git checkout -- filename
> blow away all changes in this file since last commit

## git commit -a -m "Modify readme"
> To stage+commit same time, does not include new files [un-tracked]
 
## git reset --soft HEAD^
> reset into staging (rollback last commit, HEAD^ is the previous state of HEAD)

## git commit --amend -m "message"
> this commit will merge with last commit and overwrite commit message

## git reset --hard HEAD^
> blow away last commit and all changes

## git reset --hard HEAD^^ 
> blow away last two commits and all changes

## git remote add origin https://aaaadfdfd.git
> adding remote named 'origin'. this adds the mapping {origin:address} to local repo

## git remote add \<name> \<address>
> adding new remote

## git remote rm \<name>
> removing remote

## git push -u <remote-name> <local-branch-name>
> 'local branch' to 'remote push' [ if -u is used, next time only git push will work ]

## password caching during push
> https://help.github.com/articles/set-up-git

## git clone url [local-name]
> 1) creates local directory and repo 
  2) adds the 'origin' remote pointing it to clone URL
  3) checks out initial branch (likely master) and sets the head

## git remote -v
> lists all remotes

## git branch feature2018
> creates a new branch

## git branch
> shows branch list and current branch with a *

## git checkout f2018
> switches branch

## ls
> list files in this branch

## git merge f2018
> merges f2018 into current branch, its a 'fast forward' merge if original branch was not modified meantime

## git branch -d f2018
> removing branch f2018 (when you are done it by merging it to master)

## git checkout -b feat
> created a branch named feat and checked it out

## git pull
> 'git fetch' and then merges the origin/master to master
   1) git fetch
   2) git merge origin/master

## git commit -a
> after resolving conflicts manually, to do 'merge commit'

## git push origin shopping_cart
> newly created shoppping_cart branch is pushed to remote, 'origin' , so that others can work on it

## git branch -r
> list all remote branches

## git checkout shopping_cart
> Branch shopping_cart set up to track remote branch shopping_cart from origin. Switched to a new branch 'shopping_cart' (another developer does this.) 

##  git branch --set-upstream-to=origin/admin admin
> branch 'admin' set up to track remote branch 'admin' from 'origin' (means local 'admin' merges with remote 'admin')

## git branch -m <oldname> <newname>
> how to rename a local branch

## git push origin :shopping_cart
> deletes remote branch shopping_cart, but keeps the local intact

## git branch -d shopping_cart
> deletes local branch shopping_cart if changes are merged to some other branch, if not, it shows warning

## git branch -D shopping_cart
> then deletes the local branch, even if there are unmerged changes in this branch









