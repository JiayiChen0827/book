# 表MOPay_Scheme

    包括MOPay_Scheme以及MOPay_Scheme_CouponOffer表,并主要关联于DianpingHui中的表HUI_CouponOffer。
    
表MOPay_Scheme:

* scheme_id:对应scheme；

* solution_id:对应solution；

* type：0为点评/1为美团。



表MOPay_Scheme_CouponOffer:

* relate_scheme_id: 对应表MOPay_Scheme中id；
* coupon_offer_id:对应表HUI_CouponOffer中coupon Id
