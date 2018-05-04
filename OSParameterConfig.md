# 操作系统参数

## 文件句柄数配置
在/etc/security/limits.conf的末尾加入<br>
\* soft nofile 100000<br>
\* hard nofile 100000<br>
配置完重新登录即可生效。<br>
