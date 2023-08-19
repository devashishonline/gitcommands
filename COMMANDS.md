# Git Commands Cheat Sheet

## Configuring Git

- Configure your name: `git config --global user.name "Your Name"`
- Configure your email: `git config --global user.email "your.email@example.com"`
- Set your preferred text editor: `git config --global core.editor "editor-command"`

## Creating Repositories

- Initialize a new repository: `git init`
- Clone a repository: `git clone <repository-url>`

## Basic Workflow

- Check the status of your repository: `git status`
- Add changes to the staging area: `git add <file>`
- Remove changes from the staging area: `git restore --staged <file>`
- Commit changes: `git commit -m "Commit message"`
- Push commits to a remote repository: `git push <remote-name> <branch-name>`
- Pull changes from a remote repository: `git pull <remote-name> <branch-name>`

## Branching and Merging

- Create a new branch: `git branch <branch-name>`
- Switch to a branch: `git checkout <branch-name>`
- Create and switch to a new branch: `git checkout -b <branch-name>`
- Merge branches: `git merge <branch-name>`
- Delete a branch: `git branch -d <branch-name>`

## Remote Repositories

- Add a remote repository: `git remote add <remote-name> <remote-url>`
- List remote repositories: `git remote -v`
- Fetch changes from a remote repository: `git fetch <remote-name>`
- Pull changes from a remote repository: `git pull <remote-name> <branch-name>`
- Push commits to a remote repository: `git push <remote-name> <branch-name>`

## Stashing Changes

- Stash changes: `git stash`
- Apply stashed changes: `git stash apply`
- List stashes: `git stash list`
- Clear stashes: `git stash clear`

## Viewing History

- View commit history: `git log`
- View changes in a commit: `git show <commit-hash>`
- View changes between commits: `git diff <commit1> <commit2>`
- View changes in the staging area: `git diff --staged`

## Undoing Changes

- Discard local changes in a file: `git restore <file>`
- Restore a file to a specific commit: `git checkout <commit-hash> <file>`
- Revert a commit: `git revert <commit-hash>`
- Reset to a specific commit: `git reset --hard <commit-hash>`

## Tagging

- Create a tag: `git tag <tag-name>`
- Create an annotated tag: `git tag -a <tag-name> -m "Tag message"`
- List tags: `git tag`
- Push tags to a remote repository: `git push <remote-name> --tags`

## Git Configuration

- Show Git configuration: `git config --list`
- Show repository-specific configuration: `git config --local --list`
- Show global configuration: `git config --global --list`

## More Help

- Get help on a specific command: `git help <command>`
- Get help on Git usage: `git help -g`

---

### Comprehensive Git Commands Cheat Sheet

## Configuration

- Set your name: `git config --global user.name "Your Name"`
- Set your email: `git config --global user.email "your.email@example.com"`
- Configure default text editor: `git config --global core.editor "editor-command"`
- Configure line ending settings: `git config --global core.autocrlf <true/false/input>`

## Repository Initialization

- Initialize a new repository: `git init`
- Clone a repository: `git clone <repository-url>`

## Basic Workflow

- Check repository status: `git status`
- Stage changes: `git add <file>`
- Unstage changes: `git restore --staged <file>`
- Commit changes: `git commit -m "Commit message"`
- Push commits to a remote: `git push <remote-name> <branch-name>`
- Pull changes from a remote: `git pull <remote-name> <branch-name>`
