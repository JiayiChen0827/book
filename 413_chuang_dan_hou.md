# 4.1.3 创单后

1. cashier-service监听订单状态消息，更新子订单状态；

2. 通过子订单状态信息，更新订单状态同时向mopay-service发送消息；

3. mopay-service更具收到的订单状态消息更新mopay-order状态，若支付成功，完成发放积分，尊享券等操作。

