
```
ensure that the repository is not currently on the branch to be deleted
1-delete branch locally
git branch -d branch-to-delete
2-delete branch remotely
git push remote-name --delete branch-to-delete
annotated tags vs lightweights tags
Annotated tags are full objects in Git's database. They contain metadata such as the tagger's name, email, date, and a message.
git tag -a v1.0 -m "Release version 1.0"
lightweight tags Lightweight tags are simply pointers to a specific commit. They do not contain any additional metadata.
when to use rebase:
Keeping Feature Branches Updated:
git checkout feature-branch
git rebase main


git tag v1.0
when to use rebase:
how to list tags:
git tag
Delete a Local Tag: git tag -d tagname
Delete a remote Tag: git push --delete remote-name tagname
```