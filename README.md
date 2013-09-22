sstdm_restaurant
================

spatio-temporal data mining of restaurants using google api


 
Hypothesis: The “page rank” of a business is somewhat related to its creditworthiness.
Problem: Given a restaurant, find it’s “local page rank” using a google API (e.g., the google places API), that is, how “important” does google think the restaurant is compared to it’s neighbouring restaurants.


================

This is strictly a proof of concept application.  Simplicity is key - as is proof of concept, so it's all in a completely self-contained html file. Just download it, double-click on it and it'll show up on your browser. Then, just search for a restaurant and it'll give you the relative prominence ranking of that restaurant.

One way to make this better is to create an aggregator of your own. To do this, you'd make a web server with php or node, and make an api call that would take the data, do any extra processing on it, and store it in a DB.


[![Bitdeli Badge](https://d2weczhvl823v0.cloudfront.net/wanderlustzoe/sstdm_restaurant/trend.png)](https://bitdeli.com/free "Bitdeli Badge")

