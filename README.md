# Spaceship_Titanic

The Spacceship Titanic was an interstellar passenger liner. There are almost 10000 passengers on board, the vessel set out on its maiden voyage transporting emigrants

from our solar system to three newly habitable exoplanets orbiting nearby stars. While rounding Alpha Centauri en route to its first destination—the 

torrid 55 Cancri E—the unwary Spaceship Titanic collided with a spacetime anomaly hidden within a dust cloud. Sadly, it met a similar fate as its namesake from 1000 years

before. Though the ship stayed intact, almost half of the passengers were transported to an alternate dimension.

Hence, this project is to predict which passangers were transported to an alternate dimension. 



train.csv - Personal records for about two-thirds (~8700) of the passengers, to be used as training data.

i) PassengerId - A unique Id for each passenger. Each Id takes the form gggg_pp where gggg indicates a group the passenger is travelling with and pp is their number 

within the group. People in a group are often family members, but not always.

ii) HomePlanet - The planet the passenger departed from, typically their planet of permanent residence.

iii) CryoSleep - Indicates whether the passenger elected to be put into suspended animation for the duration of the voyage. Passengers in cryosleep are confined to 

their cabins.

iv) Cabin - The cabin number where the passenger is staying. Takes the form deck/num/side, where side can be either P for Port or S for Starboard.

v) Destination - The planet the passenger will be debarking to.

vi) Age - The age of the passenger.

vii) VIP - Whether the passenger has paid for special VIP service during the voyage.

viii) RoomService, FoodCourt, ShoppingMall, Spa, VRDeck - Amount the passenger has billed at each of the Spaceship Titanic's many luxury amenities.

ix) Name - The first and last names of the passenger.

x) Transported - Whether the passenger was transported to another dimension. This is the target, the column you are trying to predict.



test.csv - Personal records for the remaining one-third (~4500) of the passengers, to be used as test data. Your task is to predict the value of Transported

for the passengers in this set.
