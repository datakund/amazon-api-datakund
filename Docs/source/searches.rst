**************************************************
Search
**************************************************
It searches the keyword passed in ``keyword``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.search(keyword="shoes")

   
   :param str keyword: keyword which needs to be searched on amazon
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
