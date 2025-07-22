This repo is to practice git commands

 Repository Setup & Configuration
- git init – Initialize a new Git repository
- git clone <repo-url> – Clone an existing remote repository
- git config --global user.name "Your Name" – Set your Git username
- git config --global user.email "you@example.com" – Set your Git email

📦 Staging & Committing Changes
- git status – Check current changes and branch info
- git add <file> or git add . – Stage changes
- git commit -m "message" – Commit staged changes
- git commit -am "message" – Add and commit tracked files in one go

🔄 Syncing with Remote Repositories
- git remote add origin <url> – Link local repo to remote
- git fetch – Download changes from remote without merging
- git pull – Fetch and merge changes from remote
- git push – Push local commits to remote

🌿 Branching & Merging
- git branch – List branches
- git branch <name> – Create a new branch
- git checkout <branch> – Switch branches
- git merge <branch> – Merge another branch into current
- git rebase <branch> – Reapply commits on top of another branch

🧹 Undo & Cleanup
- git reset – Unstage changes
- git reset --hard <commit> – Reset to a specific commit
- git push origin <brach_name> --force -- to push the changes after hard reset
- git revert <commit> – Create a new commit that undoes changes
- git stash – Temporarily save changes
- git stash pop – Reapply stashed changes

📜 History & Inspection
- git log – View commit history
- git show <commit> – Show details of a specific commit
- git diff – See unstaged changes
- git blame <file> – See who last modified each line

These commands form the backbone of daily DevOps workflows—from managing infrastructure code to collaborating on deployment scripts. Want me to tailor a cheat sheet for your portfolio or CI/CD setup?