# mymemo


## pull request training

1. make test repository on GitHub
2. clone on the local machine with SourceTree
3. make new branch  
`$ git branch`
```
$ git checkout -b my-edit
$ git add mytext.md
$ git commit -m "Update README"
$ git push origin my-edit
```
with Haroopad, SourceTree
4. Push the new Branch to the origin  
`git push origin my-edit`
5. test a user request in your local machine  
```
$ git fetch
$ git branch -a
\* master
  remotes/origin/HEAD
  ..
$ git checkout -b my-edit origin/my-edit
```
6. Merge the pull request  
and delete the branch my-edit.
7. Pull master to the local.