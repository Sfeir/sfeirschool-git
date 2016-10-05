# Git 100 — Query the repository state

### Purpose
This chapter aims to show how the state of the repository can be queried

#### How to query the repository state?
This can be accomplished with the `status` command as follows:

```
prompt> git status
On branch master 

Initial commit

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)

	new file:   file.txt

```

In this case git indicates us that a new file has been added it also let us
know how we can cancel the addition of the file so that it won't be committed


##### Exercice
1. check that the file you've added before is mentionned by the `git status` command
2. use the indicated command to remove the file from the index
3. retype `git status` and observe what git says
4. add the file back to the index


