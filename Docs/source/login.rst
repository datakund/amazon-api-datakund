**************************************************
Login
**************************************************
It logins to the amazon through credentials passed in ``email`` and ``password``. By default it logins to amazon.com, but you can login to others by passing login url in ``login_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.login(email="datakund@gmail.com",login_url="amazon sign in url",password="pwd123")

   
   :param str email: amazon email
   :param str login_url: amazon login url(can exclude it)
   :param str password: amazon password
   :return: {"body": {}, "success_score": "100", "errors": []}
   :rtype: dict
