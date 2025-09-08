# git init
# ls -a                                      : show all hidden files
# ls .git                                    : inside .git folder
# touch name.txt
# git status
# git add .                                   : put all untracked files in staging area
# git commit -m "message"
# vi name.txt                                 : edit in file
# cat name.txt                                : show file data
# git restore --staged name.txt               : This unstage the file name.txt from the Git staging area if not commit yet
git config --global user.name               : to check username
git log                                     : commit history
rm -rf name.txt                             : -r : remove directories and its contact ; -f: forcefully  ; command : delete file
git reset commit_id                         : if mistakenly done commit and want to restore then check git log and get commit id , if 3 commits and want to delete
git stash                                   : rather doing commit , do stash then code we want in temporary basis will be at somewhere ,we have code and we donot want to make commit and when git status then it will not show any commit
                                            : first do some change and git add . then rather than commit do git stash . it will not commit code and don't create log
git stash pop                               : if we want to the file changes in stash to commit means come from background to commit state
git stash clear                             : if donot want to stash changes
git remote add origin https://github.com/sharma1698/git-command.git                           : add git repository to our local project  ; create repo at github then copy url and add in command ; here origin is name of url
# git remote -v
    show all url (remote repository) attach to current project
# git push origin branchname : here origin is https://github.com/sharma1698/git-command.git
# git log --oneline  :
        check commit history


