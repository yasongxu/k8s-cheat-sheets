## docker images

```
docker images
```

```
docker build -t .
```

## containers

列出当前所有正在运行的container
```
$docker ps
```

用一行列出所有正在运行的container（容器多的时候非常清晰）
```
$docker ps | less -S
```

列出所有的container
```
$docker ps -a  
```

列出最近一次启动的container
```
$docker ps -l 
```

显示一个运行的容器里面的进程信息
```
$docker top Name/ID  
```

查看容器内部详情：
```
$docker inspect <id/container_name>
```
