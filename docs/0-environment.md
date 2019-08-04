开发及运行环境
===
## 操作系统环境: 
ubuntu 18.04 amd64

## 依赖包说明
1. [hit-oslab-linux-20110823.tar.gz](https://github.com/hoverwinter/HIT-OSLab/tree/master/Resources)		
	包含linux-0.11源码，bochs虚拟机等
2. [gcc-3.4-ubuntu.tar.gz](https://github.com/hoverwinter/HIT-OSLab/tree/master/Resources)		
	编译linux-0.11需要用到的低版本的gcc 
3. 所有的依赖我都已经添加到路径下面了， 在ubuntu18.04系统上可以clone项目直接安装运行

## 安装
1. 克隆该仓库
	```bash
	git clone https://github.com/libaoan/gk-linux0.11.git
	```
2. 进入到仓库目录
	```bash
	cd gk-linux-0.11/
	```
3. 执行setup.sh脚本
	```bash
	./setup.sh
	```

## 运行
1. 由于下载下来的是源代码，需要先编译生成Image镜像
	```bash
	./run make
	```
2. 运行并启动gk-linux-0.11
	```bash
	./run 
	```
## 重置环境
如果涉及到修改源代码，需要删除旧的目标文件以及Image镜像，可以运行以下命令重置环境
	```bash
	./run clean
	```

