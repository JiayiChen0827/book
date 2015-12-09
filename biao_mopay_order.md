# 表MOPay_Order

    MOPay_Order表纪录在用的闪惠订单信息。

其中需要提及的column有：

OrderStatus:取代Status表示订单状态信息。
* 0:未支付；
* 10:已支付；


SerializedId：MM站订单使用这里的数据。

CashierOrderId：关联UniCashier_Order表，为其Id。

PayOrderId:此处已废弃。