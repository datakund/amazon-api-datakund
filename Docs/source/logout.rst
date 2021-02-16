**************************************************
Logout
**************************************************
It goes to homepage and then log out from amazon. By default log outs from amazon.com, can send other url in ``home_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.logout(home_url="https://www.amazon.in/")

   
   :param str home_url: Home Url
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
