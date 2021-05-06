# GIT ALL COMMANDS - a quick cheat - sheet
---
**Download GIT Software From Below Link**
[https://git-scm.com/downloads](https://git-scm.com/downloads)

**After Install, Open CMD & Check The Git Version By Below Command**  
`git --version`
## GIT Commands and Descriptions are Listed Below

> **GIT SETUP AND CONFIGURATION**
---

<dl>
  <dt>1. <code>git init</span></code></dt>
  <dd><small><i>initialize git for your project (only first time).</i></small></dd>
</dl>

<dl>
  <dt>2. <code>git config</span></code></dt>
  <dd><small><i>showing the configuration & all avaliable syntax.</i></small></dd>
</dl>

<dl>
  <dt>3. <code>git config --list</span></code></dt>
  <dd><small><i>showing the global configurations for your project.</i></small></dd>
</dl>

<dl>
  <dt>4. <code>git config --global user.name 'YOUR_NAME'</span></code></dt>
  <dd><small><i>Define the author name to be used for all commits by the current user. Set the name that will be attached to your commits and tags.</i></small></dd>
</dl>

<dl>
  <dt>4.1. <code>git config user.name 'YOUR_NAME'</span></code></dt>
  <dd><small><i>Define the author name project basis, not globally</i></small></dd>
</dl>

<dl>
  <dt>5. <code>git config --global user.email 'YOUR_EMAIL'</span></code></dt>
  <dd><small><i>Define the author email to be used for all commits by the current user. Set the e-mail address that will be attached to your commits and tags.</i></small></dd>
</dl>

<dl>
  <dt>5.1. <code>git config user.email 'YOUR_NAME'</span></code></dt>
  <dd><small><i>Define the author email project basis, not globally</i></small></dd>
</dl>

<dl>
  <dt>6. <code>git config --global user.name </span></code></dt>
  <dd><small><i>Check global author name which you set for globally in global config</i></small></dd>
</dl>

<dl>
  <dt>6.1. <code>git config user.name </span></code></dt>
  <dd><small><i>Check author name which you set for the project config</i></small></dd>
</dl>

<dl>
  <dt>7. <code>git config --global user.email </span></code></dt>
  <dd><small><i>Check global author email which you set for globally in global config</i></small></dd>
</dl>

<dl>
  <dt>7.1. <code>git config user.email </span></code></dt>
  <dd><small><i>Check author email which you set for the project config</i></small></dd>
</dl>

<dl>
  <dt>8. <code>git config --global color.ui auto</span></code></dt>
  <dd><small><i>Set automatic command line coloring for Git for easy reviewing. Enable some colorization of Git output.</i></small></dd>
</dl>

<dl>
  <dt>9. <code>git config --system core.editor 'YOUR_EDITOR_NAME'</span></code></dt>
  <dd><small><i>Set text editor used by commands for all users on the machine. <code>'YOUR_EDITOR_NAME'</code>arg should be the command that launches the desired editor (e.g., vi).</i></small></dd>
</dl>

<dl>
  <dt>10. <code>git config --global --edit</span></code></dt>
  <dd><small><i>Open the global configuration file in a text editor for manual editing.</i></small><dd>
</dl>

> **GIT CLONE A REPO**
---

<dl>
  <dt>11. <code>git clone 'REPO_URL'</span></code></dt>
  <dd><small><i>Clone repo located at <code>'REPO_URL'</code> onto local machine. Original repo can be
located on the local filesystem or on a remote machine via HTTP or SSH.Downloads a project with the entire history from the remote repository.</i></small><dd>
</dl>

<dl>
  <dt>12. <code>git clone -c http.sslverify=false 'REPO_URL'</span></code></dt>
  <dd><small><i>Clone repo located at <code>'REPO_URL'</code> onto local machine. Original repo can be
located on the local filesystem or on a remote machine via HTTP or SSH.Downloads a project with the entire history from the remote repository.</i></small><dd>
</dl>

> **GIT ADD FILES**
---

<dl>
  <dt>13. <code>git add .</span></code></dt>
  <dd><small><i>Add all modified files to commit.</i></small><dd>
</dl>

<dl>
  <dt>14. <code>git add 'ANY_PARTICULAR_FILE_NAME'</span></code></dt>
  <dd><small><i>Add any particular modified file to commit.</i></small><dd>
</dl>

<dl>
  <dt>15. <code>git add *.txt</span></code></dt>
  <dd><small><i>Add all .txt modified files to commit.</i></small><dd>
</dl>

<dl>
  <dt>16. <code>git status</span></code></dt>
  <dd><small><i>Show git tree status. List which files are staged, unstaged, and untracked. show modified files in working directory, staged for your next commit.</i></small><dd>
</dl>

> **GIT COMMIT**
---

<dl>
  <dt>17. <code>git commit -m 'YOUR_COMMIT_MSG'</span></code></dt>
  <dd><small><i>Commit the staged snapshot, but instead of launching
a text editor, use <code>'YOUR_COMMIT_MSG'</code> as the commit message..</i></small><dd>
</dl>

> **GIT BRANCH**
---

<dl>
  <dt>18. <code>git branch 'BRANCH_NAME'</span></code></dt>
  <dd><small><i>Create a new branch for your project</i></small><dd>
</dl>

<dl>
  <dt>19. <code>git branch</span></code></dt>
  <dd><small><i>Showing all your working branches</i></small><dd>
</dl>

<dl>
  <dt>20. <code>git branch --all</span></code></dt>
  <dd><small><i>Showing all avaliable branches in the project</i></small><dd>
</dl>

<dl>
  <dt>21. <code>git checkout 'YOUR_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Switch working directory to the specified branch.</i></small><dd>
</dl>

<dl>
  <dt>22. <code>git checkout -b 'BRANCH_NAME'</span></code></dt>
  <dd><small><i>Create and check out a new branch.</i></small><dd>
</dl>

<dl>
  <dt>23. <code>git branch -d 'YOUR_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Delete any branch from your local.</i></small><dd>
</dl>

<dl>
  <dt>24. <code>git branch -D 'YOUR_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Forcefully delete any branch from your local.</i></small><dd>
</dl>

<dl>
  <dt>25. <code>git push origin --delete 'YOUR_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Delete any branch from your git.</i></small><dd>
</dl>

<dl>
  <dt>26. <code>git merge 'YOUR_OTHER_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Current branch merge with other existing branch.</i></small><dd>
</dl>

> **GIT DIFF**
---

<dl>
  <dt>27. <code>git diff 'FILE_NAME'</span></code></dt>
  <dd><small><i>Difference of what is changed but not staged.</i></small><dd>
</dl>

<dl>
  <dt>28. <code>git diff 'BRANCH_NAME_1, BRANCH_NAME_2'</span></code></dt>
  <dd><small><i>Showing difference between branches.</i></small><dd>
</dl>

> **GIT TAG**
---

<dl>
  <dt>29. <code>git tag</span></code></dt>
  <dd><small><i>List all tags.</i></small><dd>
</dl>

<dl>
  <dt>30. <code>git tag 'NEW_TAG_NAME'</span></code></dt>
  <dd><small><i>Create new tag.</i></small><dd>
</dl>

<dl>
  <dt>31. <code>git push origin 'YOUR_BRANCH_NAME' --tags</span></code></dt>
  <dd><small><i>Commit with tag.</i></small><dd>
</dl>

<dl>
  <dt>32. <code>git show 'TAG_NAME'</span></code></dt>
  <dd><small><i>Show changes/difference for the tag</i></small><dd>
</dl>

<dl>
  <dt>33. <code>git push origin 'TAG_NAME'</span></code></dt>
  <dd><small><i>Push into a tag</i></small><dd>
</dl>

<dl>
  <dt>34. <code>git tag -d 'TAG_NAME'</span></code></dt>
  <dd><small><i>Delete a tag from local.</i></small><dd>
</dl>

<dl>
  <dt>35. <code>git push --delete origin 'TAG_NAME'</span></code></dt>
  <dd><small><i>Delete a tag from git.</i></small><dd>
</dl>

> **GIT LOGS**
---
<dl>
  <dt>36. <code>git log</span></code></dt>
  <dd><small><i>Show all commits in the current branch’s history.</i></small><dd>
</dl>

<dl>
  <dt>37. <code>git log -'NO_OF_LOGS'</span></code></dt>
  <dd><small><i>Show that no. of logs commits in the current branch’s history, ex: git log -3</i></small><dd>
</dl>

<dl>
  <dt>38. <code>git log --oneline</span></code></dt>
  <dd><small><i>Show all commits in the current branch’s history in one single line, more clear view.</i></small><dd>
</dl>

<dl>
  <dt>39. <code>git log --oneline -'NO_OF_LOGS'</span></code></dt>
  <dd><small><i>Show that no. of logs commits in the current branch’s history in one single line, more clear view, ex: git log --oneline -3</i></small><dd>
</dl>

<dl>
  <dt>40. <code>git log -p</span></code></dt>
  <dd><small><i>Display the full diff of each commit.</i></small><dd>
</dl>

<dl>
  <dt>40. <code>git log -p -'NO_OF_LOGS'</span></code></dt>
  <dd><small><i>Display the full diff of no. of commits that you want. ex: git log -p -3.</i></small><dd>
</dl>

<dl>
  <dt>41. <code>git log -p 'FILE_NAME'</span></code></dt>
  <dd><small><i>Show changes over time for a specific file.</i></small><dd>
</dl>

<dl>
  <dt>42. <code>git log --stat</span></code></dt>
  <dd><small><i>Include which files were altered and the relative number of
lines that were added or deleted from each of them.</i></small><dd>
</dl>

<dl>
  <dt>43. <code>git reflog</span></code></dt>
  <dd><small><i>List operations (e.g. checkouts or commits) made on local repository.</i></small><dd>
</dl>

<dl>
  <dt>44. <code>git log --author='AUTHOR_NAME'</span></code></dt>
  <dd><small><i>Search for commits by a particular author</i></small><dd>
</dl>

<dl>
  <dt>45. <code>git log --grep='COMMIT_MSG'</span></code></dt>
  <dd><small><i>Search for commits with a commit message that matches parttern.</i></small><dd>
</dl>

<dl>
  <dt>46. <code>git log --graph --decorate</span></code></dt>
  <dd><small><i>--graph flag draws a text based graph of commits on left side of commit
msgs. --decorate adds names of branches or tags of commit.</i></small><dd>
</dl>

<dl>
  <dt>47. <code>git log --oneline --graph --decorate</span></code></dt>
  <dd><small><i>An overview with reference labels and history graph. One commit per line.</i></small><dd>
</dl>

<dl>
  <dt>48. <code>git blame 'FILE_NAME'</span></code></dt>
  <dd><small><i>Who change - what, when for the file.</i></small><dd>
</dl>

<dl>
  <dt>49. <code>git blame 'FILE_NAME'</span></code></dt>
  <dd><small><i>Who change - what, when for the file.</i></small><dd>
</dl>

<dl>
  <dt>50. <code>git log 'branchB' 'branchA'</span></code></dt>
  <dd><small><i>show the commits on branchA that are not on branchB.</i></small><dd>
</dl>

<dl>
  <dt>51. <code>git log --follow 'FILE_NAME'</span></code></dt>
  <dd><small><i>show the commits that changed file, even across renames.</i></small><dd>
</dl>

> **GIT RESET**
---
