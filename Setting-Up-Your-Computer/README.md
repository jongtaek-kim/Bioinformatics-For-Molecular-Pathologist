## Setting Up Your Computer For NGS Tutorial

#### A) Install "Ubuntu: Windows Subsystem for Linux" on Windows Desktop (Skip for MAC users) from [here.](https://www.microsoft.com/en-us/p/ubuntu/9nblggh4msv6?activetab=pivot:overviewtab)
#### Windows Subsystem for Linux (WSL) allows you to run a real Linux environement on windows, open the command line and start working on the file system like you are on Linux. 
#### You will be able to run NGS and other linux programs.
<p align="left">
  <img width="868" height="441" src="https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/blob/33615de48a130b0df82cd93b9bd1fbf628f1e8ba/docs/images/wsl2-logo.png">
</p>

#### B) If you have Mac OS, download the Miniconda installer for Mac [(here)](https://docs.conda.io/en/latest/miniconda.html). Instructions are [(here)](https://conda.io/projects/conda/en/latest/user-guide/install/macos.html). Be sure to download the Python 3.7 version! After downloading, run the following in your terminal:
```bash
$ bash Miniconda3-latest-MacOSX-x86_64.sh
```
&nbsp;  
#### Or you can also directly fetch it in your terminal.
```bash
$ curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-MacOSX-x86_64.sh
```
&nbsp;  

#### C) If you have Linux OS (Ubuntu or Debian) or Windows Subsystem for Linux (WSL), download the Miniconda installer for Linux [(here)](https://docs.conda.io/en/latest/miniconda.html). Instructions are [(here)](https://conda.io/projects/conda/en/latest/user-guide/install/linux.html#install-linux-silent). Be sure to download the Python 3.7 version! After downloading, run the following in your terminal:
```bash
$ bash Miniconda3-latest-Linux-x86_64.sh
```
&nbsp;  
#### Or you can also directly fetch it in your terminal.
```bash
$ curl -O https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
```
&nbsp;  

#### D) Set up channels- It is important to add them in this order so that the priority is set correctly (that is, conda-forge is highest priority).
```bash
conda config --add channels defaults
conda config --add channels bioconda
conda config --add channels conda-forge
```
&nbsp; 

#### E) Install Packages Needed for NGS Tutorial.
```bash
conda install fastqc
conda install trimmomatic
conda install bwa
conda install samtools
conda install gatk
```
&nbsp; 

#### F) Practice Command Line Tutorials [Here.](https://github.com/jongtaek-kim/Bioinformatics-For-Molecular-Pathologist/tree/main/Command-Line-Coding)
