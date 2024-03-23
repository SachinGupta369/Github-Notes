Check for git version
`git --version`

how to initalise a git repo, How to enable git
`git init`

How to make a new branch
`git branch <branch-name>`

How to view the branches
`git branch`

How to switch to different branch
`git switch <branch-name>`

How to create a new branch and switch at the same time
`git checkout -b <branch-name>`

Tracking/knowing which files to put
`git add <file-1> <file-2> <file-3>`
for tracking everything
`git add .`

Putting commit/finalising version of code
`git commit -m <"commit-message">`

Pushing code to github
`git push`

Upstream mean

How to remove a file
`git rm <file-name>`

How to see the commit on branchA that are not on branchB
`git log branchB..branchA`

How to see diff of what is in branchA that is not in branchB
`git diff branchB...branchA`

How to clone entire repository
`git clone <url of repo>`

#Configurinf user information used across all local repositories
set a name that is identifiable for credit when review version history
`git config --global user.name <"FIRSTNAME LASTNAME">`

Set an email address that will be associated with each history marker
`git config --global user.email <"valid-email">`
