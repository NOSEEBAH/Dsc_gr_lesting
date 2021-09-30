# dscly-git-infosession
this repo includes the needed things for the dsc git info session

ref:https://git-scm.com/book/en/v2

<b>Configure Tooling</b>
git config --global user.name "[name]"
<i>Sets the name you want attached to your commit transactions</i>
git config --global user.email "[email address]"
<i>Sets the email you want attached to your commit transactions</i>

<b>Create Repositories</b>
git init [project-name]
<i>Creates a new local repository with the specified name</i>
git clone [url]
<i>Downloads a project and its entire version history</i>

<b>Group Changes</b>
git branch
Lists all local branches in the current repository
git branch [branch-name]
Creates a new branch
git checkout [branch-name]
Switches to the specified branch and updates the working directory
git merge [branch]
Combines the specified branch's history into the current branch
git branch -d [branch-name]
Deletes the specified branch
git remote add [remote-name] [url]
Add a new remote git repository as a shortname
git remote -v
Lists all remote git repositories