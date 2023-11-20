``` java
List<Restaurant> restaurants = global_restaurant_manager.get_restaurants();  
Assert.assertEquals(1, restaurants.size());  
Restaurant restaurant = restaurants.get(0);  
Assert.assertEquals(restaurant_name, restaurant.getName());  
Menu menu = restaurant.getListemenu().get(0);
```
