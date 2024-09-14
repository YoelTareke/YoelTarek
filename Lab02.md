## Lab 02

- Name:Yoel Tareke
- Email:tareke.2@wright.edu

## Part 1 Answers

1. Command & steps to create an SSH key pair:ssh-keygen
2. Steps to add public key to GitHub profile:git add
3. git command to clone repository: git clone git@github.com:WSU-kduncan/ceg2350f24-YoelTareke.git

## Part 2 Answers

The answers for this section are to help you record what steps  
are needed to create a file locally (in your cloned repo)  
and push them (sync) with GitHub.  Only `git` commands are 
valid answers

1. git command to view the status of the repository:git status
2. git command example to add a file for tracking:git add lab02.md
3. git command to commit changes:git commit
4. git command to sync local commits with GitHub:git push
5. git command to sync commits on GitHub to `clone`d repository:git pull

## Part 3 Answers

1. `chmod u+r bubbles.txt`
    - Means: User is able to write into 'bubble.txt'.
2. `chmod u=rw,g-w,o-x banana.cabana`
    - Means: user can read and write, group can only write, others can only execute into 'banana.cabana'.
3. `chmod a=w snow.md`
    - Means: all can write into 'snow.md'
4. `chmod 751 program`
    - Means: User can write,read and execute in program, group are able to only read and execute, and Others can only execute.
5. `chmod -R ug+w share`
    - Means: User and group can  and write in share.

## Part 4 Answers

1. Command to create new user: sudo adduser bob
2. Path to user's home directory:/home/bob
3. Evaluate if `ubuntu` can add files to user's home directory:No
4. Command to switch to user:su bob
5. Command(s) to go to user's home directory:cd ~bob
6. Evaluate if user can add files to user's home directory:
7. Command to switch to `ubuntu`: sudo - 'ubuntu'
8. Command to return to `ubuntu` home directory: cd ~

## Part 5 Answers

For each, write the command used or answer the question posed.

1. Command to create group named `crew`: sudo groupadd 'crew'
2. Command(s) to add `ubuntu` & user to group `crew`: sudo usermod -a -G crew ubuntu
3. Command to modify `share` to have group ownership of `crew`:sudo chgrp crew share
4. Command to switch to user:cd su ytareke
5. Command to add file to `share`:touch /home/user/share/bob.txt
6. Evaluate why these steps allowed the above action: Having the right permissions and using the correct commands allows you create a file in 'share'.

## Part 6 Answers

For each, write the command used or answer the question posed.

1. Command to create file using `sudo`:sudo touch /path/to/file.txt
2. Evaluate (in plain text) the permission of the file: read and execute
3. Provide a method to edit the file without modifying permissions: vim /path/to/file.txt
4. Command(s) to modify permissions:chmod
