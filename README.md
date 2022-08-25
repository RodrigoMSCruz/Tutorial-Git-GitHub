# Tutorial-Git-GitHub
A quick and basic tutorial on how to use Git and GitHub.
<br>
<h1>Git and GitHub</h1>
<br>
<h2>CONFIGURATION</h2>
git config --global user.name myNameHere<br>
git config --global.user.email mmm@email.com<br>
<br>
<h2>INITIALIZING</h2>
git init<br>
<br>
git add filename.txt<br>
git add .<br>
<br>
git commit -m "type comments here"<br>
<br>
git status<br>
git diff                    //Compare the current pre-commit file and the already committed version<br>
git log                     //Show history of all commits<br>
git show f35a198449ac...    //Show commit at a point in time
git show                    //Show the last commit at a point in time<br>
git checkout f35a198449ac... --file.txt     //Bring back the file from that point at time to the current time<br>
<br>
<h2>BRANCH</h2><br>
git branch nameOfTheBranch   //Create a branch<br>
git checkout nameOfTheBranch //Go to the branch<br>

<h3>TO JOIN THE BRANCH WITH THE MASTER</h3><br>
git checkout master<br>
git merge nameOfTheBranch<br>
git branch -d nameOfTheBranch<br>

<h2>GitHub</h2><br>
git remote add origin https://github.com/nameOfTheRepository //Add the git to the online repository in the GitHub<br>
git remote -v   //Show all the online repositories<br>
git push -u origin master<br>
