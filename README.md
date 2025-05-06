# Required Assignment 5.1: Will the Customer Accept the Coupon?

## Summary of Findings

This project analyzes the factors influencing the acceptance of various coupon types, particularly focussing on bar
coupons and carry-out coupons. The analysis uses visualizations and statistical summaries to identify patterns in coupon
acceptance.

The findings suggest that various parameters influence coupon acceptance, including the type of coupon, the customer's
demographic information, and the context in which the coupon is presented.

## Data Source

This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk.
The dataset is attached in the `data` folder of this repository.

The dataset is named `coupon_data.csv`.

### Key Findings:

These findings are based on the findings section in the submitted jupyter notebook.

1. **Bar Coupons**:
    - Bar coupons account for 16% of all distributed coupons.
    - Bar coupons have a low acceptance rate of 41% and a high rejection rate of 59%.
    - Drivers without children in the car are more likely to accept bar coupons.
    - Drivers aged 26-30 who visit bars 1-3 times a month are more likely to accept bar coupons.
    - Drivers with passengers (not kids) and occupations outside farming, fishing, or forestry show higher acceptance
      rates.
    - Income level shows correlation with acceptance rates.
    - There is a relationship between the drivers with lower income who frequently visit cheap restaurants also show a
      higher acceptance rate for bar coupons.


2. **Carry-Out Coupons**:
    - Carry-out coupons have the highest acceptance rate at 74% and the lowest rejection rate at 26%.
    - Higher acceptance rates among younger adults (21-30) and middle-aged adults (31-45)
    - Drivers are more likely to accept these coupon if they are in middle-income groups (`$25k-$50k`)
    - Education level has a positive correlation with acceptance rates. Higher acceptance among those with some college education or bachelor's degree are more likely to accept than other degrees.
    - Acceptance is higher during morning and evening hours, especially around 7AM and 6 PM.
    - Sunny weather positively influences acceptance rates.
    - Drivers with a higher frequency of carry-out visits (1-3 times a month) are more likely to accept carry-out
      coupons.
    - Drivers accept carry-out coupons more when they are alone in the car.
    - Drivers accept carry-out coupons when they are not in a hurry and have longer expiration of 1 day than shorter 2
      hours.


3. **Other Findings**:
    - Carry out coupons are accepted more based on driver's convenient timing and location factors. 
    - Bar coupons are more influenced by demographic or social factors.


4. **Recommendations**:
    - Driver's age (26 - 30) plays a crucial role in coupon acceptance. Future research should focus on the age group of drivers and their
      preferences.
    - Bar coupon acceptance is influenced by the presence of children in the car unlike carry-out coupons. Future research should
      focus on the impact of children on coupon acceptance.
    - Target younger adults (21-30) and middle-aged adults (31-45) for both carry-out coupons and bar coupons.
    - Target middle-income groups (`$25k-$50k`) for carry-out coupons.
    - Target drivers with some college education or bachelor's degree for carry-out coupons.
    - Target drivers who are alone in the car for carry-out coupons.
    - For bar coupons, target drivers with lower income who frequently visit cheap restaurants.
    - Target drivers with occupations outside farming, fishing, or forestry for bar coupons.
