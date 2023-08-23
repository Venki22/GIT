### Rebase:
With the rebase command, you can take all the changes that were committed on one branch and replay them on a different branch
### How Git performs rebase?
- Pointer goes to the common ancestor of the two branches(the one you'reon and the one you're rebasing onto).
- Gets the differnece introduced by each commit of hte branch you're on.
- Saving those diffs to temporary files.
- Resetting the current branch to the same commit as the branch you are rebasing onto.
- Finally applying each change in turn

Key points on Rebasing
No difference in the end product of the integration.
but rebasing makes for a cleaner history.

The log history looks like a linear history: it appears that all the work happened in series,even when it originally happend in parallel
Often,you'll do this to make sure your commits apply clenly on a remote branch.

One point of view is commit history is a record of what actually happened
The opposing point is the commit history is the story of how your project was made

git rebase master

git log --oneline --graph --all

git merge feature

git log --oneline --graph --all