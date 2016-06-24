This is a description txt file for githome.
in current directory, there is a sub directory named a001.
git log --pretty=oneline
remote repository

 Create SSH key:
   ssh-keygen -t rsa -C "kangjingwang@qq.com"
   enter
   enter
   enter
 
 Copy public key(~/.ssh/id_rsa.pub) to Github
 
 Create a remote connection
 git remote add origin git@github.com:BossJing/githome.git

 Check connection
 git remote

 Push
 git push -u origin master


