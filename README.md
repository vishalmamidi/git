# git

## login

```
git config --global user.email "mamidivishalsa@gmail.com"
git config --global user.name "vishalmamidi"
```

```
git config --global user.email "vishalmamidi1@gmail.com"
git config --global user.name "vishalmamidi1"
```


## Squash last N commits

```
git reset --soft HEAD~3 
git commit -m "new commit message"
```

```
git push --force-with-lease origin <branch-name>
```
above 3 indicates last 3 commits which will be squashed.

<https://stackoverflow.com/questions/5189560/how-do-i-squash-my-last-n-commits-together>



## logout
```
git config --global --unset user.name
git config --global --unset user.email
git config --global --unset credential.helper
```
or
```
git config --global --unset-all
```


## windows
```
remove from windows creds manager if windows.
change .gitconfig at home directory
```

## login
## windows 
open `credential manager` add `windows credential` 
network address: `github.com`
username: `vishalmamidi`
password: `PVC-token`
