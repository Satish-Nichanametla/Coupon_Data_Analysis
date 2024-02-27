**Overview**:
“Will a customer accept the coupon?” The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not. 

**Data:**
This data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, passenger, etc., and then asks people whether they will accept the coupon if they are the driver. Answers given that the users will drive there “right away” or “later before the coupon expires” are labeled as “Y = 1”, and answers “no, I do not want the coupon” are labeled as “Y = 0”. There are five different types of coupons—less expensive restaurants (under $20), coffee houses, carry out and take away, bars, and more expensive restaurants ($20–$50).

**Findings:**
1. **Common trends**
   - Acceptance rate is better if destination is not an urgent place
   - There are more chances of accepting coupon when the weather is sunny
   - Acceptance rate is low if coupons gets expired in couple of hours
2. **Bar Coupon**
   - Approximately 41.2% of bar coupons were accepted
   - Drivers who go to bar more than once and without kids in the car are more likely to accept coupons.
   - High chance to accepting coupon when passenger is a friend.
   - Males has higher chance of accepting 
3. **Coffee House**
   - When its raining acceptance rate is high in this category when compared to others.
   - Popular among young people(below 21)
4. **Restaurant(20-50)**
   - Acceptance rate is high at 10AM and low at 10PM

**Recommendations to improve acceptance rate**
1. Avoid issuing coupons when its snowy. When its raining issue Coffee House coupons. Warm weather is in general good for all types of coupons
2. Issue restaurant and coffee coupons in the morning/afternoon and bar coupons in the evening. 
3. Less chances of accepting coupons if expiry is within 2h. Suggest to increase the expiration duration.
4. Issue more bar coupons to males and who are single
5. Avoid issuing coupons if destination is more than 25min
   
**Links:**
Link to report - 
