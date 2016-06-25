Firstly, you need to do is to register a github.com account.

then, access to github.com via browser. create a new repository.

In your local PC, install git tool which usually use to clone from
a repository or push local file up to a repository exists in
github.com.
you can download from url:http://msysgit.github.io/

Config user_name and user.email
 git config --global user.name "Your Name"
 git config --global user.email "you@email.com"

Create SSH key:
   ssh-keygen -t rsa -C "kangjingwang@qq.com"
   enter
   enter
   enter
 
Copy public key(~/.ssh/id_rsa.pub) to Github

Init a local repository
 git init

New a file
 vi new_test.txt

Add a file to stage
 git add new_test.txt

Commit a file
 git commit -m "a description for this very commit"

Create a remote connection to github.com
 git remote add origin git@github.com:BossJing/githome.git

Check connection
 git remote

Push file to a repository in github.com
 git push -u origin master

Warning: Permanently added the RSA host key for IP address '192.30.252.131' to the list of known hosts.
Branch master set up to track remote branch master from origin.
Everything up-to-date

C:\Users\kangj>ping -a -4 192.30.252.131

Pinging github.com [192.30.252.131] with 32 bytes of data:
Reply from 192.30.252.131: bytes=32 time=204ms TTL=51
Reply from 192.30.252.131: bytes=32 time=205ms TTL=51
Reply from 192.30.252.131: bytes=32 time=205ms TTL=51
Reply from 192.30.252.131: bytes=32 time=206ms TTL=51

Ping statistics for 192.30.252.131:
    Packets: Sent = 4, Received = 4, Lost = 0 (0% loss),
Approximate round trip times in milli-seconds:
    Minimum = 204ms, Maximum = 206ms, Average = 205ms


