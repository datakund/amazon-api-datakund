**************************************************
Product Info
**************************************************
It fetches information of the product passed in ``product_url``.

**body**: returns data

**success_score**: api success rate

**errors**: errors encountered in api 

Here is the code:-

.. py:function:: amazon.product_info(product_url="product_url")

   
   :param str product_url: product url
   :return: {"body": {'Review Terms': 'Review Terms', 'NoOfRatings': 'NoOfRatings', 'ReviewsLink': 'ReviewsLink', 'Price': 'Price', 'Ratings': 'Ratings', 'Description': 'Description', 'Features': 'Features', 'Offers': 'Offers', 'Title': 'Title'}, "success_score": "100", "errors": []}
   :rtype: dict