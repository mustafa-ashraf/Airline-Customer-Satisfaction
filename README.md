# **Airline passenger satisfaction**

![Airline customer](https://cdn.businesstraveller.com/wp-content/uploads/fly-images/807449/Happy-passenger-e1494847969809-916x515.jpg)





<h3>There is the following information about the passengers of some airline:</h3>

-Gender: male or female<br>
-Customer type: regular or non-regular airline customer<br>
-Age: the actual age of the passenger<br>
-Type of travel: the purpose of the passenger's flight (personal or business travel)<br>
-Class: business, economy, economy plus<br>
-Flight distance<br>
-Seat comfort: seat satisfaction level (0: not rated; 1-5)<br>
-Departure/Arrival time convenient: departure/arrival time satisfaction level (0: not rated; 1-5)<br>
-Food and drink: food and drink satisfaction level (0: not rated; 1-5)<br>
-Gate location: level of satisfaction with the gate location (0: not rated; 1-5)<br>
-Inflight wifi service: satisfaction level with Wi-Fi service on board (0: not rated; 1-5)<br>
-Inflight entertainment: satisfaction with inflight entertainment (0: not rated; 1-5)<br>
-Online Support<br>
-Ease of Online booking: online booking satisfaction rate (0: not rated; 1-5)<br>
-On-board service: level of satisfaction with on-board service (0: not rated; 1-5)<br>
-Leg room service: level of satisfaction with leg room service (0: not rated; 1-5)<br>
-Baggage handling: level of satisfaction with baggage handling (0: not rated; 1-5)<br>
-Checkin service: level of satisfaction with checkin service (0: not rated; 1-5)<br>
-Cleanliness: level of satisfaction with cleanliness (0: not rated; 1-5)<br>
-Online boarding: satisfaction level with online boarding (0: not rated; 1-5)<br>
-Departure delay in minutes<br>
-Arrival delay in minutes<br><br><br>
This data set contains a survey on air passenger satisfaction. The following classification problem is set:<br>

It is necessary to predict which of the two levels of satisfaction with the airline the passenger belongs to:<br>
- Satisfaction
- dissatisfied

We get insights:<br>
- Ease of online booking is an important factor affect the satisfaction<br>
- online suuport is an important factor affect the satisfaction<br>
- on board service is an important factor affect the satisfaction<br>


we have two methods that we will use to detect the best related features to our target
- Chi-Square
- Random Forest importance Method
- Feature Permutation Importance


From all above results, finally we can combine and conclude the list of important features.
Really Important Features: Seat comfort,Customer Type,Inflight_entertainment,Gender,Checkin_service
Important Features: Type of Travel,Online support, Baggage handling,cleanliness,Online boarding,On_board service,Class


Conclusion:

- Passengers also appear to be sensitive to certain aspects of their services and as 
such the airline should tackle such issues as a priority to improve services.
- This includes inflight wifi and departure time. That said, if the airline wished to continue to 
focus on business travellers aspects such as online booking and seat comfort should be prioritised.
- There are also aspects such as ticket price, flight location also missing from this dataset.


Recommendation:
About business, my advise to the company to improve the services that have low score for the Eco class:
- food_and_drink
- online_boarding
- seat_comfort
- inflight_entertainment
- on_board_service
- leg_room_service

Future work:<br>
- we have some questions that we thought it will help us to get to know our data more
- was the departure delay caused by bad weather?
- was their seatmate rude?
- we would love to know more details about the dataset to get more detailed analysis



# THANK YOU



