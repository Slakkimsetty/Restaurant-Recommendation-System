# Restaurant-Recommendation-System

Recomending Restaurants based on reviews and cusine types with zomato dataset using mining of massive datasets algorithms.

##Dataset 
**Attributes used :** 

* url = contains the url of the restaurant in the zomato website
* address = contains the address of the restaurant in Bengaluru
* name = contains the name of the restaurant
* online_order = whether online ordering is available in the restaurant or not
* book_table = table book option available or not
* rate = contains the overall rating of the restaurant out of 5
* location = contains the neighborhood in which the restaurant is located
* rest_type = restaurant type
* dish_liked = dishes people liked in the restaurant
* cuisines = food styles, separated by comma
* approx_cost(for two people) = contains the approximate cost for meal for two people
* reviews_list = list of tuples containing reviews for the restaurant, each tuple consists of two values,
  rating and review by the customer
* menu_item = contains list of menus available in the restaurant
* listed_in(type) = type of meal
* listed_in(city)contains the neighborhood in which the restaurant is listed

##Dataset Sample :

![image](https://user-images.githubusercontent.com/95501767/204100064-f9c4f97f-b25a-46c0-8e5e-eeb489d9e6b1.png)


## Algorithms Used :
In this Problem Statement we have used Three differernt models respectively :

  1. TF - IDF
  2. APRORI 
  3. JACCARD SIMILARITY
