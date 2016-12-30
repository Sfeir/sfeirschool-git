# Git100 — More about branches

#### Description
You've learnt to create a branch in the previous chapter using the `branch` command. Here you will have additional information.

#### How can I switch from a branch to another one?
This is accomplished through the `checkout` command:

```
git checkout my_other_branch
```

By typing this you will be placed on the "my_other_branch" branch. Now if you type in the `branch` command alone you will remark that the **`*`** is placed in front of the chosen branch.


#### Is it possible to create a branch and switch to it directly?
Yes it is and very simple:

```
git checkout -b my_other_branch
```

The `-b` option will create the indicated branch.


#### I mispelled my branch, how can I rename it?
This is accomplished through the `branch` command and its `m` option:

```
git branch -m old_name new_name
```

By typing this, the first mentioned branch will be renamed to the _new_name_.


### I don't need my branch anymore, how can I delete it?
This is accomplished through the `branch` command and its `-d` option:

```
git branch -d branch_to_delete
```

> **Note:**
  this applies to a fully merged branch
  to force the deletion use the option `-D`


#### Exercices
1. switch between your available branches
2. create a branch and switch to it directly
3. rename a branch among the ones you have


