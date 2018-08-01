# 更改运行环境
在更改BUMO的运行环境之前需要[关闭BUMO服务](/yun-wei/guan-bi-bumo-fu-wu.md)。您可按照以下步骤进行修改。

1.输入以下命令进入到配置文件目录。

```
cd /usr/local/buchain/config/
```

**说明**：在该目录下提供了以下运行环境的配置文件。
* bumo-mainnet.json（该文件是主网环境的配置文件，应用在生成环境中）
* bumo-testnet.json（该文件是测试网环境的配置文件）
* bumo-single.json（该文件是单节点调试环境的配置文件）

2.把当前运行环境的配置文件（bumo.json）更改为其他名称，例如：

```
mv bumo.json bumoprevious.json
```

3.把要运行的环境配置文件更改为bumo.json，例如：

```
mv bumo-mainnet.json bumo.json
```
**说明**：
* 本示例中把主网环境设置成了运行环境。
* 更改运行环境后需要[清空数据库](/yun-wei/qing-kong-shu-ju-ku.md)才能重启bumo服务。






