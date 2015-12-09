# 4.1.2 创单时

    创单操作由mopay-service和cashier-service共同完成。

创单操作主要由以下步骤组成：

创单前校验，校验成功后允许创单；

通过用户实付金额将订单分为2类进行cashier order创单操作：0元单/非0元单两类；
其中非0元单创单时会生成付款单，向支付中心发送消息。

之后调用mopay-service创建mopay order。
  
 


 
