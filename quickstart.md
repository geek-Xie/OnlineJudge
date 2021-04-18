### 后台开启服务：
```
nohup python manage.py runserver 0.0.0.0:8000 &
```


### 停止服务：
```
# 查看运行服务的进程号
netstat -nap|grep 8000
# 杀死进程
kill -9 进程号
```