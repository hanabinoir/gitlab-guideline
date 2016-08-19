# Git and GitLab Guideline  
## Table of Contents
1. [Required Tools](#required-tools)  
2. [Installation](#installation)  
3. [Configuration](#configuration)  
    3-1. [git config](#git-config)  
    3-2. [ssh key](#ssh-key)  
4. [GitLab Account](#gitlab-account)  
5. [Usage](#usage)  
    5-1. [Repository](#repository)  
    5-2. [Clone and pull](#clone-and-pull)  
    5-3. [Commit and push](#commit-and-push)  
    5-4. [Other](#other)  
6. [References](#references)  


## Required Tools
### Linux
Check if the required packages are existing:

- Git: `$ git --version`  
- OpenSSH: `$ ssh -V`

### Windows 10
- [Git for Windows](https://git-scm.com/download/win)
- [TortoiseGit](https://tortoisegit.org/download/)  
    ***Note that __TortoiseGit__ is different from __TortoiseSVN__.***  
    Developers who previously install TortoiseSVN should install TortoiseGit separately.

## Installation
### Ubuntu
- Git:  
```sh
$ sudo apt-get update
$ sudo apt-get install git
```
- OpenSSH client:  
```sh
$ sudo apt install openssh-client
```

### Windows 10
- Git:  
    -  Features to be installed  
    ![features](Images/git-setup-features.jpg)
  
    - Git command-line setup  
    ![env](Images/git-setup-env.jpg)  
  
    - Use __OpenSSH__ is recommended in many tutorial, but it is tested to cause error on Windows 10, so that __Tortoise Plink__ is used instead.  
    ![ssh](Images/git-setup-ssh.jpg)
  
    - Tested working  
    ![terminal](Images/git-setup-terminal.jpg)
  
    - Recommanded  
    ![line-ending](Images/git-setup-line-ending.jpg)
  
    - Left as default  
    ![extra](Images/git-setup-extra.jpg)

- TortoiseGit:
    - Register for git   
    ![features](Images/tortoisegit-setup-features.jpg)

## Configuration
### git config
### ssh key

## GitLab Account

## Usage
### Repository
### Clone and pull
### Commit and push
### Other

## References

