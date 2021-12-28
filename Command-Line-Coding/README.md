# A) If You Have Windows, Open Ubuntu Terminal (Windows Subsystem for Linux).
<p align="left">
  <img width="1129" height="427" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/49af07c44672afa11bd31326f2e96a1ace27d06d/docs/images/WSL.png">
</p>

# B) The Directory Structure
<p align="left">
  <img width="1145" height="558" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/706a9cf895ee107535d5f042b12bf9e113a73c9d/docs/images/directory1.png">
</p>

# C) Once you open the terminal, you will see a $ prompt, waiting for you to start entering commands.

```bash
$ 
```
&nbsp;  
# D) pwd (print working directory)
```bash
$ pwd
```
&nbsp;  
## This prints out the current directoy you are in. Something like this.
```bash
$ /home/jtk622
```
&nbsp; 

# E) touch (create a file with touch command)
```bash
$ touch
```
&nbsp; 

## This will create a file named "file1.txt".

```bash
$ touch file1.txt
```
&nbsp; 

## You can also edit the file you just created "file1.txt" with a text editor called nano.

```bash
$ nano file1.txt
```
&nbsp; 

## The cp command can be used to copy the file you just created.

```bash
$ cp file1.txt copyfile1.txt
```
&nbsp; 

# F) mkdir (make a new folder or directory)
```bash
$ mdkir
```
&nbsp;  
## This will make a subfolder named "folder1" in your home directory.
```bash
$ mkdir folder1
```
&nbsp;  

# G) ls (list) 
## The ls command lists the contents of your current working directory.
```bash
$ ls
```
&nbsp;  
## Something like this will appear.
```bash
$ ls
folder1 file1.txt copyfile1.txt
```
&nbsp; 
<p align="left">
  <img width="1145" height="558" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/de1a912f5af87ba8b47a2a60e5ea311a11b300e0/docs/images/directory2.png">
</p>

# H) cd (change directory)
```bash
$ cd
```
&nbsp;  
## This command will change the current working directory to folder1.
```bash
$ cd folder1
```
&nbsp;  

## This prints out the current directory you just changed to. Something like this.
```bash
$ pwd
/home/jtk622/folder1
```
&nbsp; 

## This command will move back one directory up the hierarchy (back to your home directory). 
```bash
$ cd ..
```
&nbsp; 

## Now you are back to your home directory. 
```bash
$ pwd
/home/jtk622
```
&nbsp; 

## You can move to the "Windows OS" with cd command.
```bash
$ cd /mnt/c/Users/yourname
```
&nbsp;  

## You can practice the rest of command line codes listed in the cheatsheet.  
<p align="left">
  <img width="2000" height="2588" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/4bb35756df4b9dae985c27c1d976b7aa72c0c00c/docs/images/command-line.png">
</p>
