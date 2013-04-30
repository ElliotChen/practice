practice
========

practice git

git rebase -i @{u} before git push
(on “feature”) git merge master to make feature compatible with latest master
(on “master”) git merge --no-ff feature to ship a feature
However if “feature” contains only 1 commit, avoid the merge commit:
(on “master”) git cherry-pick feature
