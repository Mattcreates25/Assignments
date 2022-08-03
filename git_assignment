# Git-assignment
These are the steps for creating a repository on Git and github then linking them. 


on the commandline 
```bash
mkdir hello_world
```
this code makes a working directory called hello_world

move into the working directory using:

```bash
cd hello_world/
```
to be able to track the changes in our repository we use:

```bash
git init
```
this makes the directory a git repository

create a markdown file in the directory  for example

```bash
touch index.md
```

clone the repo you wish to merge to the repo you've just created

```bash
 git clone git@github.com:Mattcreates25/hello_world.git

```
__output__
```bash
Cloning into 'hello_world'...
Enter passphrase for key '/home/mark/.ssh/id_ed25519':
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (8/8), done.
remote: Total 10 (delta 1), reused 6 (delta 0), pack-reused 0
Receiving objects: 100% (10/10), done.
Resolving deltas: 100% (1/1), done.
```

move into the directory of the clone

```bash
cd hello_world/
```

create another remote in this clone which directs us to the second repo understanding _Git is a repo i've already created on Github

```bash
git remote add hello_world git@github.com:Mattcreates25/understanding_Git.git 
```

check the remotes that are available

```bash
git remote -v
```

__output__
```bash
hello_world     git@github.com:Mattcreates25/understanding_Git.git (fetch)
hello_world     git@github.com:Mattcreates25/understanding_Git.git (push)
origin  git@github.com:Mattcreates25/hello_world.git (fetch)
origin  git@github.com:Mattcreates25/hello_world.git (push
```

fetch content from the repo hello_world using:

```
git fetch hello_world
```

__output__
```bash
Enter passphrase for key '/home/mark/.ssh/id_ed25519':
warning: no common commits
remote: Enumerating objects: 15, done.
remote: Counting objects: 100% (15/15), done.
remote: Compressing objects: 100% (9/9), done.
remote: Total 15 (delta 0), reused 6 (delta 0), pack-reused 0
Unpacking objects: 100% (15/15), 2.53 KiB | 33.00 KiB/s, done.
From github.com:Mattcreates25/understanding_Git
 * [new branch]      master     -> hello_world/master
 ```
 
 the content of understanding_Git is in the remote still, which we fetched but can’t yet access. to do so we can copy it into a new local branch
 
 ```bash
 git checkout -b understanding_Git_branch hello_world/master
 ```
 
 get back into the master from the branch you've created
 ```bash
 git checkout master
 ```
 
 to merge the new branch do 
 ```
 git merge merge understanding_Git_branch
 ```
