# github

What OS are you using? (Windows, Mac, Linux) Download git from link below.

+ [Git for Windows](https://git-scm.com/download/win)
+ [Git for Mac](https://git-scm.com/download/mac)
+ [Git for Linux](https://git-scm.com/download/linux)

<h3>Setup</h3>
<p>
Download and Install from link above.
<br>
Open Git Bash.
<br>

1. Initially, we will clone the github repo (folder). Navigate to your desktop (folder) in the shell and clone (copy from download). (cd - change directory to 'Desktop') (clone - download repo (folder)) </br>
`$ cd Desktop` </br>
`$ git clone https://github.com/brandon-rowe/github.git` `<-- input your repo here`</br>

2. Next we will navigate to the github repo. (cd - change directory to 'github' repo (folder))</br>
`$ cd github`</br>

3. Now that we have navigated to the repo (folder), we need to make sure our 
git credentials are entered. </br>
`$ git config --global user.name git_username` </br>
`$ git config --global user.email git_emailaddress` </br>

4. Once we have made our changes to the files within our github repo, we add
the changes from our working directory to the index (staging). </br>
`$ git add *` or `$ git add filename.txt filename.java` </br>

5. Now we commit the changes from the index to the head (commiting). </br>
`$ git commit -m "some message about changes"` </br>

6. Lastly, we push the changes to the repo, usually the master branch. </br>
`$ git push origin master` </br>



<p>
Links in the resources list have more in-depth tutorials for walking through the basics of git. We have outlined the basics of the first link, Github Getting Started, above.
</p>

<h6>Resources</h6>

Extra links that help with github.
### Basics
+ [Github Getting Started](https://rogerdudler.github.io/git-guide/)
+ [Git Commit Messages](https://chris.beams.io/posts/git-commit/)
+ [Mastering Markup](https://guides.github.com/features/mastering-markdown/)
+ [Remote Server Setup](https://kbroman.org/github_tutorial/pages/init.html)
+ [Kanban Automation](https://help.github.com/en/articles/configuring-automation-for-project-boards)
+ [Finding Open-Source Programs](https://help.github.com/en/articles/finding-open-source-projects-on-github)
+ [Github Code Review](https://github.com/features/code-review/)
+ [Managing Large Files with Git LFS](https://git-lfs.github.com/)

### Branching
+ [Git-checkout docs](https://git-scm.com/docs/git-checkout)
+ [Branching](https://confluence.atlassian.com/bitbucket/branching-a-repository-223217999.html)
+ [Delete Branch locally and remotely](https://stackoverflow.com/questions/2003505/how-do-i-delete-a-git-branch-locally-and-remotely)
+ [Switch Branch](https://backlog.com/git-tutorial/branching/switch-branch/)
+ [Syncing and Rebasing](https://help.github.com/en/desktop/contributing-to-projects/syncing-your-branch)
+ [Manage Branches](https://github.com/Kunena/Kunena-Forum/wiki/Create-a-new-branch-with-git-and-manage-branches)
+ [Update Branch to Master](https://stackoverflow.com/questions/47088506/git-update-branch-to-master)
+ [Comparing Branches and Pull Requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-comparing-branches-in-pull-requests)
+ [How to use Merge Correctly](https://dev.to/neshaz/how-to-use-git-merge-the-correctway-25pd)
+ [Resolving Merge Conflicts](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-on-github)
+ [Resolving Merge Conflicts with CLI](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/resolving-a-merge-conflict-using-the-command-line)



























