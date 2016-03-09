###### git fetch
  But wait? Whats the origin?

  <!-- .element: class="fragment" data-fragment-index="0" -->
    git clone -o foo https://github.com/norbertes/ppt-how-to-git.git

  <!-- .element: class="fragment" data-fragment-index="1" -->
    ⇒  cat ./.git/config
    [core] ...
    [remote "foo"]
    	url = https://github.com/norbertes/ppt-how-to-git.git
    	fetch = +refs/heads/*:refs/remotes/foo/*
    [branch "master"]
    	remote = foo
    	merge = refs/heads/master

  <!-- .element: class="fragment" data-fragment-index="2" -->
    git fetch -va === git fetch foo -va

  <!-- .element: class="fragment" data-fragment-index="3" -->
    ⇒  git fetch origin -va
    fatal: 'origin' does not appear to be a git repository
    fatal: Could not read from remote repository.

    Please make sure you have the correct access rights
    and the repository exists.

Note:
  - 'origin and master' doesnt have any special meaning in git
