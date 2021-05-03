# GIT ALL COMMANDS - a quick cheat - sheet
---
**Download GIT Software From Below Link**
[https://git-scm.com/downloads](https://git-scm.com/downloads)

**After Install, Open CMD & Check The Git Version By Below Command**  
`git --version`
## GIT Commands and Descriptions are Listed Below

> **Git Setup and Configuration**

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
  <dt>5. <code>git config --global user.email 'YOUR_EMAIL'</span></code></dt>
  <dd><small><i>Define the author email to be used for all commits by the current user. Set the e-mail address that will be attached to your commits and tags.</i></small></dd>
</dl>

<dl>
  <dt>6. <code>git config --global color.ui auto</span></code></dt>
  <dd><small><i>Set automatic command line coloring for Git for easy reviewing. Enable some colorization of Git output.</i></small></dd>
</dl>

<dl>
  <dt>7. <code>git config --system core.editor 'YOUR_EDITOR_NAME'</span></code></dt>
  <dd><small><i>Set text editor used by commands for all users on the machine. <code>'YOUR_EDITOR_NAME'</code>arg should be the command that launches the desired editor (e.g., vi).</i></small></dd>
</dl>

<dl>
  <dt>8. <code>git config --global --edit</span></code></dt>
  <dd><small><i>Open the global configuration file in a text editor for manual editing.</i></small><dd>
</dl>

> **Git Clone a Repo**

<dl>
  <dt>9. <code>git clone 'REPO_URL'</span></code></dt>
  <dd><small><i>Clone repo located at <code>'REPO_URL'</code> onto local machine. Original repo can be
located on the local filesystem or on a remote machine via HTTP or SSH.Downloads a project with the entire history from the remote repository.</i></small><dd>
</dl>

<dl>
  <dt>10. <code>git clone -c http.sslverify=false 'REPO_URL'</span></code></dt>
  <dd><small><i>Clone repo located at <code>'REPO_URL'</code> onto local machine. Original repo can be
located on the local filesystem or on a remote machine via HTTP or SSH.Downloads a project with the entire history from the remote repository.</i></small><dd>
</dl>

> **Git Add Files**

<dl>
  <dt>10. <code>git add .</span></code></dt>
  <dd><small><i>Add all modified files to commit.</i></small><dd>
</dl>

<dl>
  <dt>11. <code>git add 'ANY_PARTICULAR_FILE_NAME'</span></code></dt>
  <dd><small><i>Add any particular modified file to commit.</i></small><dd>
</dl>

<dl>
  <dt>12. <code>git add *.txt</span></code></dt>
  <dd><small><i>Add all .txt modified files to commit.</i></small><dd>
</dl>

<dl>
  <dt>13. <code>git status</span></code></dt>
  <dd><small><i>Show git tree status. List which files are staged, unstaged, and untracked. show modified files in working directory, staged for your next commit.</i></small><dd>
</dl>

> **Commits**

<dl>
  <dt>14. <code>git commit -m 'YOUR_COMMIT_MSG'</span></code></dt>
  <dd><small><i>Commit the staged snapshot, but instead of launching
a text editor, use <code>'YOUR_COMMIT_MSG'</code> as the commit message..</i></small><dd>
</dl>

> **Branches**

<dl>
  <dt>15. <code>git branch 'BRANCH_NAME'</span></code></dt>
  <dd><small><i>Create a new branch for your project</i></small><dd>
</dl>

<dl>
  <dt>16. <code>git branch</span></code></dt>
  <dd><small><i>Showing all your working branches</i></small><dd>
</dl>

<dl>
  <dt>17. <code>git branch --all</span></code></dt>
  <dd><small><i>Showing all avaliable branches in the project</i></small><dd>
</dl>

<dl>
  <dt>18. <code>git checkout 'YOUR_EXISTING_BRANCH_NAME'</span></code></dt>
  <dd><small><i>Switch working directory to the specified branch.</i></small><dd>
</dl>

<dl>
  <dt>1. <code>git checkout -b 'BRANCH_NAME'</span></code></dt>
  <dd><small><i>Create and check out a new branch.</i></small><dd>
</dl>


