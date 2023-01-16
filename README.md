# Notes for Github usage

## Create Local branch

```sh
$ git checkout -b (brance-name)

# Example
# Jira ticket number
$ git checkout -b  eg-2000
```

### list all the branches and active one

```sh
$ git branch
```

### push local branch to remote branch

1. add update file
2. commit
3. push local branch to remote

```sh
$ git push -u origin eg-2000

```

### Merging locally

1. checkout master branch
2. git pull
3. merge to master

```sh
$ git merge  eg-2000 (branch to merge in)
```
