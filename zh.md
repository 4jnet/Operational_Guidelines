如何从合约购买 4JNET Token
====


#### 1.Open Pancakerouter 智能合约，来自 bscscan.com:0x10ED43C718714eb63d5aA57B78B54704E256024E  或者，在 Web 浏览器中，输入 Web 链接为：
  https://bscscan.com/address/0x10ED43C718714eb63d5aA57B78B54704E256024E#writeContract

#### 2.链接钱包（例如MetaMask）
  点击Connect to Web3

  ![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot1.jpg)


#### 3.调用"swapExactETHForTokensSupportingFeeOnTransferTokens"函数与BNB兑换4JNET，函数参数如下：

  （1）和函数名相同的参数为用于兑换用户想支出的bnb本金数量（默认省略了18位小数） 例如可以输入 0.01 （数量要小于账号bnb的余额，因为要支付一些gas费）。
    因为4jnet每次转账的最大限额为10万亿，外加手续费的影响，交易开启后，4jnet的第一笔最多可以兑换1bnb左右。后随着4jnet价格上升，可以使用更多的bnb进行兑换。
  （2）用户能接受4JNET的最小输出数量。如果因为滑点变化没有得到足够的4JNET，交易会失败。为保证成功，建议输入0
  （3）兑换路径，WBNB -> 4JNET  (BscScan或浏览器的原因，列表中的地址有可能需要加双引号)
    [0xbb4cdb9cbd36b01bd1cbaebf2de08d9173bc095c,0xbfb1a68962fb4ed040fd3a0a71dc2c2015bcc667]
  （4）4jnet接收地址，为用户钱包的bsc地址
  （5）截止时间，需要输入一个比当前时间大一些的Unix时间戳,比如可以输入   1703310977
![Image text](https://raw.githubusercontent.com/4jnet/Operational_Guidelines/main/images/ScreenShot2.jpg)

