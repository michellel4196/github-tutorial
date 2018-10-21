# GitHub Tutorial

_By Michelle Lin_

---
## Git vs. GitHub

* **Git** = version control (keeps a snapshot of your code)
  * **This does not require Github**
  * Runs in command line
  * Basic workflow:
     * You have a directory (folder) with files in them
     * When you initialize git, it's called a repository (repo)
  * 
* **Github** = stores your code in the cloud (internet)
  * **This reguires git**
  * Makes it easier to track the changes in your code
  * Easier to collaborate on files (you can help someone else with their project)


---
## Initial Setup

**Steps to setup a github account:**

1) Create a [github](https://github.com/) account
   * Make a username and password (If you go to HSTAT, you can use your HSTAT email)
2) Choose your plan (Click the free option)
3) Choose your experiences 
   * Choose the student option
4) 

**Steps to setup a cloud9 account:**

1) Go to [cloud9](https://c9.io/login)
2) Click on the cat icon on the top right corner 
    * Login using your github account
3) Go to the top right corner of your screen > click "connect service" > click connect on the github section
4) Create your "github-learning" workspace
   * Name the workspace "github-learning" (all lower case)
   * In the descriptions, type "Version Control and Collaboration"
   * Select "don't set a team for this workspace"
   * For the template, select "Blank" > click "Create Workspace"

**Steps to setup SSH key:**

1) Go to https://github.com/ 
2) On the top right, click the profile icon > settings
3) On the left side bar > SSH and GPG
4) Click "New SSH key" botton
5) Title: Cloud9
6) Key: 
   * Go to your cloud9 tab > top right > gear icon 
   * Go to "SSH key" tab > copy & paste the 2nd SSH key into github 
     * The beginning starts with "ssh-rsa"
   * Add SSH key (Only need to use once)
7) Go to cloud9 > open git-learning IDE
   * ssh -T git@github.com
   * It would say "Hi <your username>!You've successfully authenticated, but GitHub does not provide shell access"


---
## Repository Setup

To make a new repo on github

When initializing the stage, be sure you are not in the workspace. 
  * If you did initialize your workspace, you can use "rm -rf .git"
```bash
michellel4196:~/workspace $ git init 
initialized empty Git repository in /home/ubuntu/workspace/.git/
michellel4196:~/workspace (master) $ 
michellel4196:~/workspace (master) $ rm -rf .git 
michellel4196:~/workspace $ 
```
**Your first repo on github:**

Make a new folder, name it first-repo (make sure you are in the workspace)
```bash
michellel4196:~/workspace $ mkdir first-repo
michellel4196:~/workspace $ cd first-repo
michellel4196:~/workspace/first-repo $ git init
michellel4196:~/workspace/first-repo (master) $
```
Make a new file inside your first-repo
```bash
michellel4196:~/workspace/first-repo (master) $ touch README.md
michellel4196:~/workspace/first-repo (master) $ c9 README.md
```
When you are done writing in your file > add > commit 
```bash
michellel4196:~/workspace/first-repo (master) $ git add README.md

```

Your first add and commit

---
## Workflow & Commands



---
## Rolling Back Changes