**************************************************
Select Category
**************************************************
It selects the category passed in ``category`` when search is made.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.select_category(category="Clothes")

   
   :param str category: Category name like shoes/clothes
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
