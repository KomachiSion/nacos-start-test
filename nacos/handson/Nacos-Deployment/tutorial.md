# Nacos 部署文档

## 0. 依赖说明

使用Nacos前，需要在运行环境中安装Java(x64) 8～11版本。

## 1. 下载并安装Nacos服务端

官方的Nacos服务端需要在Github上进行下载

[Nacos下载页]{https://github.com/alibaba/nacos/releases}

在本实验中，您可以使用以下命令直接下载

```
https://github.com/alibaba/nacos/releases/download/2.0.0-BETA/nacos-server-2.0.0-BETA.tar.gz
```

下载完成后，仅需要解压即可安装完成。

```
tar -zxvf nacos-server-2.0.0-BETA.tar.gz
```

## 2. 启动Nacos服务端

进入解压后的Nacos目录，然后使用下列命令即可启动一个单例模式的Nacos服务端。

```
cd nacos
bin/startup.sh -m standalone
```
