# 常见问题

## BUChain命令的节点启动

问：使用BUChain命令行时是否需要启动该节点？

答：不用。

## gas_price和fee_limit的值是否固定

问：gas_price 是固定1000MO，fee_limit 是1000000MO 吗？

答：不是固定。但目前(2018-04-23)gas_price 是1000MO，gas_price 越大越优先打包。fee_limit是交易时交易发起方最多给区块链的交易费用，在正常合法的交易情况下区块链收取的真实费用小于调用方填写的fee_limit。(gas_price 可通过[http://seed1.bumo.io:16002/getLedger?with_fee=true](http://seed1.bumo.io:16002/getLedger?with_fee=true)查询的结果result.fees.gas_price字段得到）。

##  账户余额转出
 
问：账户的余额能否全部转出？

答：不能。为了防止DDOS 攻击，防止创建大量垃圾账户，BUMO激活的账户必须保留一定数量的BU，目前是0.1BU（可通过[http://seed1.bumo.io:16002/getLedger?with_fee=true](http://seed1.bumo.io:16002/getLedger?with_fee=true) 查询  
的结果result.fees.base_reserve 字段得到）。

