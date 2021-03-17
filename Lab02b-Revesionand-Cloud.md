Revesions and Cloud 

 

From the previous articles, I learn that the version control is a system that allows you to revisit various versions of the files by recording the changes,and there are three type of such system , like :  VCS, CVCS , DVCS . Git is a DVCS , it stores data in a file system made up of snapshots , eliminating the need to fetch history  from the server because it's found in the local disk and detect file corruption or loss of information in transit. Files in the Git can reside in three states: committed, modified and staged.

Also, I learn the methods how i can downloed the Git which is depend on the current operating system and how to perform some customization steps , like : configuration of variables and identity setting . In addition , I get some commands in order to set default text editor,check the overall settings and setting up a Git repository about importing and cloning , such as : 

$ git init ...... ( for intialize )

$ git clone https://github.com/test  ........ ( Here ,I want to mention that Git will automatically give the name “origin” to the server from which you cloned and the name “master” to your local branch )

Finally , I learn the components of local repository structure .Also , I know the fact of the files in a checked out copy of project file may be either in tracked or untracked state , so there are commands to check file status , tracking staging a new file , committing all changes , pushing changes to a remote repository and stashing changes if you aren't ready to commit changes but you need them for next time .