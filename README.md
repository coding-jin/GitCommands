Git Commands

### Creating a repository online for the <b>1st time</b>!

``` sh
$ touch README.md
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/coding-jin/GitCommands.git
$ git push -u origin master
# put in username&password
```

### When on adding on to your repository online with changes
``` sh
$ git add .
$ git commit -m 'what has changed'
$ git push
# put in username&password
```


### No more username password input for every push
``` sh
$ git remote set-url origin git@github.com:coding-jin/GitCommands.git
```
