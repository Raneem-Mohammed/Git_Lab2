-Tell me how to remove them locally and remotely.
locally:
    git branch -d dev
    git branch -d test

remotely : 
    git push origin :dev
    git push origin :test




-Tell me how to checkout another branch without commit changes 
    git stach

-Tell me how to list tags
    git tag



-Tell me how to delete tag locally and remotely
locally:
    git tag -d v1.7
remotely:
    git push origin --delete v1.7


-Add an image in the README.md file
![Git logo](lab2/cosmo.png)