# Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning

**Mini Project File Link is** <a href="https://drive.google.com/file/d/1BqzY9_Q5Pc7Njh7-x3Hz5dQfzHc4BmPM/view?usp=sharing">Here</a>

## Customer Type and Behaviour Analysis on Advertisement
- Statistical Analysis
  
1) Numerical Features
     
     ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/04044494-2c5a-4e13-95f5-551d23fad062)

     - The time that users spend on the website has an average of 64 minutes per day with a minimum of 32 minutes and a maximum of 91 minutes.
     - User age has an average of 36 years with a minimum of 19 years and a maximum of 61 years.
     - The average user income is 3.84 hundred million with a minimum of 97 million and a maximum of 5.56 hundred million.
     - User internet usage has an average of 179 minutes per day with a minimum of 104 minutes and a maximum of 267 minutes.

 2) Categorical Features

    ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/203fbc89-84ff-403d-8b8f-838f2b21d098)

    ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/9b3236ac-0cef-47bf-89e7-fdbee8721009)

    - There is a feature called Male (should be Gender, it will be preprocessed) with the highest frequency being Female.
    - The Timestamp feature (dtypes will be preprocessed to become a datetime) with the most frequency is May 26, 2016 at 15:40.
    - The Clicked on Ad feature has the same number of users who do not click ads and those who click ads.
    - The City feature has the largest number of users in the cities of Surabaya and Bandung.
    - The Province feature has the highest number of users in the Special Capital Region of Jakarta province.
    - Category features have the highest number of users who use automotive.
      
- Univariate Analysis

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/745fed15-9f52-4d49-a612-1fd8f5aadb47)

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/f0b0e6b5-bf73-4afb-9f3c-eab013b48aa2)

  - In the boxplot, the numerical features Daily Time Spent on Site, Age, and Daily Internet Usage have no outliers, while the Area Income feature has an outlier.
  - The Daily Time Spent on Site and Daily Internet Usage features have a distribution close to the normal distribution.
  - The Income Area feature has a negative skewed or left skew distribution, meaning that most customers have low incomes compared to high incomes.
  - The Age feature has a positive skewed or right skewed distribution, meaning that most customers are more than 30 years old compared to customers who are less than that.
    
- Bivariate Analysis

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/2a438c91-e006-421d-a1bb-7f4111de012a)

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/c51c67e8-c02a-4d1d-bd17-ba4c5fefe440)

  - The more time spent visiting a website, the more customers tend not to click on ads. Vice versa, the less time spent visiting a website, the customer tends to click on ads.
  - Customers who click on ads are on average 40 years old and do not click on ads on average 30 years old.
  - Active users have a tendency not to click ads compared to inactive users (users who use the internet not too long).
  - Customers who have large income tend not to click on ads.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/9c6d8406-a8e7-47cf-8d45-8051c7c8de82)

  - The time spent on using the website has a skew distribution. Users who click on ads have a right skew distribution, meaning that the time spent tends to be faster. This is in contrast to users who do not click on ads having a left skew distribution, meaning that the time spent tends to be long.
  - The age of users who click on ads has a normal distribution, meaning that the ages of users who click on ads are evenly distributed from various age groups. Meanwhile, the age of users who do not click on ads tends to be younger (under 40 years old).
  - The average income of the geographic area of customers who click on ads has a normal distribution, meaning that the distribution of users who click on these ads is evenly distributed across various income variations. Meanwhile, users who do not click on ads tend to have high income (the distribution is skew left).
  - The longer the use of the internet every day, the lower the tendency of users to click ads. Meanwhile, the faster the internet is used every day, the lower the tendency for users to click on ads.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/c8e13adc-6d17-4640-91a4-53210eeca41a)

  - The less time spent on the website, the less often the internet is used, and the older the user is, the user will have a greater tendency to click on ads.
  - Conversely, the younger the user, the more time spent on the website, and the more often they use the internet, the user will have a greater tendency not to click on ads.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/b00d2f9b-fd23-4355-9aca-91c2b751ed11)

  - The less time spent on the website and the less often you use the internet, the more users tend to click ads.
  - The longer the time spent on the website and the more frequently the internet is used, the less likely users are to click on ads.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/4659ff93-94de-47a9-b714-54292fcd18c9)

  - Women are more likely to click ads than men.
  - Three cities that have users clicking on ads more than those who don't click on them are Bandung, Surabaya and Bekasi respectively.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/920f22ac-f37b-4760-8c61-b83af035d31e)

  - West Java Province has the highest number of users who click on ads compared to those who don't.
  - The most categories that have a greater number of ad clicks than not clicks are automotive. Meanwhile, the health category is the highest category which has a greater number of unclicked ads than clicked.

- Multivariate Analysis

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/e4362d28-a321-4f5d-b7d0-204269fda05d)

  - Daily internet usage has a high positive correlation with daily time spent on the website (51%). The more frequent use of the internet, the longer time spent on the website as well.
  - User age has a negative correlation with the other three features, namely the user's geographic average income, time spent on the website, and daily internet usage. User age that has a high correlation with these three features is daily internet usage (37%). The older the user is, the less often daily internet use is done.

## Data Cleaning & Preprocessing

- Handle Missing Value

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/f43b5b9e-5542-45b2-b8aa-4628e1bb7c1a)

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/f73efcfd-3bdc-4986-81cd-6d8211ba33d2)

  There are 4 features that have missing values, namely Daily Time Spent on Site with 13 data (1.3%), Area Income with 13 data (1.3%), Daily Internet Usage with 11 data (1.1%), and Male with 3 data (0.3%).

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/5d3766ef-bde1-4a7c-88c6-07cf360962a6)

  Fill in the missing value of numerical features using the median value because the median is relatively robust from the outliers (not affected by very high or low values) and does not affect the distribution of the data at the start.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/779a8931-aabe-47b2-96e1-ba5da30e8952)

  Filling in the missing value of categorical features uses the mode value, which is the value that appears most often in the Male feature. The mode for the Male feature is Female.

- Handle Outlier 

  **Before Handling Outlier**

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/7c4829f7-439d-4240-8780-191fd53ad121)

  There is an Income Area feature that has an outlier

  **After Handling Outlier**

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/f447c62d-d4bc-49ce-ac7f-a5caabbcc386)

- Feature Engineering
  
  - Feature Extraction

    ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/20341e93-a324-400a-9383-cd63c8f01818)

    The data type in the Timestamp feature is changed to a datetime data type, which was originally an object data type. Then, feature extraction is carried out from these features into month, weekday, day, week, and year features.

   - Feature Encoding

     Prior to feature encoding, the Male feature was renamed to the Gender feature.

     ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/05fb9451-5fc5-4688-bb8a-0d18e1ef48d0)

     - Label Encoding

       ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/157ef91f-a914-48f7-870d-96be08cafc69)

       - In the Gender feature, the Male value is changed to 0 and the Female value is changed to 1.
       - In the Clicked on Ad feature, the No value is changed to a value of 0 and the Yes value is changed to 1.
         
      - One Hot Encoding

        ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/dae29d92-e760-47b1-8da5-cc85eed515f1)

        The feature that is used in One Hot Encoding is the category feature because it only has the least unique value, while the other two features, such as city and province are not done because if there are too many features, it can cause dimension curses which can reduce model performance.

        ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/c68467b4-e498-4c5e-8bc6-49f2322a065d)

        One Hot Encoding is done in the Feature category
        
   - Feature Selection

     ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/672a7d8e-9852-4842-8fd1-69ddefbbeb5b)

     The features used in the model are features of the numeric data type.

- Split Data

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/de2d6cf3-da9b-43a5-9c80-3c9156d6414d)

  The targeted feature is the 'Clicked on Ad' feature.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/ae21de94-91fc-47fe-a7bc-634e8b9f6dc1)

  Before splitting the data, the columns for the non-target features are standardized.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/0cf48ea4-4db4-49ea-93f9-8885a9f545ec)

  Split data was carried out with train data of 80% and test data of 20% of the total data

## Data Modeling

- Result of Experiment 1

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/8ae16233-75d1-4061-b0b0-88f62bc5fec8)

  The results of model performance using datasets without standardization are as follows:
  - Almost all models have performance results between the test and train that don't have a big gap.
  - The Random Forest model has the highest accuracy and recall.
  - If you want to use a faster time_elapsed to predict the model, then the Gradient Boosting model is another option compared to the Random Forest model.
  - The K-Nearest Neighbors model has the worst performance among other models.

- Result of Experiment 2

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/a8f76b8d-0dd6-47a6-a6b1-c6ad1b0dafac)

  The results of model performance using standardized datasets are as follows:
  - The model has better performance than the unstandardized model.
  - Among these models, Logistic Regression has an underfit model because the train value < test value on recall and accuracy.
  - The K-Nearest Neighbors model has quite good performance after standardization.
  - The model with the highest recall value and accuracy is the Random Forest model.
    
- Conclusion from The Result of Experiment 1 & 2
  
  The model chosen is the Random Forest model after being standardized because it has the highest recall value and accuracy compared to the other models.

- Confusion Matrix

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/67e10414-1e44-4cd2-895f-3e1dde8fd34f)

  - Data Train
    - Of the 395 actual data that clicked ad on the data train, there were 387 data predicted to click ad and 8 data predicted not to click ad (should have clicked but predicted the opposite).
    - Of the 397 actual data that did not click on ad in the data train, there were 392 data predicted not to click on ad and 5 data predicted to click on ad (should not click but predicted the opposite). As a result, the model performance is very good because it reduces the value of the prediction error in the actual data.

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/c9c67d40-902a-4e69-a93f-22550f081966)

  - Data Test
    - Of the 96 actual data that clicked ad on the test data, there were 93 data predicted to click ad and 3 data predicted not to click ad (should have clicked but predicted the opposite).
    - Of the 103 actual data that did not click ad on the test data, there were 100 data predicted not to click ad and 3 data predicted to click ad (should not click but predicted the opposite). As a result, the model performance is very good because it reduces the value of the prediction error in the actual data.

- Feature Importance

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/78021f29-a32c-45f2-b3bd-c97647d8514d)

  ![image](https://github.com/nunuufdlh01/Predict-Clicked-Ads-Customer-Classification-by-using-Machine-Learning/assets/89932073/40738b6a-daf1-4f91-91d0-6cb11074fe9c)

  Feature importance that influences whether or not a user clicks on an advertisement is Daily Internet Usage and Daily Time Spent on Site.
  - The lower the Daily Internet Usage, the more users click on ads, while the higher the Daily Internet Usage, the fewer users click on ads.
  - Likewise with the Daily Time Spent on Site. The lower the Daily Time Spent on Site, the more users click on ads, while the higher the Daily Time Spend on Site, the fewer users click on ads.

## Business Recommendation & Simulation

- Feature Importance

  Based on feature importance and EDA results, there are several things that should be recommended to increase customer interest in viewing advertisements:
  - In advertising products on a website, companies must pay attention to customer behavior as long as they spend time on the website. For example, a customer really likes things about sports, so the advertised product is a product about sports as well.
  - Displaying advertisements on the website is not recommended too often for customers who have income below 400 million. This is because customers who have nominal income tend not to click on ads even though the duration spent and internet usage on the website are high.
  - Customers aged 20-40 years tend not to like seeing product advertisements on a website, even though they tend to spend longer time on the website. His advice: because they tend to be the younger generation, the generation that tends to get bored easily if too many ads are displayed, it is best if the ad is displayed when they have repeated product searches for 2-3 consecutive days and the length of the product search exceeds the average duration. spent by other customers in general.

- Business Simulation

  For example, the number of users used is 1000 users with each user who clicks on ads and users who do not click on ads are the same, namely 500 users.

  - Initial assumptions:
    - The budget issued per user is IDR 500.00
    - The profit earned per user in each click of one ad is IDR 2,000.00
  - Calculation of costs:

    cost = budget * n_user

  - Before Using Machine Learning

    - Cost = IDR 500.00 * 1000 = IDR 500,000.00
    - Conversion rate = 50%, because out of 1000 users there are 500 users who click on ads
    - Revenue = IDR 2,000.00 * 500 = IDR 1,000,000.00
    - Profit = IDR 1,000,000.00 - IDR 500,000.00 = IDR 500,000.00

  - After Using Machine Learning

    - The conversion rate in the Random Forest model is 97%, meaning that out of 1000 users there are 970 users who click on ads

    So that,
    - the costs incurred remain the same, namely IDR 500,000.00. However:
    - Revenue = IDR 2,000.00 * 970 = IDR 1,940,000.00
    - Profit = IDR 1,940,000.00 - IDR 500,000 = IDR 1,440,000.00

  - Conclusion

    From the results of business simulations, if we don't use machine learning, the profit earned is Rp. 500,000.00, whereas if we have used machine learning, the profit obtained will increase almost 3 times from the profit obtained previously.

    So we can conclude that:
    
    machine learning can work well in increasing a company's profit.
  




