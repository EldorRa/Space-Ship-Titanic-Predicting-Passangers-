# Spaceship-Titanic

Predict which passengers are transported to an alternate dimension ( Kaggle competition )

Link to competition : https://www.kaggle.com/competitions/spaceship-titanic/overview

Data
There is version of data on Kaggle : https://www.kaggle.com/competitions/spaceship-titanic/data

Evaluation
Submission to Kaggle evaluated based on classification accuracy

Features
1. PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp
where gggg indicates a group the passenger is travelling with and pp is their number within the group. People in a group are often family members, but not always. 
2. HomePlanet - The planet the passenger departed from, typically their planet of permanent residence. 
3. CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to their cabins. 4. Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard. 
5. Destination - The planet the passenger will be debarking to. 
6. Age - The age of the passenger. 
7. VIP - Whether the passenger has paid for special VIP service during the voyage. 
8. RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities. 
9. Name - The first and last names of the passenger. 
10. Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.
