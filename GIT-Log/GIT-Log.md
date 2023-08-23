# GIT-Log Commands
## List of commmands 
- Display the entire commit history using the default formatting. If the output takes up more than one  screen, you can use Space to scroll and q to exit.

### Date range
```
git log
git log -2
git log --after <"YYYY-MM-DD">  before <"YYYY-MM-DD">
git log --before "YYYY-MM-DD"
git log --after "YYYY-MM-DD"
git log --committer name
git log --author name
git log --author="author name" file-name
```

### Commit by x days ago
```
git log --after 2.days.ago
```

### To view summary of changes to each commit
```
git log --stat
```

### To view one line per commit
```
git log --oneline
git log --oneline --graph --all
git log --graph
git log --pretty=format:"Commit Hash: %H, Author: %aN, Date: %aD"
```

### View All Diff of Changes for Each Commit
```
git log -p 
```

### This command shows the file differences which are not yet staged.
### This command shows the differences between the files in the staging area and the latest version present.
```
git diff
git diff first-branch second-branch

git commit --amend
git commit –-amend  -m "commit message"
git reflog
git reflog HEAD@{n}
git reflog HEAD@{1.days.ago}
git reflog HEAD@{2.weeks.ago}
git reflog --pretty --oneline
git diff HEAD@{3} HEAD@{6}
git diff HEAD@{1.min.ago} HEAD@{2.weeks.ago}

        


