# 3.1: Intro to Git

_Git_ is probably the most used __version control__ system. Using version control means you always have a way to revert to an earlier version of your project in case you have issues. Version control also lets multiple developers work on the same project with fewer problems.

_Github_ is an online hosting service for Git __repositories__. Github lets users "fork" projects

* __Forking__ is copying a repository from one user's accoutn to another.
* If the second user makes changes, he/she can send a __pull request__ to the owner who can then choose to merge those changes into the original repo.

Github is also just a great place to store and backup your projects. Github also hosts simple static pages, meaning we can use Github to put our portfolio pages online for others to see.

### Create a New Repository

While Git and Github work with IDEs like Repl.it and there are desktop applications that help you integrate both into your workflow, many developers prefer to use the command line to use them.

Open your terminal and `cd` over to the top level directory that hosts your portfolio. In the terminal, type
```
    git init
```

Add a README file (we'll use this later) by typing `touch readme.md`.

### Add Your Github Credentials

Next, we'll need to add youd Github account info to the computer. Type (make sure you use the quotation marks):
```
    git config --global user.email "you@mail.com"
    git config --global user.name "Your Name"
```

### Add and Commit

In order to actually save your files to your git repo (short for repository), you first add them to a __staging area__, then __commit them__. Later, we'll __push__ them to Github.

In the terminal, make sure you're still in the same directory and type 
```
    git add .
```
You can also add single files by typing 
```
    git add <filename>
```

To check the status of your repo and see which files are ready to commit, type
```
    git status
```
When you're ready to commit, type
```
    git commit -m "commit message"
```
It's important to add a descriptive and meaningful message. That way, you'll have a history of all your commits and what you worked or changed on at each step.

### Add Your Repo to Github

Log into your Github account. Hit the plus sign in the upper right corner and select "New Repository." Give your repo a name and a short description. You can choose to make your repo public or private, then click "Create Repository."

To add your local repo to Github, you should be able to copy the path from Github. In the terminal, type
```
    git remote add origin <paste your repo address here>
```
Lastly, type
```
    git push origin master
```
Go back to Github, refresh the page, and make sure that your repo has been added and uploaded correctly. All the files from your directory should be listed, and you should be able to click on any of them to read the contents.

### Keep Your Repo Updated

When you make changes to files that you want to commit to git and push to github (do this after significant changes, not too often), you'll need to follow these steps:
1. Add the changed or updated files to the staging area
    `git add <filename>` or `git add .`
2. Commit the changes
    `git commit -m "commit message"`
3. Push the changes to your remote repo (Github)
    `git push origin master`
