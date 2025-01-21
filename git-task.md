### `Git Task:`

**Step 1:**
  Iam Creating an new repository in Remote repository with the name of BhanuAT1049 (Github)

  ![preview](/images/git.1.PNG)

  and you can see here the repository which i have created

  ![preview](/images/git.2.PNG)

  **Step 2:**
  I need to change my base branch name from main to master

  Go for the respository settings 

  ![preview](/images/git.3.PNG)
  There you can see Default branch option and you can rename your base branch here

  * I'm changing my base branch name master from main
  
  ![preview](/images/git.4.PNG)

  * Here you can see the branch which i renamed

  ![preview](/images/git.5.PNG)

  **Step 3:**

  I'm Cloning my code from remote to local repository

  * to clone the code you need to copy the link of your repository 

  ![preview](/images/git.6.PNG)

  * After Copying open your git bash in your local machine and use `git clone url` command for cloning 

  ![preview](/images/git.7.PNG)

  * Here you can see that my repository BhanuAT1049 (to display the files or folders we need to use `ls` command) 

  ![preview](/images/git.8.PNG)

  * and i'm going to the path of BhanuAT1049 repository by using `cd` command and after that i'm checking whether i have .git folder or not by using `ls -la` command.

  ![preview](/images/git.9.PNG)
  I'm having .git folder

  **Step 4:**

  * I'm creating 5 files by using `touch` command and i'm checking whether the files are created or not by using `ls` command and it's created

  ![preview](/images/git.10.PNG)

  **Step 5:**

* I'm checking my repository  status by using `git status` and it displays we have untracked files in red colour font

![preview](/images/git.11.PNG)

* To track the files we need to use one command and that `git add .`

![preview](/images/git.12.PNG)

* Next i'm checking my status whether the files are tracked or not and it is showing that the files are tracked, we can identify the tracked files by seeing green colour file names 


![preview](/images/git.13.PNG)

* It is showing that changes to be committed
* Before commiting i need to add some data to the files but it is in staging area .
* We can't add the data when the files is in staging area, to add the data we need to come out from staging area that is to working directory
* To come back to the Working directory from staging area we can use `git restore --staged file name ` 
* After using `git restore` we can see whether the files are untracked or not

![preview](/images/git.14.PNG)
* The files are untracked 
* Again i'm tracking my files and checking my status

![preview](/images/git.15.PNG)

*Again i'm commitimg my files

![preview](/images/git.16.PNG)

* I'm Pushing my files to remote repository (Github) by using `git push`

![preview](/images/git.17.PNG)

* My files are moved to remote repository

![preview](/images/git.18.PNG)

* I'm Checking my commit Id's and messages which i gave while commiting by using `git log`

![preview](/images/git.19.PNG)

* Next , I'm adding some data to file by using `cat` command

![preview](/images/git.20.PNG)

* I'm Checking my status

![preview](/images/git.21.PNG)

* Next , I'm Commiting and adding the files in single command that is `git commit -am "msg"`


![preview](/images/git.22.PNG)

* I'm chaging my message by using `amend` command

![preview](/images/git.23.PNG)

* Then i push my files to remote repository

![preview](/images/git.24.PNG)

* This is the data that i added to the file

![preview](/images/git.25.PNG)

**Step 6:**

* I'm checking how many branches that i have by using `git branch` command

![preview](/images/git.26.PNG)

* I have only master so that i'm creating new branch by using `git branch branch_name`

![preview](/images/git.27.PNG)

* I need to switch the branch which i have created . we can switch to the branch by using `git switch branch_name`

![preview](/images/git.28.PNG)

* In new branch i'm creating files 

![preview](/images/git.29.PNG)

* I'm adding my files 

![preview](/images/git.30.PNG)

* I'm commiting and pushing my files to the remote repo

![preview](/images/git.31.PNG)

* In branch is created in remote also after pushing

![preview](/images/git.32.PNG)

* I'm Checking my commit Id's and messages which i gave while commiting by using `git log`

![preview](/images/git.33.PNG)

*I'm switching to master branch to merge the files and i'm merging the files

![preview](/images/git.34.PNG)

* If i check my git logs , the git logs are also merged to master branch

![preview](/images/git.35.PNG)

* I'm marking this by using `git tag -a annotation -m "msg" `
* We can see that by using `git tag `

![preview](/images/git.36.PNG)

*I'm pushing all these changes to remote repo

![preview](/images/git.37.PNG)

* Here you can see the tag which i have marked

![preview](/images/git.38.PNG)

* If i click on tag then the output will be display like this 

![preview](/images/git.39.PNG)



































