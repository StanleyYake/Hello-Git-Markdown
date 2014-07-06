	1.link a remote repository at the first time,type:'git remote add origin git@server-name:path/repo-name.git'
	2.after linked,'git push -u origin master' to push your master and the branch content.
	3.when you modified some file at the local,use 'git push origin master to apply the change.
	
###上传
'''
$ mkdir learngit
$ cd learngit
$ git init
$ git add readme.txt
$ git commit -m "wrote a readme file"
'''

###删除文件
'''
$ rm test.txt
$ git rm test.txt
$ git commit -m "remove test.txt"

    $ git checkout -- test.txt
'''
