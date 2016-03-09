###### strange notation
    git checkout HEAD~2
    git checkout HEAD^2
    git checkout HEAD~3^2

Note:
Shorthand for specifing previous commits without having hash
~n: n comments before HEAD
^n: n means which parent (remember commits have at least two parents: merged-into and 2nd commit which was merged). There might be more parents with octopus merges.
