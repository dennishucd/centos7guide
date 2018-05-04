# 软件包安装与卸载

## 软件包查询
如果我们想确认某个软件包是否已安装或者想卸载它，可能就会想到先查一下。如这里想查询一下是否安装了Elastic。
[root@centos7 ~]# rpm -qa|grep -i Elastic<br>
elasticsearch-5.5.1-1.noarch<br>

## 软件包安装
[root@centos7 ~]# rpm -i elasticsearch-6.2.4.rpm<br>

## 软件包卸载
针对查询出来已安装的软件包，可以通过yum卸载它。<br>
[root@centos7 ~]# yum remove elasticsearch-5.5.1-1.noarch<br>

