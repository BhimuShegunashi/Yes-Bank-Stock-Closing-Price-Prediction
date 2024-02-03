Problem Statement-
 Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

🏁 A bank plays an important role in maintaining the economical condition of the country. The Yes Bank crisis created panic among the people in March 2020 as it was the biggest private sector bank. The failure of a bank, be it a public sector bank or a private sector bank, can affect everyone. In March 2020, news came out that there is a high chance of a Yes bank collapse which caused panic among the depositors. The Reserve Bank of India decided to solve this issue. Reserve Bank of India superseded Yes Bank board of directors for a period of 30 days.
🚦Framing The Right Questions For The Analysis

As stated in the general problem statement and overall purpose of the project, 'create the regression model that can predict the closing price of the stock'. Before we get into the specifics of creating a machine learning model, it is crucial to define the questionaries. We therefore come up with the following set of questions after performing the initial inspection of the dataset.
Are there any outliers or anomalies in the data that need to be addressed.
How are the data points distributed across time?
What is the distribution of the stock prices for each feature (Open, High, Low, Close)?
Are there any unusual spikes or dips in the data that need to be investigated further?
Can we identify any potential outliers or anomalies in the data?
Is closing price of (n)th day impacts the opening price of (n + 1)th day?
Are there any significant differences between the different features of the dataset?
What additional insights can be gained by visualizing the data in different ways (e.g., scatter plots, box plots, heat maps, etc.)?
What is the overall trend of the stock prices over time?
Are there any seasonal patterns or trends in the data that can be observed?
Which features have the strongest correlation with the closing price of the stock?
How accurately can we predict the future closing prices of the stock based on past data?
Can the model be improved by adding additional features or applying different regression techniques?
What is the most optimal way to train and test the model?
How can the model be interpreted and applied in real-world scenarios?
