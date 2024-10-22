**INTRODUCTION**

Regression is one of the most important models to follow when we try our hand at prediction, be it the value of something or the predicting the decrease or increase that might take place in the future. Through this project, I am looking to make use of one such algorithm to find the market value of footballers.
I chose this project as it is a combination of two things that I have the most interest in, Machine Learning & Football. This provides me with the opportunity to professionally work on something I have been a follower of since my childhood, outside the world of Tech.


**STEPS INVOLVED**

_**WEB SCRAPING DATA:**_
After choosing the problem that I wanted to work on, the next thing that I had to do was to find the data to work with. With the help of Web Scraping using Python BeautifulSoup, I extracted the relevant data from a website that contained player stats from the latest edition of the FIFA game series, which is the closest thing to evaluating player skills numerically.


_**DATA CLEANSING:**_
Any project in machine learning is incomplete without the data cleansing of data, as it helps to remove the irrelevant data and gets more accurate results. The data we obtain after web scraping is in a raw form and requires a lot of cleaning before it can be used anywhere.


_**EXPLORATORY DATA ANALYSIS:**_
After cleansing the data, the net step required me to explore, understand and show the data in a presentable form. At this step, I extracted and ranked various statistics like Most Valuable Players, Highest Rated Players, Most Valuable Clubs, Mean Value of Positions, etc. I also used this data to design Mean Value Graphs, Player Position Distribution, etc.


_**CONSTRUCTING THE MODEL:**_
Using the Regression Models to predict continuous value, we predict the value of variable Y based on the input variable X. The linear relationship between the target and predictor is what makes it a linear regression.


_**EVALUATING THE TEST RESULTS:**_
At this step, we evaluate the test results that we obtained and the graphs we plotted after constructing the model. After the construction of a few graphs, I decreased the number of features being used with the help of the correlation matrix. After the features were narrowed down to 7, I constructed a heatmap and a pairplot. This was then followed by the finding of the results of OLS Regression. Since, I narrowed down the number of features being used to seven, the level of clarity in the model increased considerably.
In order to compare the results for Ridge, Lasso and Polynomial regression, I had to split my data into train, test and validation sets respectively. The best results are obtained at Degree 2 Polynomial Regression which is then followed by Linear Regression. Results of the Lasso Regression indicate that it was an overfitting problem, while Ridge results are identical to the ones obtained in Linear Regression.


_**CONCLUSION:**_
Here, I took multiple assumptions(5) to compare the models and the actual results to the predicted ones. After plotting relevant graphs and getting the test results, I compared which players are the most overvalued and which players are undervalued. Finally, I predicted the player’s value based on his stats and data in Fifa21.


