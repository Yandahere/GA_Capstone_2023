# Startup Success Prediction
## Yanda DSI 33
 # Table of contents
1. [Background and Problem Statement]
2. [Data Cleaning]
3. [EDA and Data Visualisation]
4. [Modelling]
5. [Conclusion and Recommendations]
# Background
Singapore is often considered a startup-friendly environment due to its pro-business policies, highly educated workforce, and strong support from the government. The city-state has a developed infrastructure and a stable political environment, which makes it an attractive location for entrepreneurs to start and grow their businesses.

Singapore has directed a strong focus onto technology and innovation, with it's government investing heavily on initiatives to promote the growth of the startup ecosystem. The government's [StartupSG](https://www.startupsg.gov.sg/) program provides funding, mentorship, and networking opportunities for entrepreneurs, and there are also numerous co-working spaces and incubators available for startups to use.

There are several challenges that start-ups in Singapore may face, some of which include:

1. Access to funding: Securing funding can be a significant challenge for start-ups in Singapore, as investors may be hesitant to invest in early-stage companies with untested business models.

2. Talent attraction and retention: Singapore has a highly competitive talent market, which can make it difficult for start-ups to attract and retain top talent.

3. Intense competition: Singapore is home to a large number of start-ups and established companies, which can make it difficult for new businesses to stand out and gain market share.

4. High operating costs: Singapore has one of the highest costs of living in the world, which can make it expensive for start-ups to operate and attract employees.

However, in spite of the many challenges, Singapore is widely regarded as one of the best environments for startups. In addition to government support, there are also many venture capital firms and angel investors in Singapore who are actively looking to invest in promising startups. The city-state has also attracted many multinational corporations who have set up innovation centers or corporate venture arms in Singapore, which provide opportunities for collaboration and partnerships for local startups.

Singapore has high cost of living compared to other Southeast Asian countries, which can be a barrier for some startups. Starting up as a innovator or investor can be a daunting task to many, due to the high demands of a start up.

For the first phase of the project, I would be using available dataset from the US as a proof of concept. Subsequently, with more time we would scrape our own dataset with local data.
For this capstone project, supervised machine learning will be done.
# Problem Statement:
Nurturing the newest unicorn in a sea of start ups can be challenging to early start ups and new investors. What can investors and entrepreneurs look out for to predict a success of a start up?
# Model Summary
|Model|Train Score|Test SCore|Specificity|F1 Score|
|---|---|---|---|---|
|**KNN**|0.85|0.76|0.49|0.69|
|**Logistic Regression**|0.84|0.81|0.63|0.77|
|**Adaboost**|0.89|0.83|0.65|0.79|
# Conclusion
As we can see the best performing model is `Adaboost` after hyper parameter tuning in predicting the success of a start up. 
Majority of the start ups in the US dataset tend to be in software, web and mobile. Out of these categories, travel, news and analytics have the highest success rates.
By analyzing various data points such as funding history, team composition, and industry trends, the model can provide insights into the likelihood of a startup's success.
In conclusion, a classifier model can be a valuable tool for predicting the success of a startup, but it is important to be aware of its limitations. The model's predictions are only as good as the data it is trained on, and it may not take into account other important factors such as market conditions and timing. Additionally, startup success is a multidimensional construct and depends on various factors such as the quality of the management team and the company's ability to adapt to changing market conditions.

Recommendations:
Investors and new startups should focus on securing funding and researching into trending businesses. Marketing and social media are important once launch of the product or service to increase visibility of the product. Products or services can also offer attractive bundles or offers to draw in crowd during launch and retain a customer base for future scaling of the business. 
# Limitations:
1. Data availability and quality: The model is only as good as the data it is trained on. If the data is incomplete, inaccurate, or biased, the model's predictions will also be affected. Additionally, startups in their early stages may not have enough historical data available to train a model on. The model is operating on a dataset of startups in the 2000 to 2010 period. Due to pandemic, the nature of all business have shifted and a refocus of priority and consumer habits has changed the success of different start ups. Without time constraint, further data collection specific to Singapore can be scrapped and collected, as success rates of start ups in different country can be much more varied. 

2. Lack of context: A classifier model can only make predictions based on the data it is given, and may not take into account other important factors such as market conditions and timing.

3. Human factors: A startup's success also depends on various human factors such as the quality of the management team and the company's ability to adapt to changing market conditions which make these factors hard to quantify.
