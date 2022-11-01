# Cryptocurrencies - Module 18 Challenge
---
## Background
You have been asked by Martha and one of our most important clients, Accountability Accounting to determine a list of tradeable cryptocurrencies via an automated system.  They would like the currencies grouped into a classification system for their new investments.

### Step 1: Import and Clean the Data
  
After the data is imported it is discovered that there is a column titled "Unamed:0" that has data that could cause a problem later on so we will need to drop it from our DataFrame.
  
![data_imput.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/data_input.png)
![data_clean.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/data_clean.png)

The data is cleaned even more by keeping active Algorithms, only actively trading and has no blank values.

### Step 2: Reduce the dimensions to the three principal components

![PCA.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/PCA.png)

### Step 3: K-Means Elbows

![Elbow_Curve.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/Elbow_Curve.png)

### Step 4: Clusters are fun

![3D_scatterclusters.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/3D_scatterclusters.png)
![hvplot.png](https://github.com/Normanfamdamly/Cryptocurrencies/blob/main/Images/hvplot.png)
