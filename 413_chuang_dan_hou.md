# 4.1.3 创单后

cashier-service监听订单状态消息，更新子订单状态；

通过子订单状态信息，更新订单状态同时向mopay-service发送消息；

mopay-service收到