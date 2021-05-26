# 26/05/2021 Git Collaboration
- `git clone <URL>` : Downnloads repo to current directory

## Branches

- `git branch <NAME>` : Creates new branch with <NAME> 
- `git branch -a` : lists all braches
- `git branch -d <NAME>` : deletes the brannch <NAME>
    `git branch -D <NAME>`: forced delete of <NAME>
- `git checkout <NAME>` : switch to branch <NAME>
    - `git switch <NAME>` : same, but in newer git versions

- `git switch -c <NAME>` : create and swithc to branchj 1 command
    - `git checkout -b <NAME>`: same but using checkout

- `git log --oneline --graph --all` : show you giit history

## Pull requests

- Also see branch delete above
- `git fetch --prune` : clean up git history in regards to hub
- `git branch -d <NAME>` : delete branch

## Conflicts

- `git rebase <BRANCH>` : e.g. <main> will update current position to main branch
