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
git log 2.days.ago
```

### To view summary of changes to each commit
```
git log --stat
```

### To view one line per commit
```
git log --oneline
git log --oneline --graph --all
```