**************************************************
Login Cookie
**************************************************
It logins to the amazon through cookies passed in ``cookies``. By default it logins to amazon.com , but you can pass login url in ``login_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.login_cookie(login_url="login_url",cookies="cookies")

   
   :param str login_url: e.g www.amazon.in
   :param str cookies: list of cookies
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict