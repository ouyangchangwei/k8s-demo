### 指令
#### 在windows系统下修改命令
1. set GOOS=linux
2. set GOARCH=arm
3. go build -o k8s-demo .
#### 编写Dockerfile
执行docker build . -t oyzzz.github.com/k8s-demo:v0.0.1

#### docker构建镜像
```bash
    docker build . -t oyzzz.github.com/k8s-demo:v0.0.1
```

#### docker运行镜像
```bash
    docker run -p 8088:8088 oyzzz.github.com/k8s-demo:v0.0.1
```