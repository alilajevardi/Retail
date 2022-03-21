
# EDA-for-restaurant-datasets
## Loading and merging data:
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r1.png)
 
 Four datases of Rating_Final_RECODED.csv, chefmozparking.csv, geoplaces2.csv and userprofile.csv has been merged.
 The new feature of distance_km has been created that displays distance between customer with retaurant in km.
 
 
 Below table demonstrate a high correlation between 'general_score' and 'general_score_binary' features. It means that these to feature can be consider as one alternative feature.
 
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r2.png)
 
 ### Medium price range restaurants get higher rating
 Demonstrated by below graph and table:
 
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r3.png)
 
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r4.png)
 
 
 ### Restaurant closer to customer get higher rating
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r5.png) 
 
 ![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r6.png)


### Customers with higher budget give higher rating
![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r7.png)



### No correlation between customer budget and restaurant price:
customers with all budget ranges go to variod price range restaurants

![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r8.png)


## Interactive map of restaurants and customers
[Map is here](https://github.com/alilajevardi/Retail/blob/main/assets/place_user_map.html)

![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r11.png)

## XGB BOOST Model accuracy with demonstrated feature importance:
![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r9.png)
![picture](https://github.com/alilajevardi/Retail/blob/main/assets/r10.png)

Above graph demonstrates that 'smoking_area' and 'Rambiance' are not highly effective features for salary perdiction. But still, I prefer to keeo it in the dataset. On the other hand engineered feature of 'distance_km' is highly effective.


## Derieved insight
The new restaurant shloud be in medium range price that have valet parkeing service. It is recommended that the resturant get located in high compact residential area with higher budget. 
