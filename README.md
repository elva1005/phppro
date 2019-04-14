# phppro

## 1. install git 
```
yum install git
```

## 2. install docker
```
yum install docker

## 启动docker服务
service docker start
```

## 3. install docker compose

- 下载文件
	```bash
	sudo curl -L https://github.com/docker/compose/releases/download/1.16.1/docker-compose-`uname -s`-`uname -m` -o /usr/local/bin/docker-compose
	```
- 设置执行权限
	```bash
	sudo chmod +x /usr/local/bin/docker-compose
	```

- 验证
	```bash
	docker-compose --version 
	```

