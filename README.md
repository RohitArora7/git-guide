# git-guide

It is used to initilise git project
```bash
git init
```




vim

cat index.html

ls -a
show full list view
ls -l

git init

 cd .git/






rohit@DESKTOP-SFVUJIL:~/my-project/.git$ ls
HEAD  branches  config  description  hooks  info  objects  refs



rohit@DESKTOP-SFVUJIL:~/my-project$ ls
index.html

rohit@DESKTOP-SFVUJIL:~/my-project$ git status
On branch master
No commits yet


rohit@DESKTOP-SFVUJIL:~/my-project$ git add index.html


rohit@DESKTOP-SFVUJIL:~/my-project$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.html



rohit@DESKTOP-SFVUJIL:~/my-project$ git commit


git config --global user.email "arora.rohit627@gmail.com"

 git config --global user.name "Rohit Arora"

git config --global user.name "Rohit Arora"


git commit -m "first commit"

git log


we have added git hub 
git remote add origin https://github.com/RohitArora7/my-project.git


rohit@DESKTOP-SFVUJIL:~/my-project$ cat .git/config
[core]
        repositoryformatversion = 0
        filemode = true
        bare = false
        logallrefupdates = true
[remote "origin"]
        url = https://github.com/RohitArora7/my-project.git
        fetch = +refs/heads/*:refs/remotes/origin/*
rohit@DESKTOP-SFVUJIL:~/my-project$ git status
On branch master
nothing to commit, working tree clean


git push -u origin master

rohit@DESKTOP-SFVUJIL:~/my-project$ git push



git clone https://github.com/RohitArora7/my-project-2.git










rohit@DESKTOP-SFVUJIL:~/my-project-2$ git branch
* master


rohit@DESKTOP-SFVUJIL:~/my-project-2$ git checkout -b new-branch
Switched to a new branch 'new-branch'
rohit@DESKTOP-SFVUJIL:~/my-project-2$ git branch
  master
* new-branch


 git checkout master


 git merge new-branch

rm -rf my-project-2/

ssh-keygen

git diff

cat ~/.ssh/id_rsa.pub






 git clone https://github.com/RohitArora7/my-project.git




git clone git@github.com:RohitArora7/runsh.git

mv run.sh runsh

git status

git add run.sh

git commmit -m "first added"

git push

git pull








git log  // will show you all the commits 

git diff

git checkout // you can jump to nay commit 

git checkout master // brings you to latest




child 


git checkout -b newbranch // create new bacha 
git push origin newbranch // push in new bacha 




git branch


 _________________________________________________________________
 
 git clone git@github.com:wavelabsai/ueransim.git 

//create another branch 
git checkout -b ansible-update 

//copy from vm
scp 'ansible@192.168.122.245:/home/ansible/UERANSIM/*' .

//latest commits
git log

// show tracking
git status

//git add
git add .

//commit
git commit

//git push
git push origin ansible-update




_________________________________________________________________


git status

git add .

git commit -m "first commit"

cd /mnt/c/xampp/htdocs/outt

git config --global user.email "arora.rohit627@gmail.com"

git config --global user.name "Rohit Arora"

git remote add origin git@github.com:RohitArora7/Website.git

git push --set-upstream origin master

__________________________________________________________
