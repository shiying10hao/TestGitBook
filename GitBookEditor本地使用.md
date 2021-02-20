# Git和GitBookEditor安装

* 官网下载安装

# 本地GitBookEditor关联远程存储库

* 在文件夹下右击Git bash here 出现命令框体
* $ mkdir book --创建文件夹
* $ cd book --跳转到新创建文件夹，可以不创建文件夹，克隆时会创建存储库文件件
* $ git clone [https://github.com/shiying10hao/testGitBook.git](https://github.com/shiying10hao/testGitBook.git)  --克隆远程存储库，需要输入用户名和密码
* 使用GitBookEditor的“Open”方式打开本地刚克隆的存储库，编辑“Save”后需要上传“Sync”到远程存储库，首次会再输入一次用户名和密码

# 本地上传到TFS中OpenDoc存储库下

* git branch xxx  --新建分支，客户端只新建一次
* git branch -a --查看所有分支
* git checkout xxx  --切换到某一分支 【由批处理文件统一执行，并提交分支】
* git add .  --添加修改代码到缓存（注意最后的"."前面有个空格）【由批处理文件统一执行，并提交分支】
* git commit -m "XXXX"  --（XXXX为本次提交代码的备注） 添加提交代码的备注【由批处理文件统一执行，并提交分支】
* git push origin xxx  --（xxx为要提交代码的分支名称）提交代码到指定分支【由批处理文件统一执行，并提交分支】



