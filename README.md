# Louplus
<h2>将本地的项目上传至github</h2>
<p>1.首先登录到github创建一个分支</p>
<p>本地操作，将入到项目目录（例如：cd dpp-vote投票系统）打开git操作命令窗口，鼠标右键选择Git Bash Here

    1）、将git初始化至该目录下，会生成.git配置文件，执行命令：git init

    2）、将远程的仓库分支来取到本地，执行命令：git remote add origin http://gitlab.com/dangjian/dpp-mobile.git

    3）、将本地的修改提交到暂存区（注add后面接着一个点），执行命令：git add .

    4）、将暂存区里的改动给提交到本地的版本库，执行命令：git commit -m "备注内容" 

    5）、将本地的版本库分支推送到远程服务器上对应的分支，执行命令：git push -u origin master
