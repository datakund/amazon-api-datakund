**************************************************
Select Payment Method
**************************************************
It chooses the payment method passed in ``payment_method``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.select_payment_method(payment_method="Net Banking")

   
   :param str payment_method: payment method
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
