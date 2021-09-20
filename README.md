# Mari框架

## 源码地址
https://github.com/yumeminami/Mari


## 1.写在前面
首先做这个框架的目的主要有两个，一是使用Golang语言去写一个项目，为了提高Golang的编程能力，更好地去理解Golang语言的特性；二是了解基于Golang编写一个TCP服务器的整体轮廓，学习开发的迭代思维，一个版本一个版本迭代，每个版本的添加功能都是微小的，以循序渐进的曲线方式了解服务器框架的领域。


## 2.快速启动

```bash
# 克隆项目
$ git clone https://github.com/yumeminami/Mari.git

# 进入服务端样例目录
$ cd ./Mari/examples/Mari_server

# 服务端编译
$ make build

# 服务端容器化
$ make image

# 服务端启动
$ make run 

# 进入客户端样例目录
$ cd ../Mari_client

# 启动客户端进行测试
$ go run main.go 

```
## 3.Mari架构图
![Golang轻量级并发服务器框架](https://user-images.githubusercontent.com/67509746/133978611-0fb78caa-74d9-444f-b69c-ec9ec47f05e8.png)
