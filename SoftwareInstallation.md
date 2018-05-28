# 常见软件安装
## Nginx
**第一步：添加nginx资源库**<br>
说明：由于CentOS默认没有nginx的安装源，因此需要自己添加资源库。<br>
[root@centos7 ~]# rpm -Uvh http://nginx.org/packages/centos/7/noarch/RPMS/nginx-release-centos-7-0.el7.ngx.noarch.rpm
<br>

**第二步：安装nginx**<br>
[root@centos7 ~]# yum install nginx -y<br>

**第三步：启动nginx**<br>
[root@elk ~]# systemctl start nginx<br>

**第四步：检查nginx**<br>
[1] 查看nginx状态<br>
[root@elk ~]# systemctl status nginx<br>

[2] 通过浏览器查看nginx默认首页<br>
nginx默认端口为80，因此，直接访问：http://{your IP address}/，如http://192.168.159.161/。<br>


