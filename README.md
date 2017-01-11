# gitlearn
learn git
config your git,three level
1.system level
    ```git config --system ... ```which config file /etc/gitconfig
2.global level
    ```git config --global ... ```~/.gitconfig

3.project level
    ```git config ... ``` .git/config

you can edit those files to directly change the values
you can access those values by :
    ```git config --global user.email``` like this

chapter 5

fix confict is easy
but sometimes
fix confict is hard
i dont konw how to fix it 

use fetch to fetch changes to responsity first,then merge to your workplace

```git fetch origin branch``` fetch origin branch to local responsity
```git diff local_branch origin/branch``` diff 
```git merge origin/branch``` merge remote branch to local branch
