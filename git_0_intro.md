# Git Terminology

## Git     --[terminal]
Git is a system for version control and it is independent of GitHub. It runs at the **command line on your local machine** and allows you to keep track of your files and modifications in a "repository". 

### Fun Fact on Git
* Git was created by Linus Torvalds in 2005 for development of the Linux kernel, with other kernel developers contributing to its initial development.

Check out his Ted Talk:  [The Mind Behind Linux](https://www.ted.com/talks/linus_torvalds_the_mind_behind_linux)  
>Linus Torvalds transformed technology twice -- first with the Linux kernel, which helps power the Internet, and again with Git, the source code management system used by developers worldwide. In a rare interview with TED Curator Chris Anderson, Torvalds discusses with remarkable openness the personality traits that prompted his unique philosophy of work, engineering and life. "I am not a visionary, I'm an engineer," Torvalds says. "I'm perfectly happy with all the people who are walking around and just staring at the clouds ... but I'm looking at the ground, and I want to fix the pothole that's right in front of me before I fall in."

## GitHub    --[browser]
**GitHub** is an online facility where projects are made available for others to access and make contributions. Projects are maintained and managed in **repositories**. Github allows you to have a backup of your files *away* fom your local machine in these repositories. It has a visual interface to navigate your repositories, and it allows other people to be able to view them. People often refer to the repositories as **repos**. 

In addition, Github includes some very nice tools for software projects, like Markdown rendering, issue tracker and wiki tools, and the ability to “fork” a project to make your own independent copy of it for development. This repository, for example, is indeed a fork from https://github.com/reshama/git-intro-workshop5-pyladies, which I slightly modified ror the purpose of my class.

GitHub is also *social*. 
Just like a social networking site, individuals who participate on GitHub have profiles that share details about who they are. Github users can **watch** repositories, follow other users’ activities, and interact with their peers. 

Github is a hub for open source development and you too as a github user can contribute to an open source project by opening an  **issue** if you encounter a bug in a software or submitting a **pull request**. 

Check out this TechCrunch article:  [What Exactly is GitHub Anyway?](https://techcrunch.com/2012/07/14/what-exactly-is-github-anyway/)

## What is version control?
Version control systems are a category of software tools that help a software team manage changes to source code over time.   
- Version control software keeps track of every modification to the code in a special kind of database. Git tracks modifications by creating a *snapshot* of the project's states when those states are **commited**.

## Why is version control useful?
* **Backup** — computer crashes
	* *Undo* — Oops, was that important?
* **Collaborate** — programming is a team sport
	* *Track steps* — What happened while you were sleeping
	* *Branching and merging* — Work in parallel and bring it back together
* **Transparency**
	* *Transparency* - For scientists, it is important that others can see each step of their analysis; it gives their research credibility. With `snapshots` available at each revision in the project, everyone can see how we got to the final result/code.
	

## Remotes 
Remotes are copies of a repo on another computer **(or on a service like Github)**  

Example:  
* `upstream` [organization repo]
* `origin`   [your forked repo]

## Branches
Branching means you diverge from the main line of development and continue to do work without changing the main line. 


## Account settings
- review account options
