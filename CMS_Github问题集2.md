# 问题集2

1. 个人主页上的“+”下拉菜单可创建的四种类别分别有？分别的意思？
2. 如何能将仓库中的html文件直接解析成页面？
3. 如何删除仓库
4. Bash是什么操作系统的命令
5. Pwd是什么命令
6. Cd是什么命令
7. Echo是什么命令
8. 配置git用户名的命令
9. 配置邮箱的命令
10. 命令行换行方式
11. 命令行终结方式
12. 使用命令行比GUI方式有何优势
13. 提交到本地仓库时为什么有暂存区
14. 新建代码仓库的命令
15. git clone [url] 这个命令的作用是
16. 添加指定文件到暂存区的命令
17. 删除工作区文件，并且将这次删除放入暂存区的命令
18. 改名文件，并且将这个改名文件放入暂存区的命令
19. 提交暂存区到仓库的命令
20. 直接从工作区提交到仓库的命令
21. 显示变更信息的命令
22. 查看历史信息的命令
23. Commit的意义是
24. Pull的意义是
25. Push的意义是

### ---答案
1、new repository创建仓库
import repository导入库
new gist创建代码片段
new organization创建组织
2、在仓库里找到create new file，文件名后缀为.html，然后再在仓库中的
settings中找到GitHub Pages 将sourse中的None改为master branch，save
在点击给出的网址，后面加上文件名
3、settings中最下面，Danger Zone中有Delete this repository
4、Bash是Linux操作系统的命令
5、Pwd是打印当前工作目录
6、cd 改变目录
7、Echo是在命令行打印信息
8、配置git用户名的命令是 git config --global user.name "李亚欣"
9、配置邮箱的命令是 git config --global user.email "563294284@qq.com"
10.\
11.Ctrl+C
12.
使git能够发挥强大功能的最佳方式
可以方便的查看每个仓库的状态
可以写批处理 一次性建多个文件夹
复杂的命令很容易完成
13.控制提交的颗粒度，可以保证返回到合适的版本
工作区 仓库 中间有暂存区  工作区中对于之前的文档有10个变动  可以将10个变动一起放到暂存区中
可以选择将10个变动全都commit上去  也可以自己选3+4+3（相当于三个版本） 可以根据自己的需求划分几个版本
14.git init
github-create repo_name
15.将URL地址的远程版本库克隆在本地
16.git add
17、git rm [file1] [file2]...
18、git mv 原文件 改名文件
19、git commit -m [message]
20、git commit -am [message]
21、git status
22、显示当前分支的版本历史 git log
23、commit推送修改到本地库中
24、pull 取回远程主机某个分支的更新，再与本地的指定分支合并
25、push 用于将本地分支的更新，推送到远程主机
