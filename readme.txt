注意：所有版本控制系统 都只能跟踪【文本文件】的改动。
 ->txt、html、cpp等。
 ->picture、world等二进制文件不能跟踪细节修改。

·查看用户名及邮箱：
 ->git config user.name
 ->git config user.email
·修改用户名及邮箱
 ->git config --global user.name "your name"
 ->git config --global user.email "your email"
·查看git的安装路径
 ->where git
 ·创建版本库
  ->git init path
·添加文件到仓库
 ->git add file 
 ->git commit -m  "message"
 ·查看仓库状态
  ->git status
·比较有什么不同
 ->git diff file_name
·查看仓库文件提交日志
 ->git log
