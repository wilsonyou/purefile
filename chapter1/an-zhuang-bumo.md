# 安装BUMO节点

在编译完成后才能安装BUMO节点。安装BUMO节点需要完成以下步骤：

  
1.输入以下命令进入到安装目录。

```
cd /bumo/
```

2.输入以下命令完成安装。出现下图所示信息则表示安装成功。

```
make install
```

![](/assets/compile_installed.png)


**说明**：

* 默认情况下服务安装在/usr/local/buchain/目录下。
* 安装完成后无需其他配置即可通过`service bumo start` 命令来启动bumo服务。
* 安装完BUMO节点后在buchain/目录下有如下目录结构：

| 目录|说明|
|----------|
|bin|存放可执行文件（编译后的bumo可执行程序）|
|jslib|	存放第三方js库|
|config|配置文件目录包含：bumo.json|
|data|数据库目录，存放账本数据|
|scripts|启停脚本目录|
|log|运行日志存储目录|





