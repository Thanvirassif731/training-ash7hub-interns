# Git & GitHub Commands

## Git Workflow
Unstagged -> Stagged -> Commit -> Repo Push

## Git Commands that I have learned so far:
* git init 
* git config --global user.name [username]
* git config --global user.email [user-email@gmail.com]
* git clone [repo-url]
* git status

## Open Default Editor as VS Code
* git config --global core.editor "code --wait"
* git config --global -e -- To Verify the settings

## Stages:
1. Unstaged
2. Staged
3. Committed
4. Pushed to Github

## Common Workflow Commands:
* git add [filename]
* git commit -m "YOUR COMMENTS"
* git push

## Branch & Checkout:
* git branch
* git branch [branch-name] -- Only create branch
* git checkout -b [branch-name] -- Create branch and checkout
    - Both branch and checkout -b are same for creating branch
* git checkout [branch-name]
* git branch -d [branch-name] -- Delete branch

## Merge Command:
* git merge [branch-name]

## Pull Command:
* git pull
* git pull origin [branch-name]

## Additional Commands
### To check the configuration File of Git
- View in **Windows:**
    * notepad $env:USERPROFILE\.gitconfig
- View in **Linux:**
    * cd ~
    * cat .gitconfig