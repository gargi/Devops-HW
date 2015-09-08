
# Level 1.1   
```
git commit
git commit
```

# Level 1.2
```
git branch bugFix
git checkout bugFix
```

# Level 1.3
```
git checkout -b bugFix
git commit
git checkout master
git commit
git merge bugFix
```

# Level 1.4
```
git checkout -b bugFix
git commit
git checkout master
git commit
git checkout bugFix
git rebase master
```

# Level 2.1
```
git checkout c4
```

# Level 2.2
```
git checkout bugFix^
```

# Level 2.3
```
git branch -f master C6
git checkout HEAD~1
git branch -f bugFix HEAD~1
```

# Level 2.4
```
git reset HEAD~1
git checkout pushed
git revert HEAD
```
