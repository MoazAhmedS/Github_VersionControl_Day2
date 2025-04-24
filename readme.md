# Day 2 Assignment 
> Tell me how to remove them locally and remotely
>> To remove a file locally and remotely 
>> 1. Use the command `git branch -d dev` to remove the branch localy.
>> 2. Use the command `git push origin :dev` to remove the branch remotely.

> Tell me how to checkout another branch without commit changes
>> To checkout another branch without commit changes, we can use the command `git stash` to save the changes temporarily.
>> After that, we can use the command `git checkout dev` to switch to another branch.
>> And at the end, we can use the command `git stash pop` to apply the changes back to the working directory.
