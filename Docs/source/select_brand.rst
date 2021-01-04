**************************************************
Select Brand
**************************************************
It selects the brand passed in ``brand`` when search is made.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.select_brand(brand="brand")

   
   :param str brand: Brand name like Nike if you searched shoes
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict