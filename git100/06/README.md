# Git100 — Create branches

#### Purpose
This chapter aims to show how to create branches in a git repository

#### Description
Like in many other VCS _git_ can create branches, however it is more powerful in that it is simple to switch from a branch to another.

#### How do I create a branch?
It can be done with the command `branch`:

```
prompt> git branch my_branch
```

After typing this command you can simply type the following to list the available branches:

```
prompt> git branch
* master
  my_branch
```

As you can see in this example another branch called _master_ is already present. Actually, it is created at repository initialization and effective after the first commit.
The asteric **`*`** indicates that is it the branch you are currently working on.


#### Exercice
1. create a branch called _develop_
2. check that the branch has been created


