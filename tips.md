1.link a remote repository at the first time,type:`git remote add origin git@server-name:path/repo-name.git`
2.after linked,`git push -u origin master` to push your master and the branch content.
3.when you modified some file at the local,use `git push origin master` to apply the change.

$ ssh-keygen -t rsa -C "youremail@example.com"	
###上传
```
$ mkdir learngit
$ cd learngit
$ git init
$ git add readme.txt
$ git commit -m "wrote a readme file"
```

$ git remote add origin git@github.com:StanleyYake/learngit.git

$ git push -u origin master第一次

$ git push origin master此后都可以用这句

**注意**
> 这里的origin是指的remote branch 的默认名字

> 等于git push origin master：master

> 更一般的 git push origin master：/src/hello

> 它表示在local 寻找名为master的branch，用它去更新remote下名为hello的branch.

###删除文件
```
$ rm test.txt
$ git rm test.txt
$ git commit -m "remove test.txt" 

    $ git checkout -- test.txt 撤销
```
###版本回退
```
$ git log --pretty=oneline
$ git reset --hard 3628164
$ git reflog

```
###撤销修改
```
$ git checkout -- readme.txt

$ git reset HEAD readme.txt  撤销已经add到暂存区的更改，移除暂存区
$ git checkout -- readme.txt

```
###分支创建与合并
```
$ git checkout -b dev创建并转到，相当于$ git branch dev和$ git checkout dev
$ git branch
$ git add readme.txt 
$ git commit -m "branch changed"
$ git checkout master
$ git merge dev  合并某分支到当前$ git merge --no-ff -m "merge with no-ff" dev会留下合并历史no “Fast forward”
$ git log --graph --pretty=oneline --abbrev-commit
$ git branch -d dev
$ git branch
```
