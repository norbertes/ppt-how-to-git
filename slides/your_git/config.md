###### config

    ⇒  cat ~/.gitconfig
    [user]
    	name = Norbert Sienkiewicz
    	email = norbert.sienkiewicz@gmail.com
    [credential]
    	helper = osxkeychain
    [push]
    	default = simple
    [core]
    	excludesfile = ~/.gitignore
    	editor = nano
    	pager = diff-highlight | diff-so-fancy | less --tabs=1,5 -R
    [rerere]
    	enabled = true
    [color "diff-highlight"]
    	oldNormal = red bold, oldHighlight = red bold 52
    	newNormal = green bold, newHighlight = green bold 22
    [alias]
      lg1 = [loooooong stuff]

Note:
git config --global rerere.enabled true
