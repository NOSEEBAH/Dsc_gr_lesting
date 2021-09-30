# dscly-git-infosession
this repo includes the needed things for the dsc git info session

git reso:https://git-scm.com/downloads
git command ref:https://git-scm.com/book/en/v2
github education:https://education.github.com/pack


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
<i>Lists all local branches in the current repository</i>
git branch [branch-name]
<i>Creates a new branch</i>
git checkout [branch-name]
<i>Switches to the specified branch and updates the working directory</i>
git merge [branch]
<i>Combines the specified branch's history into the current branch</i>
git branch -d [branch-name]
<i>Deletes the specified branch</i>
git remote add [remote-name] [url]
<i>Add a new remote git repository as a shortname</i>
git remote -v
<i>Lists all remote git repositories</i>

<b>Make Changes</b>
git status
<i>Lists all new or modified files to be committed</i>
git diff
<i>Shows file differences not yet staged</i>
git add [file]
<i>Snapshots the file in preparation for versioning</i>
git diff --staged
<i>Shows file differences between staging and the last file version</i>
git reset [file]
<i>Unstages the file, but preserves its contents</i>
git commit -m "[descriptive message]"
<i>Records the file snapshots permanently in version history</i>