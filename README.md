Description
======
A pseudo art project to retroactively chronicle the progress of my career through a versioned résumé using Github for versioning and some little Git tricks to fake the commit dates.

Implementation
-----
To backdate a Git commit simply amend the commit before you push: `GIT_COMMITTER_DATE="Thu Jan 27 14:01 2000 +0000" git commit --amend --date="Thu Jan 27 14:01 2000 +0000"`