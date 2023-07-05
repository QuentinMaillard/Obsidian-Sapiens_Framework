⬆️ up :: [[210. Coding]]

🏷️ tags :: #index/embodiment 

---

1. Initialization:
    
    - Initialize a new repository: `git init`
    - Clone a repository: `git clone [repository URL]`
2. Configuration:
    
    - Set username: `git config --global user.name "[username]"`
    - Set email: `git config --global user.email "[email]"`
3. Basic Commands:
    
    - Check repository status: `git status`
    - Add changes to the staging area: `git add [file]` or `git add .` (for all files)
    - Commit changes: `git commit -m "[commit message]"`
    - Push changes to a remote repository: `git push [remote] [branch]`
4. Branching:
    
    - Create a new branch: `git branch [branch-name]`
    - Switch to a branch: `git checkout [branch-name]`
    - Create and switch to a new branch: `git checkout -b [branch-name]`
    - Merge branches: `git merge [branch-name]`
5. Remote Operations:
    
    - Add a remote repository: `git remote add [remote-name] [remote-url]`
    - List remote repositories: `git remote -v`
    - Fetch changes from a remote repository: `git fetch [remote]`
    - Pull changes from a remote repository: `git pull [remote] [branch]`
6. History and Changes:
    
    - Show commit history: `git log`
    - Show changes between commits: `git diff [commit1] [commit2]`
    - Discard local changes: `git checkout -- [file]`
7. Collaboration:
    
    - Create a new branch from a remote branch: `git checkout -b [local-branch] [remote]/[remote-branch]`
    - Push a local branch to a remote repository: `git push -u [remote] [local-branch]`