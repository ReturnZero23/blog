# Docker + Caffe + Digits #
## Docker安装部署 ##
docker官方的安装教程https://docs.docker.com/engine/installation/
### 1、简单的安装的步骤：###
<p>
a、对内核的版本有要求（kernel>3.10）
<p>
b、将docker的官方源导入source.list  
On Ubuntu Precise 12.04 (LTS)  
  deb https://apt.dockerproject.org/repo ubuntu-precise main  
On Ubuntu Trusty 14.04 (LTS)  
  deb https://apt.dockerproject.org/repo ubuntu-trusty main  
Ubuntu Xenial 16.04 (LTS)  
  deb https://apt.dockerproject.org/repo ubuntu-xenial main
<p>
c、更新软件源
```
$ sudo apt-get update

```
d、安装Docker.
```
 $ sudo apt-get install docker-engine
```
e、启动Docker的服务.
```
 $ sudo service docker start
```
注意！！！这里只是简单的安装过程、如果过程中出现问题去官方的安装教程找答案。（链接见前文）
<p>
<p>
### 2、下载Caffe的docker镜像：###
<p>
a、在终端中运行这个命令
```
docker pull kaixhin/caffe
```
