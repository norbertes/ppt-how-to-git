###### git commit

    git commit
    git commit -am "message here"
    git commit --amend
    git commit --allow-empty

Grabs ours indexed changes into a "snapshot"

    ⇒  git commit -m "commit message goes here"
    [gh-pages 0cf3d43] commit message goes here
     7 files changed, 23 insertions(+), 3 deletions(-)
     create mode 100644 pic/git_tree.png
<!-- .element: class="fragment" data-fragment-index="3" -->

Note:
  * -a adds and removes all known files to stage
  * after amend you need to push -f (which is not bad at all) - I do it several times per day (will explain later Y)
  * --allow-empty is great to trigger some eg CI like jenkins
