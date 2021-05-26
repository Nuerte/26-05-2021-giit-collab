19  git status
  520  git add README.md 
  521  git commit -m "Switch/checkout new branch in 1 step"
  522  git status
  523  git log --oneline --graph --all
  524  git push origin my_first_branch
  525  git switch main
  526  git log --oneline --graph -all
  527  git log --oneline --graph -all
  528  git log --oneline --graph --all
  529  git pull origin main
  530  git log --oneline --graph --all
  531  git fetch --prune
  532  git log --oneline --graph --all
  533  git branch -d my_first_branch
  534  git log --oneline --graph --all
  535  git fetch --prune
  536  git pull origin main
  537  git status
  538  git log --oneline --graph --all
  539  git swtich -c feature1
  540  git switch -c feature1
  541  nano README.md 
  542  git switch main
  543  git switch -c feature2
  544  nano README.md 
  545  git switch feature1
  546  git status
  547  git add README.md 
  548  git commit -m "Log and fetch"
  549  git log --oneline --graph --all
  550  git switch main
  551  nano README.md 
  552  git switch  feature2
  553  nano README.md 
  554  cat README.md 
  555  git log --oneline --graph --all
  556  git status
  557  git switch feature1
  558  git stash
  559  git log --oneline --graph --all
  560  git switch feature1
  561  cat README.md 
  562  git switch feature2
  563  git stash list
  564  nano README.md 
  565  git stash apply
  566  nano README.md 
  567  git status
  568  git add README.md 
  569  git commit -m "Branch -d|-D"
  570  git log --oneline --graph --all
  571  git stash clear
  572  git log --oneline --graph --all
  573  git push origin feature2
  574  git push origin feature1
  575  git log --oneline --graph --all
  576  git switch main
  577  git pull origin main
  578  git log --oneline --graph --all
  579  cat README.md 
  580  git switch feature2
  581  cat README.md 
  582  git switch feature2
  583  git rebase main
  584  cat README.md 
  585  git log --oneline --graph --all
  586  git push origin feature2
  587  git push -f origin feature2
  588  git switch main
  589  git pull origin main
  590  git fetch --prune
  591  git branch -d feature1 feature2
  592  git log --oneline --graph --all
  593  git switch -c c1
  594  nano README.md 
  595  cat README.md 
  596  git add README.md 
  597  git commit -m "c1 titles"
  598  git log --oneline --graph --all
  599  nano README.md 
  600  git add README.md 
  601  git commit -m "git rebase"
  602  git push origin c1
  603  git switch main
  604  git switch -c c2
  605  nano README.md 
  606  nano README.md 
  607  git add README.md 
  608  git commit -m "c2 title changes"
  609  nano README.md 
  610  git add README.md 
  611  git commit -m "c2 conflict note"
  612  git push origin c2
  613  git switch main
  614  git log --oneline --graph --all
  615  git  fetch --prune
  616  git log --oneline --graph --all
  617  git reset --hard 4acdc06
  618  git log --oneline --graph --all
  619  git switch c2
  620  git rebase main
  621  git rebase --abort
  622  git rebase main
  623  nano README.md 
  624  git add README.md 
  625  git rebase --continue
  626  git status
  627  nano README.md 
  628  git add README.md 
  629  git rebase --continue
  630  git commit -m "Fixed rebase conflicts"
  631  git push origin c2
  632  git push --force-with-lease origin c2
  633  git switch main
  634  git fetch --prune
  635  git branch -d c1 c2
  636  git log --oneline --graph --all
  637  git pull origin main
  638  git fetch --prune
  639  git branch -d c1 c2
  640  git log --oneline --graph --all
  641  history
