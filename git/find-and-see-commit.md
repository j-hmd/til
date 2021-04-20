# How to find and see a commit diff

1. To search for a commit:

`git log --grep=[pattern]`

2. Which results in: 

````
commit 50d5985ee85ca0682d4a27ec5f9d08118cae7023
Author: ****
Date:   Sat Dec 30 19:15:09 2017 -0700

    added instructions for how to add git-hook for auto-generation of readme
````

3. Copy part of the commit number and get the diff:

`git show 50d5985ee`

