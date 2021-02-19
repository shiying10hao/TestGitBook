# 安装Node.js

* nvm v --查版本
* nvm ls available --查nodejs所有版本
* nvm install 12.17.0 --安装指定版本，高版本有问题
* node -v  npm -v --检验node.js以及对应npm是否安装成功
* nvm use 12.17.0 --使用nodejs某版本
* nvm ls --查看安装的所有node.js版本号，以及当前所选择的node.js运行版本

--[https://www.jb51.net/article/202124.htm](https://www.jb51.net/article/202124.htm)

#### Node.js 镜像配置

* npm config set registry [http://registry.npm.taobao.org](http://registry.npm.taobao.org) --默认的镜像地址是在国外，国内访问速度极慢

# 安装GitBook

* npm install gitbook-cli -g
* gitbook --version 查看安装的版本信息

--[https://www.mapull.com/gitbook/comscore/basic/install.htm](https://www.mapull.com/gitbook/comscore/basic/install.htm)

# GitBook运行

* gitbook serve --port 2333 --指定端口,默认端口4000

* sudo npm install gitbook-pdf -g --输入为PDF文件，需要先使用NPM安装上gitbook pdf

# GitBook停止

* "Ctrl"+C



