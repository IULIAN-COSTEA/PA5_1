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
###### Project jupyter notebook file: [PA5_1 Jupyter notebook file](https://github.com/IULIAN-COSTEA/PA5_1/blob/main/PA5_1.ipynb)
#
### Project conclusions
 * Drivers that are visiting the bars more than 1 time a month and are over the age of 25 have a hight acceptance rate, close to 70%. There is a strong corelation between the number of monthly visits to the bars and the cupon acceptance rate (for more details please check section 4 charts and conclusions)
 * If the drivers are also accompanied by other persons (excluding kids) then the acceptance rate can be slighly improved (for more details please check section 6 above). It seems that there is a relative weak correlation betwwen the accompaning person and the coupon acceptance rate. Next step: >> Explore for ther this potential correlation between those categories.
 * Although there is a correlation between age and coupon acceptance, for the analysis we have conducted age was not relevant. This can be seen ithe the chart above. Nevertheless, there is a deacrease of acceptance rate in the older age groups and this might deserve some additional analysis. Next steps: >> To analyse correlation between age groups and coupon acceptance rate. 
 * Income level also shows an inverse correlation with cupon acceptance rate. However, further analysis are needed to confirm the initial finding. Next step: >> To calculate the correlation between income groups and the coupon acceptance rate.
#
