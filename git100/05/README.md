# Git100 — Display a commit

#### Purpose
This chapter aims to show how to display information about a commit in a git repository.

#### How to display a commit?
This can be accomplished through the command `log` as follows:

```
prompt> git log
```

This command results in the display of the successive commits information. Thus, it prints out:

  * the commit identifier
  * the author's name and email address
  * the date of the commit
  * the commit message

The commits information is displayed from the youngest commit (top one) to the oldest (bottom one)

#### Is it possible to list commit given a particular criterion?
Yes, it is. `log` command has various options that can be added to it for:

  * showing a graph of the commit
  * displaying a number of commits
  * filtering commits by date
  * listing contained files


#### Exercice
1. display the commit message
2. display the file(s) contained by a commit
   **Hint:** use `--help` option to find right option


