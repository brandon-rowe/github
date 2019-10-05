# github
Learning git

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

1. Initially, we will clone the github repo. Navigate to your desktop in the shell to clone. 
`$ cd Desktop`
`$ git clone https://github.com/brandon-rowe/github.git`

2. Next we will need to navigate to the github repo.
`$ cd github`

	
3. Now that we have navigated into the repo (folder), we need to make sure our 
git credentials are entered.
`$ git config --global user.name git_username`
`$ git config --global user.email git_emailaddress`

4. Once we have made our changes to the files within your github repo, we add
the changes from our working directory to the index (staging).
`$ git add *` or `$ git add filename.txt filename.java` 

5. Now we commit the changes from the index to the head (commiting).
`$ git commit -m "some message about changes"` 

6. Lastly, we push the changes to the repo, usually the master branch.
`$ git push origin master` 



<p>
This is a repo for testing git. Use this to test push/pull/merge with different branches.
<br>
Links in the resources list have more in-depth tutorials for walking through the basics of git. We have outlined the basics of the first link, Github Getting Started, above.
</p>

<h6>Resources</h6>

Extra links that help with github.
+ [Github Getting Started](https://rogerdudler.github.io/git-guide/)
+ [Branching](https://confluence.atlassian.com/bitbucket/branching-a-repository-223217999.html)
+ [Remote Server Setup](https://kbroman.org/github_tutorial/pages/init.html)
+ [Git-checkout docs](https://git-scm.com/docs/git-checkout)
+ [Finding Open-Source Programs](https://help.github.com/en/articles/finding-open-source-projects-on-github)
+ [Kanban Automation](https://help.github.com/en/articles/configuring-automation-for-project-boards)
+ [Mastering Markup](https://guides.github.com/features/mastering-markdown/)
+ [Git Commit Messages](https://chris.beams.io/posts/git-commit/)


