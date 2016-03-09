###### git reset
    git reset <paths>
- opposite to git add


    git reset [mode] <commit>
mode: mixed, soft, hard
- soft doesn't touch added files
- mixed (default) - touch index but not working tree
- hard removes all changes made since `<commit>`
