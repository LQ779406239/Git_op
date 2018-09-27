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
·添加文件到仓库
 ->打开Git Bash 进入要管理的仓库 【cd d:\Git_Workspace】
 ->或者在在仓库路径下邮件鼠标选择【Git Bash Here】
 ->git add readme.txt （当前路径下的文件,把修改提交到暂存区）
 ->git commit -m  "添加文字-本次操作说明"： git commit -m <message> （把暂存区的所有修改提交到分支）
 ·查看仓库状态
  ->git status
·比较有什么不同
 ->git diff readme.txt(文件名)
·查看仓库文件提交日志
 ->git log
 ·查看命令历史，可以确定恢复到哪个版本
·返回历史版本号
->git reset --hard commit_id (id:十六进制的commit_id)
·返回未来版本号
 ->git reflog
 ->git reset --hard commit_id (id:十六进制的commit_id)

 ·修改了工作区某个文件的内容，还没有提交到远程版本库，想直接丢弃工作区的修改
  ->git checkout --files
  ->git reset HEAD <file>
·从版本库中删除文件
 ->git rm file （readme.txt）
 ->git commit -m "readme.txt"

 -->>>>status 工作区与暂存区