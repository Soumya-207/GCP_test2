# GCP_test2
Test repo for GCP TF

Command,Purpose
git status,"See which files are changed, staged, or untracked."
git add .,Stage all changes for the next commit.
"git commit -m ""feat: add VPC module""",Save your staged changes locally with a message.
git log --oneline,"View a clean, one-line history of your commits."
git diff,See exactly what lines you changed but haven't staged yet.

Command,Purpose
git fetch origin,"Update your local list of branches from GitHub (Fixes ""invalid reference"")."
git pull origin dev,Download and merge updates from the remote dev branch.
git push origin dev,Upload your local commits to the dev branch on GitHub.
git switch dev,Switch to an existing branch.
git switch -c feature-name,Create a new branch and switch to it immediately.
git branch -a,List all branches (local and remote).

Command,Purpose
git stash,"Temporarily ""hide"" your uncommitted changes so you can switch branches."
git stash pop,Bring your hidden changes back.
git reset --hard HEAD,Dangerous: Discard all local changes and go back to the last commit.
git commit --amend,Fix the message or files of your very last commit (before pushing).
git remote -v,Verify which GitHub URL your local project is connected to.