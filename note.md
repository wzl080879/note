一、git是什么
git是开源分布式的版本控制技术
github是一个利用git技术的开源托管平台

代码托管平台：github，码云，gitlab等

区分：git和github关系

分布式(git)，集中式（SVN）

分布式：没有中心，可以在本地独立完成，不依赖其他服务器
集中式：必须有一个核心服务器，如果核心服务坏掉，那整体网瘫痪

二、git具体怎么玩？
1.先安装一个git软件（也称git控制台）
 windows git软件下载地址：https://git-scm.com/download/win

2.检测是否安装好git
  右侧--查看一下是否有git bash
复制代码
3.创建一个项目文件夹，例如：1906pro
4.进入项目文件夹，输入git init 进行git初始化
5.就可以在git的世界尽情玩起来
window命令方式查看文件：dir
清屏：cls

mac查看文件：ls  -al 查看隐藏文件
清屏：clear

三、git文件管理命令
查看文件状态：git status
将文件添加到暂存区：git add 目录名或要添加的文件名
将暂存区的内容提交：git commit -m '提交说明'

如果查看提交信息：git log或git reflog

 git日志简化，在一行显示：git log --pretty=oneline

 如果首次安装git，使用时需要配置git用户名和git邮箱

 配置用户名： git config --global user.name '你的用户名'
 配置邮箱：git config --global user.email '你的用户名'

 查看配置信息：git config --list

注意：git管理的不是文件，管理的是”修改“