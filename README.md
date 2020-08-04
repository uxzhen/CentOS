# CentOS

## centos 安装node
```
	1.先去官网下载node安装包Linux Binaries (x64)
	2.tar -xvf node-v10.16.0-linux-x64.tar.xz 解压
	3.软连接 
	ln -s /usr/local/nodejs/bin/npm /usr/local/bin/
	ln -s /usr/local/nodejs/bin/node /usr/local/bin/


	例子：
	ln -s /www/wwwroot/node-v10.9.0-linux-x64/bin/npm /usr/local/bin/
	ln -s /www/wwwroot/node-v10.9.0-linux-x64/bin/node /usr/local/bin/
	
	4.node -v
	npm -v


	操作
	查看目录的软软连接
	ls -alR | grep ^l

	删除rm -rf npm
```


## java 部署jar包操作
```

  java -jar server.jar &
  //后台运行，退出shell依然运行。
     
 nohup java -jar server.jar &
 如果想要关闭java进程，输入命令行
 
 1，列出后台进程
 
 ps -ef | grep java
 2，杀死进程
 
kill -9 xxxx
```


