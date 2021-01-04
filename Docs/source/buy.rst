**************************************************
Buy
**************************************************
It goes to product url passed in ``product_url`` and clicks on buy button.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.buy(product_url="product_url")

   
   :param str product_url: link of product
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict