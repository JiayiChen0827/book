# 表UniCashier_Order_Children

    cashier子订单表。
    
其中：

OrderId:为父订单Id;

OrderType:为子订单类型:

 * 0:未知；
 * 10:代金券未买；
 * 11:代金券已买；
 * 20:剩余部分支付。
 

PayOrderId:纪录非0元单中支付订单Id；