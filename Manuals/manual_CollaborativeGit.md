# Freewheelin' Git Manual

```python
''''
The copyright always belongs to Freewheelin'.

Sharing is forbidden.

Author: Zihan Zhou, Pangyu Li
Date: 01-12-2022
''''
```



## Initialize the Repo

* If you have existing codebase, create the repo on github and pull it to your local directory.

```sh
$pwd
/codebase
$git init
$git remote add <alias> <URL.git>
$git pull <alias> master
```

* Now you have an empty *master*, add existing codes into your master.

```shell
$git add .
$git commit -m "comment_string"
```

* Create a *dev* branch and merge it with the *master*, now they are the same.

```sh
$git checkout -b dev
$git merge master
$git push origin dev
```

* Now back to GitHub, using the pull request to merge the *master* with the newly added *dev*.



## Collaborative

> Pricinple: always use your local <tmp> branch to commit changes, once you finished your part push your local branch<tmp> to the Github branch with the same name. Then create a pull request to merge the *dev* branch with the <tmp> branch. Finally, delete the <tmp> branch on Github.

+ If there is no local <tmp> branch, create one <tmp> branch locally. All changes should be done in this branch.

```sh
$git checkout -b <tmp>  # recommended to name the branch with your personal name
```

+ Before your any code editing, pull the latest version from the Github *dev* branch to your 

```sh
$git pull <alias> master
```

+ After all changes to the codebase, add the changes to your local git repo and then push it to the remote repo.

```sh
$git add .
$git commit -m "comment_string"
$git push origin <tmp>
```

+ Lastly, create a pull request to merge the *dev* branch with the <tmp> branch.
