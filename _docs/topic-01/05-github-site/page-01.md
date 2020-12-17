---
title: Git Version Control
module: topic-01
permalink: /topic-01/gh-vcs/
categories: development
tags: git, vcs
---

<div class="divider-heading"></div>


One great thing about working with text files is that their simplicity makes it easy to track changes between various versions of that file. Since the files contain only <a href="http://www.asciitable.com" target="_blank">ASCII</a> characters, it is easy to create programs that can look for character or word level changes to a document.

<blockquote>
  <p><i>You can think of a <b>version control system</b> (VCS) as a way to remember all the changes you made.” It lets you save a snapshot of your complete project at any time you want. When you later take a look at an older snapshot (let's start calling it “version”), your VCS shows you exactly how it differed from the previous one.</i></p>
  <p>- <a href="https://www.git-tower.com/learn/git/ebook/en/command-line/basics/what-is-version-control#start" target="_blank">Git-Tower.com</a></p>
</blockquote>

<img src="../img/what-is-vcs.png" alt="database-like structure tracking changes to a file with date stamps" title="Version Control" />


<div class="divider-pg"></div>


## Why use a VCS?
- **Tracking Changes** - Version control allows a developer/writer to make changes to a file and track their changes over time. By “committing” changes to a file with a simple, associated message, the developer can create a list of how they have changed them over time.
- **Revert Back** - Version control allows a developer/writer to make changes that may or may not work. If they find that the difference they made was inappropriate, or did not work, they can revert to a previous version. There is no need for directories full of “save as...” files.
- **Share and Collaborate** - Version control makes collaboration and sharing easier. All associated parties can then see all changes made by each other and manage any conflicts that may occur within a file.

<div class="divider-pg"></div>


## “Yes, but why are _we_ using a VCS?”
- **Homework Trial and Error** - Using the principles of GIT, you can track incremental changes to your work throughout your weekly assignments. GitHub allows students to see their change history, test things, and revert to previous versions should these tests not work.
- **Free Hosting** - Your git repositories (or repos) can easily be integrated with <a href="https://github.com/" target="_blank">GitHub.com</a>, which has some definite benefits, such as cloud backup and free hosted webspace. (This is how you will submit assignments during most of the course.)
- **Be Professional Early** - GIT and <a href="https://github.com/" target="_blank">GitHub.com</a> are standard industry tools in both commercial and research facilities. Your familiarity and comfort with GIT will make you a better future collaborator and prepare you for working in many development fields.
