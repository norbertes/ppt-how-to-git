###### tags

creation

    git tag -a 0.1.3 -m "my description"


pushing

    git push origin 0.1.3


list

    git tag -l


lookup

    git show 0.1.3


checkout (you cant override tag, so you have to create new branch)

    git checkout -b version2 0.1.3
