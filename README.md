## Linear Regression Data Set

This data set models a company based out of New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.

The company is trying to decide whether to focus their efforts on their mobile app experience or their website.

## Analyzing Data

I worked with the data set that includes (fabricated) customer info, such as Email, Address, and their color Avatar. Then it also has numerical value columns:

![img_1](https://user-images.githubusercontent.com/33237727/41071114-540939a6-69c4-11e8-9fe8-8c12a1d13ead.JPG)

Avg. Session Length: Average session of in-store style advice sessions.
Time on App: Average time spent on App in minutes
Time on Website: Average time spent on Website in minutes
Length of Membership: How many years the customer has been a member.

# Exploring the Data Set

Did analysis between time spent on the web site and the yearly amount spent:

![img_5](https://user-images.githubusercontent.com/33237727/41071120-58293e28-69c4-11e8-8fa5-2c1654599f40.JPG)

Analysis between time spent on the app and the yearly amount spent:

![img_4](https://user-images.githubusercontent.com/33237727/41071118-573061f4-69c4-11e8-8098-f10d13caae9e.JPG)

And a linear plot between the length of membership and yearly amount spent

![img_6](https://user-images.githubusercontent.com/33237727/41071122-59326092-69c4-11e8-84f9-c7984783a1ae.JPG)

## Training and Testing the Data Set

Scikit Learn packages were used to split the data and create a linear regression model

![img_2](https://user-images.githubusercontent.com/33237727/41071115-551e0eac-69c4-11e8-8ccb-7a541abf1450.JPG)

I created a scatter plot which showed the real test values vs. our predicted values:

![img_7](https://user-images.githubusercontent.com/33237727/41071123-5a1f899e-69c4-11e8-9389-fe3a86e932f0.JPG)

And the coefficients data frame:
![img_3](https://user-images.githubusercontent.com/33237727/41071117-561b8636-69c4-11e8-9448-2ac0b8a79695.JPG)
