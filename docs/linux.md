# Linux
## Linux Centos
### system
温度监控 ```sensors```
程序```top```
内存使用```free -m```
磁盘```df -h```
网络```ifconfig```

## Nginx
>添加到环境

配置```/usr/local/nginx/conf/nginx.conf```
```
nginx
nginx -s stop
nginx -s reload
```
## UWSGI
>cd 目录

配置文件```uwsgi.ini```
```
uwsgi uwsgi.ini
uwsgi --stop uwsgi.pid
uwsgi --reload uwsgi.pid
```
