**************************************************
Select Bank
**************************************************
It chooses the bank passed in ``bank``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.select_bank(bank="bank")

   
   :param str bank: bank name e.g. HDFC Bank
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict