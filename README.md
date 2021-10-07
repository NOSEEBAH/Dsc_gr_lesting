# dscly-git-infosession

<img src="banner.png"></br>

<b><h2><center>GDSC - Git & Github Repo</center></h2></b>
<b><center>this repo includes the needed things for the GDSC Git & Github info session</center></b>
<center>try to fork this repo to your account and work on it 😉.</center>
<center>Created By: Taha Alabyad
</center><br>

<b>Presentation File</b>: <a href="Git & Github.pdf">PDF File</a> or <a href="https://drive.google.com/file/d/1Gk5gVmJhygHUIX4nnBlcET0k3zDjnUCW/view?usp=sharing">Google Drive PDF File</a> 

<b>Git Download Link</b>: https://git-scm.com/downloads<br>

<b>Git Installation Guide</b>: https://youtube.com/playlist?list=PLs97GbUOC82nudd7axMvObNxEm59XwIhs<br>

<b>Git Command Ref</b>: https://git-scm.com/book/en/v2<br>

<b>Centralized vs Distributed Version Control</b> : https://www.geeksforgeeks.org/centralized-vs-distributed-version-control-which-one-should-we-choose/ </br>

<b>Github Education</b>: https://education.github.com/pack<br>

<b>Github Desktop</b>: https://desktop.github.com/<br>

<b>the next picture explains how repo works:</b>

<img src="trees.png"><br>

<b>Configure Tooling</b><br>
git config --global user.name "[name]"<br>
<i>Sets the name you want attached to your commit transactions</i><br>
git config --global user.email "[email address]"<br>
<i>Sets the email you want attached to your commit transactions</i><br>

<b>Create Repositories</b><br>
git init [project-name]<br>
<i>Creates a new local repository with the specified name</i><br>
git clone [url]<br>
<i>Downloads a project and its entire version history</i><br>

<b>Group Changes</b><br>
git branch<br>
<i>Lists all local branches in the current repository</i><br>
git branch [branch-name]</br>
<i>Creates a new branch</i><br>
git checkout [branch-name]<br>
<i>Switches to the specified branch and updates the working directory</i><br>
git merge [branch]<br>
<i>Combines the specified branch's history into the current branch</i><br>
git branch -d [branch-name]<br>
<i>Deletes the specified branch</i><br>
git remote add [remote-name] [url]<br>
<i>Add a new remote git repository as a shortname</i><br>
git remote -v<br>
<i>Lists all remote git repositories</i><br>

<b>Make Changes</b><br>
git status<br>
<i>Lists all new or modified files to be committed</i><br>
git diff<br>
<i>Shows file differences not yet staged</i><br>
git add [file]<br>
<i>Snapshots the file in preparation for versioning</i><br>
git diff --staged<br>
<i>Shows file differences between staging and the last file version</i><br>
git reset [file]<br>
<i>Unstages the file, but preserves its contents</i><br>
git commit -m "[descriptive message]"<br>
<i>Records the file snapshots permanently in version history</i><br>

<b>Save Fragments</b><br>
git stash<br>
<i>Temporarily stores all modified tracking files</i><br>

<b>Review History</b><br>
git log<br>
<i>Lists version history for the current branch</i><br>
git log --follow [file]<br>
<i>Lists version history for a file, including renames</i><br>
git diff [first-branch]...[second-branch]<br>
<i>Shows content differences between two branches</i><br>
git show [commit]<br>
<i>Outputs metadata and content changes of the specified commit</i><br>