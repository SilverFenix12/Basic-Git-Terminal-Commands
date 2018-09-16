# Basic-Git-Terminal-Commands
Cheatsheet for Git Terminal commands in Mac

Initially you have to navigate to the folder you are going to work with in GitHub.

<h2>Git Terminal Commands:</h2>
<ul>
  <li><strong>git config --global user.name "Your Name"</strong> - Sets the username in our configuration for Git.</li>
  <li><strong>git config --global user.email "your email address"</strong> - Sets the username in our configuration for Git.</li>
  <li><strong>git config --list</strong> - Shows the basic config we have set for Git.</li>
  
  <li><strong>git init</strong> - Initializes the current folder as a git repository and sets it as Master.</li>
  <li><strong>git status</strong> - Gives us the current status of the folder we are in.</li>
  
  <li><strong>git add .</strong> - Adds files/folders in current directory to staging area, setting them for commit. </li>
  <li><strong>git commit</strong> - commit the staged files/folders changes to the git repository.
      <ol>
        <li>option '<strong>-m message</strong>' - Adds a message to our commit. </li>
      </ol>
  </li>
  <li><strong>git log</strong> - Shows a list of all the commits made to the repository.</li>
      <ol>
        <li>option '<strong>-- oneline</strong>' - Shows a shorter version of that list.</li>
      </ol>
  </li>
  <li><strong>git checkout --file_name</strong> - Discards changes in file_name.</li>
  <li><strong>git checkout commit_number file_name</strong> - Reverts to a previous version of file_name contained in the commit with commit_number. (note only the first 7 digits are required for the commit number). </li>
  <li><strong>git reset HEAD file_name</strong> - Removes a file from stage area. </li>
  <li><strong>git remote add origin link_address </strong> - sets our online repository as origin to push commits with changes.</li>
  <li><strong>git push -u origin master</strong> - pushes the contents of the local git repository to the “origin” set with git remote.</li>
  <li><strong>git clone link_address </strong> - downloads a copy of a repository and sets it in current folder.</li>
</ul>
  <li><strong></strong> </li>
