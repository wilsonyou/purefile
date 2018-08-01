# 清空数据库
在更改运行环境后需要清空数据库的数据。清空数据库需要完成以下步骤。
1.输入以下命令进入到BUMO服务目录。

```
cd /usr/local/buchain/bin
```
2.输入以下命令完成数据库清除。

```
./bumo --dropdb
```

**说明**：清除数据库之后可以通过`service bumo start`命令启动BUMO服务，还可以通过`service bumo status`查看bumo的运行状态。








