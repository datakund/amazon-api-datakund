Other Functions
**************************************************
You can use basic functions which selenium provides with this library like opening a url, get pagesource, get current url etc. These are the functions:-

Open
========

It will open the url provided in the argument.

.. py:function:: amazon.open(url)

   :param str url: Link which need to be opened
   :return: {}
   :rtype: dict
	
	
Get Page Title
=================

It returns the title of page opened.

.. py:function:: amazon.get_page_title()

   :return: {"pagetitle":"amazon"}
   :rtype: dict

Get Page Source
===================

It returns the pagesource of page opened.

.. py:function:: amazon.get_page_source()

   :return: {"pagesource":"pagesource"}
   :rtype: dict

Get Current Url
===================

It returns the pagesource of page opened.

.. py:function:: amazon.get_current_url()

   :return: {"url":"url"}
   :rtype: dict

Reload
===================

It reloads the page opened.

.. py:function:: amazon.reload()

   :return: {}
   :rtype: dict

Keypress
===================

It perform the keypress passed.

.. py:function:: amazon.keypress(key)

   :param str key: Key which need to be pressed, e.g pagedown,arrowleft,enter
   :return: {}
   :rtype: dict

Scroll
===================

It scrolls to the end of page.

.. py:function:: amazon.scroll()

   :return: {}
   :rtype: dict
   
End
===================

It ends the amazon session and close the automated chromedriver.

.. note:: You will need to create amazon object again after ``end()``.

.. py:function:: amazon.end()

   :return: {}
   :rtype: dict
	
Quit
===================

It quits the bot-studio application runing in background.

.. note:: You will need to import bot-studio library again to start application.

.. py:function:: amazon.quit()

   :return: {}
   :rtype: dict
