# 文档

[Go中文标准库文档](http://word.gitbb.cn/ "Go中文标准库文档")

[地鼠文档](http://www.topgoer.cn/ "地鼠文档")

[Go文档框架链接](http://www.topgoer.com/)

[工具网站](https://oktools.net/json2go)


下载地址：https://studygolang.com/dl

1、下载golang的二进制作文件：
```
wget https://studygolang.com/dl/golang/go1.17.6.linux-amd64.tar.gz
```
2、解压二进制文件：
```shell
tar -xzvf go1.17.4.linux-amd64.tar.gz
```
3、把golang安装到系统中:
```
# rm -rf /usr/local/go;mv ./go /usr/local/
mv ./go /usr/local/
```
4、把go的二进制文件修改成可执行权限，并把路径加到path路径:
```
chmod u+x /usr/local/go/bin/go
echo 'export  PATH=$PATH:/usr/local/go/bin' >> /etc/profile
.  /etc/profile
```
5、设置代理
```
go env -w GOPROXY=https://goproxy.cn,direct
```
在终端执行：`go version`命令，看到入下内容，说明go安装成功
```
go version
```
