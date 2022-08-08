INTRODUCTION

Although researchers (Pizzol et al., 2018; Karoubi et al., 2016; Fabris, 2019; Yang et al., 2015) have used different terms such as digital payment, electronic money, cashless payment, which can all be reffered to as online payment. Online payment can be defined as payments made using electronic device and channels with the aid of the internet. Over the years, studies (Zhang et al., 2018; Laukkanen and Kiviniemi, 2010; Rehncrona 2018) have focused largely on the benefits related of online payment such as reduced transport cost, service delivery regardless time frame, reduced human resources etc. However, fraudulent transactions are increasing now a day in large amounts which have caused great losses for some banks and their fin-tech consultants. 
In line with the Theory of Perceive Risk (TPR), which states that risks entails benefits this means; there is a likelihood for loss in the pursuit of a desired outcome when using an online payment service. To this backdrop, this study, employed the use of python to explore an Online Payment Fraud Detection Dataset using models to predict fraud and fraud less transactions with regards the type of transaction, amount, and changes in the account balance of the customer (sender and recipient). The outcome from this would help BB Plc make informed decision on appropriate risk control measures whilst providing optimum service delivery to online customers. 

METHODOLOGY

Step 1. Lunch the jupyter notebook for python
Step 2. Import necessary python libraries pandas, numpy, seaborn, matplotlib.pyplot, ploty.express etc. to enable univariate and bivariate analysis of data.
Step 3. Read the csv dataset on python
Step 4. Check the dataset content and info
Step 5. Exploratory Data Analysis
•	Checking correlations
•	Transforming categorical variables 
Step 6. Splitting, training and testing learning models 
While carrying out analysis, I had challenges in fitting the models accurately. 


FINDINGS
The mean amount transacted and steps taken to execute an initaited transcation via the online payment was 158,666 and 26 steps.
Of all five different types of transction, more than one-third of the various types (35.6%) are Cash-out while 0.6% are Debit transactions.
There is a positive but weak correlation between the amount transacted and the new balance of the recipient customer.
The higher amounts transacted online were of the TRANSFER forms.
The models (Decisiom Treee and Random Classifiers) were 99% accurate.
Uisng the KNeighborsClassifier; the model predicted that are fraudulent only 13% are were actually captured as fraudulent.
Out of all the predicted fraudulent transactions, the modle only predictied this outcom 65%  wecorrectly.

REFERENCES
Karoubi, B., Chenavaz, R. and Paraschiv, C. (2016), “Consumers’ perceived risk and hold and use of payment instruments”, Applied Economics, Vol. 48 No. 14, pp. 1317-1329, doi: 10.1080/00036846.2015.1100249.
Fabris, N. (2019), “Cashless society: the future of money or a utopia?”, Journal of Central Banking Theory and Practice, Vol. 8 No. 1, pp. 53-66, doi: 10.2478/jcbtp-2019-0003.
Yang, Q., Pang, C., Liu, L., Yen, D.C. and Tarn, J.M. (2015), “Exploring consumer perceived risk and trust for online payments: an empirical study in China’s younger generation”, Computers in Human Behavior, Vol. 50, pp. 9-24, doi: 10.1016/j.chb.2015.03.058
Zhang, T., Lu, C. and Kizildag, M. (2018), “Banking ‘on-the-go’: examining consumers’ adoption of mobile banking services”, International Journal of Quality and Service Sciences, Vol. 10 No. 3, pp. 279-295, doi: 10.1108/IJQSS-07-2017-0067
Laukkanen, T. and Kiviniemi, V. (2010), “The role of information in mobile banking resistance”, International Journal of Bank Marketing, Vol. 28 No. 5, pp. 372-388, doi: 10.1108/02652321011064890
Rehncrona, C. (2018), “Young consumers’ valuations of new payment services”, International Journal of Quality and Service Sciences, Vol. 10 No. 4, pp. 384-399, doi: 10.1108/IJQSS-11-2017-0111.
Pizzol, M., Vighi, E. and Sacchi, R. (2018), “Challenges in coupling digital payments data and input–output data to change consumption patterns”, Procedia CIRP, Vol. 69, pp. 633-637, doi: 10.1016/j.procir.2017.11.004.
