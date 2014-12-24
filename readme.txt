1、windows平台下载地址
   http://msysgit.github.io/

2、安装完成后，还需要最后一步设置，在命令行输入：
   $ git config --global user.name "trumol"
   $ git config --global user.email "475609041@qq.com"

   //因为Git是分布式版本控制系统，所以，每个机器都必须自报家门：你的名字和Email地址。
   //git config命令的--global参数，用了这个参数，表示你这台机器上所有的Git仓库都会使用这个配置，

3、创建版本库
   3.1 第一步，选择一个合适的地方，创建一个空目录：
   $ mkdir E:/repository
   $ cd E:/repository
   $ pwd
    E/repository

   3.2 第二步，通过git init命令把这个目录变成Git可以管理的仓库：
   $ git init

4、把一个文件放到Git仓库只需要两步。
   4.1 第一步，用命令git add告诉Git，把文件添加到仓库：
   $ git add readme.txt

   4.2 第二步，用命令git commit告诉Git，把文件提交到仓库：
   $ git commit -m "wrote a readme file"

5、运行git status命令看看结果