将本地项目推送至远程 git 库

进入项目根目录：  .../Spring
执行初始化 git 命令：git init
将本地文件索引添加至 git 库：git add *
将本地文件提交到本地 git 库：git commit -m "first commit"
查看本地 git 库中的分枝：git branch
将本地 git 库与远程 git 库关联：git remote add origin https://github.com/BrightBi/SpringMVC.git
                        或者 git remote add origin git@github.com:BrightBi/SpringMVC.git
将本地 git 库推送至远程 git 库：git push -u origin master
可能需要输入密码和账号，对应输入远程 git 库的 密码和账号即可。
