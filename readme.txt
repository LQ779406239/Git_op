注意：所有版本控制系统 都只能跟踪【文本文件】的改动。
 ->txt文件、html网页、cpp程序源文件等。
 ->图片、world等二进制文件不能跟踪细节修改

·查看用户名及邮箱：
 git config user.name
 git config user.email
 ->(LiuQing)
 ->(lq779406239@live.com)
·修改用户名及邮箱
 git config --global user.name "your name"
 git config --global user.email "your email"
·查看git的安装路径
 where git
 ->(C:\Program Files\Git\cmd\git.exe)
 ·创建版本库
  git init  D:/Git_WorkSpace
   ->文件夹中多了一个隐藏的.git文件夹
   ->该隐藏文件夹跟踪管理版本库，手动修改不允许。
·