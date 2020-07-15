# What-Makes-Restaurants-Successful-
This project was completed as part of the "Data Analytics" course in my Master's program. Our team downloaded and cleaned restaurant data obtained from the Yelp Dataset Challenge and then completed exploratory data analysis on the cleaned dataset. The goal of the project was to build machine learning models that can help predict the success of a new restaurant from the perspective of the owner. During EDA, our team found that there was insignificant correlation between review count and average rating. Since restaurant success was defined from the owner's perspective, our team brainstormed a success metric that is more representative of customer volume: normalized review count per capita which is explained in the presentation slides. Feature selection was then implemented to pick out restaurant attributes which would have an effect on the success metric. After testing both regression and classification models, a fully connected neural network with a softmax classifier achieved an optimal accuracy of 75%. 
