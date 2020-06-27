# How to make and manage .gitignore file

### Types of files in git
1. Tracked => Tracked files are such files that are previously staged or committed.
1. Untracked => Untracked files are such files that are not previously staged or committed.
1. Ignored => Ignored files are such files that are explicitly ignored by git. We have to tell git to ignore such files.

### How to create a .gitignore file to ignore files and directories
1. touch .gitignore
1. vim .gitignore => write inside this file 
    eg. *.txt
        /new_folder/*
1. git add .
1. git commit -m "adding .gitignore file"
1. git push 

**Note :You can make any number of .gitignore fiels and anywhere in the repository**

### Rules for putting the pattern in .gitignore file:
The rules for the patterns that can be put in the .gitignore file are as follows:
* Git ignores the Blank lines or lines starting with #.
* Only the Standard glob patterns work and will be applied recursively throughout the entire working tree.
* The patterns can be started with a forward slash (/) to avoid recursively.
* The patterns can be ended with a forward slash (/) to specify a directory.
* The patterns can be negated by starting it with an exclamation point (!).


### Global .gitignore:
As we know that we can create multiple .gitignore files for a project. But Git also allows us to create a universal .gitignore file that can be used for the whole project. This file is known as a global .gitignore file. To create a global .gitignore, run the below command on terminal:

```$ git config --global core.excludesfile ~/.gitignore_global```  
The above command will create a global .gitignore file for the repository.

### How to List the Ignored Files?
In Git, We can list the ignored files. There are various commands to list the ignored files, but the most common way to list the file is the ls command. To list the ignored file, run the ls command as follows:

```$ git ls-files -i --exclude-standard```  
Or
```$ git ls-files --ignore --exclude-standard```  
The above command will list all available ignored files from the repository. In the given command, -I option stands for ignore and --exclude-standard is specifying the exclude pattern.


















