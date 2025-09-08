# ! [remote rejected] master -> master (push declined due to repository rule violations)
      reason was due to PAT token save in this file ,   not able to solve  the issue so  cleared all past commit
        - git checkout --orphan clean-slate   : This starts a fresh history with no commits:
        - git add .
        - git commit -m "Initial clean commit"
        - git branch -D master    : delete old branch
        - git branch -m master
        - git push origin master

# after pull ; fatal: refusing to merge unrelated histories : want to merge the remote and local histories (even though they’re unrelated), you can override the protection:
    git pull origin master --allow-unrelated-histories

