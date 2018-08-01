# 探测用户充值
交易所需要开发监听区块生成，然后解析区块里的交易记录，从而确认用户充值行为。具体步骤如下:

1.确保节点区块状态是正常的。

2.解析区块里包含的交易（解析方法见解析区块交易）。

3.记录解析后的结果。

## 查看区块状态
通过如下所示代码查看区块状态。

![](/assets/4.jpg)

**说明**：
* 如果返回值为true则表示区块正常
* 如果返回值为false则表示区块异常

## 解析区块交易

交易所可根据区块高度查询该区块里的交易信息，然后分析每条交易信息。

请求示例：

![](/assets/5.jpg)

响应报文如下：
![](/assets/1.png)
![](/assets/2.png)
![](/assets/3.png)
**说明**：
* 关于Bumo-sdk-java 如何使用，请访问以下链接：

https://github.com/bumoproject/bumo-sdk-java/tree/release2.0.0

* 关于交易所对接示例，请访问以下链接：

https://github.com/bumoproject/bumo-sdk-java/blob/release2.0.0/examples/src/main/java/io/bumo/sdk/example/ExchangeDemo.java



