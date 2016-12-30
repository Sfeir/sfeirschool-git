# Git 100 — Save changes

### Purpose
This chapter aims to show how to save a change and stored it in the git repository.

#### How to save my changes?
This can be achieved via the `commit` command as follows:

```
prompt> git commit
```

By executing this command _git_ will call the default editor, you will be invited to enter a commit message.
This message must have at least one line.

> **Note:** have good maners and enter first a first short sentence to indicate the purpose of the commit, then enter a blank line and enter a description of the commit (content, motivation and so on)

#### Can't I enter directly the commit message through the command?
Yes, you can do it. You need to append the `-m` option followed by the commit message between ouble quotes `"` or single quotes `'`.

```
prompt> git commit -m "Initial commit"
```

When this is done _git_ states it like follows:


```
[master (root-commit) fd6f671] Initial commit
 1 file changed, 1 insertion(+)
 create mode 100644 file.txt
```


#### Exercice
1. save the changes you've made before



