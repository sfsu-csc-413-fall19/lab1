# Git lab instructions

## Basic commits
- Modify the output of the server to something new
- Add changes to staging `git add filename`
- Commit changes `git commit filename`
- Push `git push`

## Team commits
- Checkout new branch `git checkout -b yourname-yourfeature`
- Make changes in the output and push again
- Open pull request in git
- Switch back to master to simulate a conflict `git checkoout master`
- Push changes again on the same lines
- Switch back to your working branch `git checkout yourname-yourfeature`
- Pull changes `git pull origin master`
- Fix conflicts
- Make new commit and push
- Make a comment on github
- Merge PR