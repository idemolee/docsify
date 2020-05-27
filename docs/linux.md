# Linux
## Linux Centos
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
