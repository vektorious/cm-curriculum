---
layout: page
title: "Version control"
module: "3.1"
date: 2016-10-06 14:05:56
#time: "20 min"
following: _articles/03-building-open-projects/modularity.md
summary: "A key tool for efficient collaborative work"
#prereq: "Have completed all previous sections and modules"
#materials: "Pen or pencil and paper"
---

* TOC
{:toc}

### Introduction to version control systems

Think about the times you worked in collaboration with someone, where you were both writing in the same Word document. It was a bit cumbersome, right? You most likely had to take turns, so not to overwrite/redo the same part of the text the other person was working on. On top of that you had to create multiple versions of the file, so that you could keep track of the most recent changes.

This is quite inefficient and confusing!! What was the last version? Was it my turn to be working on this? So many potential opportunities for errors and time lost.

And this is just talking about two people working in one file. Can you imagine projects with multiple files and many different contributors? It becomes almost impossible to work together and collaborate!

### Why is it important and what is is it useful for

Luckily a solution for this type of issue has been created. Called version control system (VCS), it keeps track of file changes, who made then, at what time, and in which part of the file.

The direct benefits of using a VCS are:
 - you don't need several copies of the same file, as VCS takes care of showing you what is the most up to date version, or if you are working on something that has been already updated by someone else
 - you can go "back in time" and see what changes were made and when (and also bring some changes of the past to the most recent version of your project)
 - all collaborators in a project can work on it at the same time and add their changes to the project without the risk of accidentally overwriting someone else's work.

Another very important feature of VCS systems is that it also flags and indicates to users when two changes created a "conflict". For example, both you and your colleague changed the same part in a text at the same time, the VCS would flag it, and "say" - someone needs to take an extra look at this, since there are overlapping changes.

In such a conflict case, the version control system would highlight the part that is in overlapping and block further changes until someone looks at it and decides which text to use (or even merge both versions of the text into a new one).

There are many other useful features of VCS, but to avoid an information overload, interested readers can find useful links below on the [resources section](#resources)

### Use cases and examples

Very likely the most known use case of version control comes from the software industry, where many different people are working on the same project at the same time, and the files created sometimes have thousands of lines.

People outside the software industry most likely have come across VCS when they use cloud services. Google Drive, Nextcloud or Dropbox have built-in version control. This is normally presented to users as a "restore" function, so that older versions of a certain file can be brought back and displayed as the most recent one.

Although popular services such as Google Docs have version control and other useful features such as visual simultaneous collaboration, in open hardware we use version control in a different way.

### Understanding GIT version control

For OHM we suggest participants to take a look and understand GIT so that they can use it on their project workflow. Just one of many VCS systems but by far the most used, having a project that is running with GIT VCS allows others to promptly contribute to your project and also allows newcomers to leverage the many online tutorials and the many people in this community that use GIT on a daily basis and can offer help.

Initially you should understand three main GIT commands:
- `git add`
- `git commit`
- `git push`

These commands will respectively:
- add changes made to files to a "staging area"
- commit those changes to the version control history and allow them to be tracked
- push those changes to an online version of your own repository (most likely hosted on GitHub or GitLab)

More details about git and getting started can be found in the [resources section](#resources).

#### Available platforms

For GIT the most widely used platforms are:  
- [GitHub](https://github.com)    
- [GitLab](https://gitlab.com)
- [Bitbucket](https://bitbucket.org/)

What's the difference between git, GitHub, and GitLab? The three are often a source of confusion. Git, as we mentioned, is the software that handles version control, letting you make and track local file changes and share changes with a remote repository. GitLab, GitHub and others like BitBucket are platforms that offer services based on Git.

GitHub is a cloud service for remote hosting of git repositories. In addition to hosting your code, the site helps manage software development projects with features like issue tracking, collaborating with other GitHub users, and hosting web pages. GitHub offers free services for open source projects (accessible to the public) and paid tiers for private projects. For public projects, anyone can see code you push to GitHub and offer suggestions, or even code, to improve your project. GitHub currently hosts the source code for tens of thousands of open source projects, but is not alone. BitBucket and GitLab.com offer comparable services.

The most significant difference between the two is that while GitHub is a collaboration platform that helps review and manage codes remotely, GitLab is majorly focused on DevOps and CI/CD. GitHub is more popular amongst the developers as it holds millions of repositories, but recently GitLab has been gaining popularity, as the company continues to add new features to make it more competitive and user-friendly.

Some institutions and sometimes people choose to run "self-hosted" instances of GitHub or GitLab. Self-hosting means you use your own resources (a server) to host and run applications instead of renting the services from the platforms. The benefit of self-hosting is that the user has complete control over their data, at a potentially lower monthly cost. The downside is that the user is responsible for maintaining the service. If the service encounters an error, the user is responsible for resolving the issue.


#### History of git

Git was born out of a need in the Linux Kernel community and has an interesting story, given that it is an open source tool, created to help manage an another open source project, and it is now one of the most widely used tools for software development and open collaborations.

Interested readers can find a nice short version of its history [here](https://git-scm.com/book/en/v2/Getting-Started-A-Short-History-of-Git).

### {{ site.assignment }} Define how you implement version control in your project
VCS are really useful for handling your hardware project files. If you use a platform like GitLab or GitHub, you have the advantage of using VCS and making your repository publicly available.
- Think of the files that you need to track along the life of your project.
- Which are these files?
- Which platform suits your needs better?
- How do you plan to organize your repository so people can quickly find your project files?

### Resources
- [Version control with GIT](http://swcarpentry.github.io/git-novice/)  
- [Learn GIT](https://www.atlassian.com/git)  
- [Dang it git!](https://dangitgit.com/)
- [GitHub vs GitLab: Difference Between GitHub and GitLab](https://www.upgrad.com/blog/github-vs-gitlab-difference-between-github-and-gitlab/)
