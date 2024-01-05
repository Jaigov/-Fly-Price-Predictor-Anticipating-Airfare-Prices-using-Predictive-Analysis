# Fly-Price-Predictor-Anticipating-Airfare-Prices-using-Predictive-Analysis

Fly Price Predictor: Anticipating Airfare Prices using Predictive Analysis

• Led a team of 4 to build predictive flight price models using advanced machine learning algorithms namely Linear Regression, KNN Regressor, Random Forest &amp; XG Boost with a prediction accuracy of above 90% for each model
• Enhanced the model using fine-tuning and ensemble techniques, achieving an accuracy of 97.6%, enabling data-driven decision-making for airlines in pricing strategies and better cost structure

Collaborators: 
Aishwarya Jayant Rauthan
Jaishankar Govindaraj
Jasmine Gohil
Mahika Bhartari

Data Source:
Easemytrip is an internet platform for booking flight tickets, serving as a gateway for potential passengers to purchase tickets. A thorough study of the data will aid in the discovery of valuable insights that will be of enormous value to passengers. (link - https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction)

Objective:
Our objective is to create a robust predictive model that can forecast the pricing dynamics of air tickets for domestic flights within India. This model aims to offer valuable insights into the factors affecting ticket prices.

Motivation:
We all are aware that the travel sector was adversely affected due to COVID-19. As soon as things started getting back to normal, the prices surged and still remain at an all time high especially for international travels. Our model will have real world significance and practical applications attached as it will train on a recent post-COVID dataset i.e. from February 11th to 31st March 2022. Ultimately our goal is to bring out innovative findings that enhance the existing body of knowledge in the airline industry.

Executive Summary:
In the times where the aviation industry is characterised by a dynamic environment and ever-changing demand, our Fly-Price predictor model aims to solve this question for consumers, including YOU! "When should I book my flight to get the cheapest one?" We have constructed five models (Multiple Linear Regression, Random Forest, XG Boost, SVM, KNN) and selected the most optimal model among them, with high accuracy tailored for forecasting price levels in the airline sector in India. Using built in machine learning algorithms in sci-kit learn and data analysis methodologies including hyper parameter tuning, ensemble methods we wanted to deliver a solution that consumers can use while booking price tickets that suits their economical needs. Our model has real world significance and practical applications attached as it has been trained on a recent post-COVID dataset i.e. from February 11th to 31st March 2022. The airline companies can utilise our insights to make informed business decisions.

Challenges: 
Our datatset contains 12 columns and 300261 rows which posed difficulties during model building and hyperparameter tuning processes. To tackle this issue, we tried to optimize our parameters which therefore resulted in bettering the computational time.
For the date, dep_time, arr_time columns, numeric features of these had to be extracted in order to make these features relevant for our model. This issue required deliberations for which we extracted days (day of the month) out of the date column, hour of the day from the dep_time and arr_time columns for them to be included in the modelling process.
While building the Support Vector Machine Model, we encountered a negative R-squared value, due to which we had to rule the model out of consideration.

Conclusion:
Through our analysis and machine learning modelling on the dataset, it could be observed that Random Forest Regressor and XGBoost Regressor models worked the best for us. These models performed even better after performing fine-tuning techniques, further improving the accuracy. These models were chosen based on accuracy metrics like R-square and RMSE, outperforming other regression algorithms like Linear Regression, K-Nearest Neighbours and Support Vector Machines. Out of these two, XGBoost was selected as the final modelling algorithm due to its high accuracy metrics and decently low computational time, making it an optimal choice from our repertoire. Further, this algorithm can also be utilised by airline companies in order for them to make data-driven business decisions by tuning their air fare.

Factors such as the continued existence of loss-making carriers, a bloated cost structure, and vulnerability to external events pose significant obstacles to profitability in the airline industry.

Airlines can address these challenges by leveraging Machine Learning models to implement dynamic pricing strategies. These models consider various factors such as the number of layovers, seasonality, and historical pricing to optimize their pricing structures.

Airlines face substantial costs, with labor and fuel being the majority. Labor accounts for approximately 31% of operational expenses, followed by fuel at 22%.While a few low-cost airlines have successfully achieved consistent profits, profitable airlines are generally rare. Forecasting the optimal future ticket prices becomes crucial for maintaining a balance between revenue optimization and offering reasonable ticket prices to customers.

Given the high competitiveness of the airline industry, it is imperative for airlines to analyze competitors' strategies. Adjusting prices well in advance based on these analyses is essential for maintaining a competitive edge and meeting market demands.

The integration of Machine Learning for dynamic pricing, a focus on optimizing cost structures, and a strategic approach to pricing in the competitive landscape are vital components for addressing challenges and enhancing profitability in the airline industry.
