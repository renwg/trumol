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

6、查看历史记录
   在Git中，我们用git log命令查看：
   $ git log --pretty=oneline

7、版本回退
   我们要把当前版本“append GPL”回退到上一个版本“add distributed”，就可以使用git reset命令：
   在Git中，用HEAD表示当前版本,
   上一个版本就是HEAD^，上上一个版本就是HEAD^^，当然往上100个版本写100个^比较容易数不过来，所以写成HEAD~100
   $ git reset --hard HEAD^

8、恢复到指定版本 git reset --hard commit_id
   $ git reset --hard cb926e7

9、用git reflog查看命令历史，以便确定要回到未来的哪个版本。
   $ git reflog

10、用git log可以查看提交历史，以便确定要回退到哪个版本。
   $ git log --pretty=oneline


https://github.com/twbs/bootstrap
http://www.liaoxuefeng.com/wiki/0013739516305929606dd18361248578c67b8067c8c017b000/001374829472990293f16b45df14f35b94b3e8a026220c5000
  
