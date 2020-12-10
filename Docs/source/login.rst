**************************************************
Login
**************************************************
It logins to the amazon through credentials passed in ``email`` and ``password``.

Here is the code:-

.. py:function:: amazon.login(password="password",login_url="login_url",email="email")

   
   :param str password: Amazon password
   :param str login_url: Signin url of amazon site, by default it logins to amazon.com (optional)
   :param str email: Amazon email or username
   :return: {}
   :rtype: dict