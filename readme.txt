注意：所有版本控制系统 都只能跟踪【文本文件】的改动。
 ->txt、html、cpp等。
 ->picture、world等二进制文件不能跟踪细节修改。

·查看用户名及邮箱：
 git config user.name
 git config user.email
·修改用户名及邮箱
 git config --global user.name "your name"
 git config --global user.email "your email"
·查看git的安装路径
 where git
 ->(C:\Program Files\Git\cmd\git.exe)
 ·创建版本库
  git init  path
   ->文件夹中多了一个隐藏的.git文件夹
   ->该隐藏文件夹跟踪管理版本库，手动修改不允许。
·添加文件到仓库
 ->git add file 
 ->git commit -m  "message"
 ·查看仓库状态
  ->git status
·比较有什么不同
 ->git diff readme.txt(文件名)
·查看仓库文件提交日志
 ->git log
 ·查看命令历史，可以确定恢复到哪个版本
