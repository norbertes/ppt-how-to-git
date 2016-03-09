###### git commit-tree

git reset $(git commit-tree HEAD^{tree} -m "commit message")

Note:
- Squash all commits into one
- commit-tree:
  - creates tree based on provided tree object
  - This is usually not what an end user wants to run directly
- HEAD^{tree} - tree object
