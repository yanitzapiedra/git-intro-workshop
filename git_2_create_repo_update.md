# Create a Repository on GitHub


## Step 1: Create a repo using GitHub (on web browser)
- Click on `+` next to your profile picture
- Select `New Repository`
- Repository name:  `starting_git`
- Description (optional):  `test project for git`
- `Public` repos are free
- Check box for `Initialize this repository with a README`
- Select green button `Create repository`

## Step 2:  Let's add a couple of files
- Add a Markdown file:  `holiday.md`
  - add a line with an emoji
  - I added:  _Looking forward to the party :pizza: ! :smiley:_
- Add a Python file:  `hello.py`
  - add a line, the ubiquitous:  `print("Hello World")`
  
**Note:  add a meaningful commit message**  

## Step 3:  Clone repo

### Select green button "Clone or download" and copy url

### Go to directory on local computer  
For me, it is: 
`https://github.com/anastasiaclark/git_intro`  

#### Clone repo
`git clone https://github.com/anastasiaclark/git_intro.git`  

>my example  
```console                                                            
Cloning into 'git_intro'...
remote: Counting objects: 3, done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), done.
Anastasias-MBP:~ anastasiaclark$
```

### `cd` into cloned repo
```console
Anastasias-MBP:git_intro anastasiaclark$ cd git_intro/
Anastasias-MBP:git_intro anastasiaclark$```

```console
Anastasias-MBP:git_intro anastasiaclark$ ls 
README.md	holiday.md
Anastasias-MBP:git_intro anastasiaclark$ 
```

### Check out the remote
Note:  
- a 'remote' is a copy of a repository
- notice you have push and pull access  

>my example  
```console
Anastasias-MBP:git_intro anastasiaclark$  git remote -v
origin	https://github.com/anastasiaclark/git_intro.git (fetch)
origin	https://github.com/anastasiaclark/git_intro.git (push)
```

### We can 'pull' updates from GitHub version
```console
Anastasias-MBP:git_intro anastasiaclark$  git pull
Already up-to-date.
```

## Step 4:  Make changes on local computer 

### Let's make a change on local computer and push changes up to GitHub
Open new command line/terminal and type `Spyder` to launch the Spyder editor (or use nano or any other edittor) and create a new python file which will print your name.  

My file `print_name.py` contains the following line of code:  
```python
print("My name is Anastasia")
```

### We made a change!  How does git track it?
To see what changes have been made since last `git pull`, type `git status`  
```console
Anastasias-MBP:git_intro anastasiaclark$  git status
On branch master
Your branch is up-to-date with 'origin/master'.
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	print_name.py

nothing added to commit but untracked files present (use "git add" to track)

Anastasias-MBP:git_intro anastasiaclark$  
```
