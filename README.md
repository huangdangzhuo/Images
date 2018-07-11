网站图片链接

..或在命令行上创建一个新的存储库
echo“#git”>> README.md 
git init 
git add README.md 
git commit -m“first commit” 
git remote add origin git@github.com:huangangangzhuo/git.git
git push -u origin master
...或从命令行推送现有存储库
git remote add origin git@github.com:huangangangzhuo/git.git
git push -u origin master



git更新远程仓库代码到本地
　　1 使用命令查看连接的远程的仓库

　　　　git remote -v

　　2 远程获取代码

　　　　git fetch origin master

　　如果出现 Already up-to-date 说明代码更新好了

　　出现 FETCH_HEAD

　　使用命令 git merge FETCH_HEAD

　　3 当然 我们也可以git fetch origin master:temp建立新分支temp，将代码合并到新分支temp上，在删除新分支temp


