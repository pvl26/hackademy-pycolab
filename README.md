g p gg# Python 101 Git Workshop

## SSH Key generation
Generate key with ```ssh-keygen -t rsa``` Press enter to select defaults.

Print the public key:

```
cat ~/.ssh/<key_name>.pub
```

## Git global setup
```
git config --global user.email "you@example.com"
git config --global user.name "Your Name"
```

## Clone repo
```
git clone <repo_link>
```

## Branch
* ```git branch``` Your current branch.
* ```git branch <user-id>/<feature-name>``` Create branch `<user-id>/<feature-name>`.
* ```git checkout pretty``` Move to `pretty` branch.
* ```git checkout -b awesome``` Create a new `awesome` branch and move there.


### Warnings
* Please use `<user-id>/<feature-name>` for branch names. Example: `lolteanu/fix-all-bugs`. **Thanks!**

* Make sure you are **NEVER** on `main` when writing code.


## Create commit
* ```git status``` View uncommitted and committed changes in files (red and green, respectively).

* ```git add .``` Add all changes.

* ```git commit -m "Create an awesome change"``` Commits changes with message.

* ```git log``` Show commit history.

## First changes
* ```git push origin pretty``` Push changes from `pretty` branch.
* ```git pull origin main``` Make sure you are on the `main` branch when pulling! 
