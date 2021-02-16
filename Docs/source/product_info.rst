**************************************************
Product Info
**************************************************
It fetches information of the product passed in ``product_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.product_info(product_url="https://www.amazon.in/Sony-WF-XB700-Wireless-Bluetooth-Headphones/dp/B085VQFZ8Z/ref=sr_1_2_sspa?dchild=1&keywords=jbl+earbuds&pd_rd_r=9f5d38ab-dcc6-4c29-bef0-e646dffbc5a3&pd_rd_w=3Paz5&pd_rd_wg=F14yq&pf_rd_p=1abe8808-d6bc-4840-858b-6acddb119a7a&pf_rd_r=MST8X5YENPSB71RQ87KS&qid=1613454716&sr=8-2-spons&psc=1&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEyWU1LOVBNVFBWMzI4JmVuY3J5cHRlZElkPUEwNTA4Nzg1MlUzQkQ5SkhHQUZZSiZlbmNyeXB0ZWRBZElkPUEwODUzMjU4OTRZN1dRWDI0NVdZJndpZGdldE5hbWU9c3BfYXRmJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ==")

   
   :param str product_url: product url
   :return: {"body": {'Review Terms': 'Review Terms', 'NoOfRatings': 'NoOfRatings', 'ReviewsLink': 'ReviewsLink', 'Price': 'Price', 'Ratings': 'Ratings', 'Description': 'Description', 'Features': 'Features', 'Offers': 'Offers', 'Title': 'Title'}, "success_score": "100", "errors": []}
   :rtype: dict
