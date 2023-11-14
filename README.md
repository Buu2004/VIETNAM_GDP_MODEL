# VIETNAM_GDP_MODEL
My name is Nguyen Duc Minh. I am the first-year student at FPT University, Da Nang campus. <br />
This is my machine learning project to construct a relationship between GDP of Vietnam
and some factors that can significantly affect its growth. <br />
After researching knowledge about GDP in Economics area, I chose:
1. Gross capital formation at current price
2. Final consumption at current prices
3. Export OF goods and services at current prices
4. Import OF goods and services at current prices
5. Gross domestic product at current prices divided by economic sector
6. Consumer Price Index (CPI) 
7. Producer Price Index (PPI) 
8. Exchange Rate 
9. Foreign Direct Investment (FDI) 
10. Labor Force 15 Years and Older
11. Natural Disaster 
12. Population <br />
Thanks to scikit-learn Python library, I constructed 3 machine learning models which are Linear Regression, Ridge Regression and Support Vector Regression. <br />
I ultilized GridSearchCV to find out the most effective parameters of each model. After that, I visualized the mean errors
made by each model in the validation sets:
<img width="734" alt="image" src="https://github.com/Buu2004/VIETNAM_GDP_MODEL/assets/130444437/a448c024-1a0e-4027-a625-5fb258db7557"> <br />
Finally, I visualized the RMSE and RMSPE made by each model in the test set:
<img width="728" alt="image" src="https://github.com/Buu2004/VIETNAM_GDP_MODEL/assets/130444437/274ff94a-12e1-43a8-ac95-88a8528fd607">
<img width="365" alt="image" src="https://github.com/Buu2004/VIETNAM_GDP_MODEL/assets/130444437/bfe30f46-38d2-44ec-be74-b62101ca719e"> <br />

I found out that the Linear Regression model has the best performance while constructing a model 
showing the relationship between Vietnam's GDP and some factors that can greatly affect its promotion.


