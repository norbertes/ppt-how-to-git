###### other commands
    git stash
    git fsck --unreachable
    git-gc
    git filter-branch <rev-list options>

Note:
  1. stash takes unindexed files into 'stash'
  2. file system check - for validation
  3. Cleanup unnecessary files and optimize the local repository
  4. Lets you rewrite Git revision history by rewriting the branches mentioned in the `<rev-list options>`, applying custom filters on each revision. Those filters can modify each tree (e.g. removing a file or running a perl rewrite on all files) or information about each commit. Otherwise, all information (including original commit times or merge information) will be preserved.
