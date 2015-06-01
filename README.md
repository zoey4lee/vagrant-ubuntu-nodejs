# vagrant-ubuntu-nodejs
帐号vagrant/密码vagrant
切换到root用户

$ sudo su

$ sudo apt-get upgrade

一、Linux（Ubuntu）下安装NodeJs

$ sudo apt-get install g++

$ sudo apt-get install libssl-dev


接下来，就可以下载安装nodeJS了，下面是安装步骤：

$ wget http://nodejs.org/dist/latest/node-v0.12.4.tar.gz

$ tar zxvf node-v0.8.16.tar.gz

$ ./configure

$ make && make install


安装好后，在 控制台下输入：

$ node -v


二、Linux（Ubuntu）下安装Mongodb

$ sudo apt-get install httpd php php-pear php-devel gcc

$ apt-get install mongo


通过"pgrep mongo -l "查看进程是否已经启动

$ pgrep mongo -l

$ mongo


三、Linux（Ubuntu）下安装MEAN.IO
必须切换成非root用户 sudo vagrant
$ sudo npm install -g mean-cli 

$ mean init yourNewApp


mean.io详情https://github.com/linnovate/mean
