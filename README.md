### Project description
#
##### Context
###### Imagine driving through town and a coupon is delivered to your cell phone for a restaurant near where you are driving. Would you accept that coupon and take a short detour to the restaurant? Would you accept the coupon but use it on a subsequent trip? Would you ignore the coupon entirely? What if the coupon was for a bar instead of a restaurant? What about a coffee house? Would you accept a bar coupon with a minor passenger in the car? What about if it was just you and your partner in the car? Would weather impact the rate of acceptance? What about the time of day? Obviously, proximity to the business is a factor on whether the coupon is delivered to the driver or not, but what are the factors that determine whether a driver accepts the coupon once it is delivered to them? How would you determine whether a driver is likely to accept a coupon?
##### Overview
###### The goal of this project is to use what you know about visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.
##### Data
###### This data comes to us from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. There are five different types of coupons -- less expensive restaurants (under 20), coffee houses, carry out & take away, bar, and more expensive restaurants (20 - $50).
##### Deliverables
###### Your final product should be a brief report that highlights the differences between customers who did and did not accept the coupons. To explore the data you will utilize your knowledge of plotting, statistical summaries, and visualization using Python. You will publish your findings in a public facing github repository as your first portfolio piece.
#
###### PA5_1 project repository link: [PA5_1 Project repository](https://github.com/IULIAN-COSTEA/PA5_1)
#
###### PA5_1 project jupyter notebook file link: [PA5_1 Jupyter notebook prokect file]((../blob/main/PA5_1.ipynb))
#
### Project conclusions
* Drivers that are visiting the bars more than 1 time a month and are over the age of 25, have pretty high coupon an acceptance rate, close to 70%. There is a significant corelation between number of monthly visits to the bars and the coupon acceptance rate.
* If the drivers are also accompanied by other persons (excluding kids) then the acceptance rate can be slighly improved.
* Age is not a relevant factor in cupon acceptance rate.
* Income level also shows an inverse correlation with cupon acceptance rate. However, further and more detailed analysis are needed to confirm the initial finding.
#
