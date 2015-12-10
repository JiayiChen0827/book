# 6.1.1 hui-order-service

    闪惠订单操作service，主要被mopay－service和hui－business－service所依赖，提供创建，维护闪惠订单的接口。
    

提供接口：
1. createHuiOrderService：创建HUI订单；
2. createHuiPreOrderService：创建HUI预订单；
3. orderProcessService：维护闪惠订单；
4. preOrderProcessService：维护预订单；
5. slaveQueryPreOrderService：预订单搜索；
6. refundHuiOrderService：闪惠订单退款操作；
7. queryHuiOrderService：查询闪惠订单（主库）；
8. slaveQueryHuiOrderService：查询闪惠订单（从库）；
9. huiOrderReceiptService：维护mopay_receipt表（主库）；
10. slaveQueryHuiOrderReceiptService：查询mopay_receipt表（从库）；
11. huiOrderMerchantCouponService：维护merchant表（主库）；
12. slaveQueryHuiOrderMerchantCouponService：查询merchant表（从库）；


项目依赖：

MOPay数据

