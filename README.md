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
...或从另一个存储库导入代码
您可以使用Subversion，Mercurial或TFS项目中的代码初始化此存储库。
