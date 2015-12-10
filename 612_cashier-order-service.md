# 6.1.2 cashier-order-service

        提供对数据库中cashier order相关数据的维护接口，主要向cashier－service提供服务。
        
提供接口：
1. insertOrderService：插入cashier订单，包括父单子单以及Detail等各相关表。
2. loadOrderService/slaveLoadOrderService：从主/从库中获取各表中的信息。
3. updateOrderService：对各相关表进行维护操作。
4. updateOrderStatusService：维护父订单状态变更；
