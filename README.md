# **Cryptocurrency Clustering**
In this challenge, you want to propose a novel approach to assembling investment portfolios that are based on cryptocurrencies. Instead of basing your proposal on only returns and volatility, you want to include other factors that might impact the crypto market—leading to better performance for your portfolio.

As a result, this project utilizes machine learning to cluster cryptocurrencies using the K-Means method. The cryptocurrencies are clustered by their performance, and the optimal value for k was determined using the Elbow Curve method. The optimal value for k is seen on the line graph where there is a bend, or elbow displayed in the line. Adding additional clusters beyond this point will not have a large affect in decreasing the inertia. This project applies the K-Means algorithm to two different data types, the original data and the PCA, or Principal Component Analysis.

---
## Technologies
This application is developed on the *Python 3.7.11 version* 
Jupyter Lab Notebook that is an open sourced, web based user interface for software design, coding, visualization and documentationis is used for running the program that incorporates the following required dependencies:

**Pandas**: A software library that allows to import functions needed to program appliation for financial analysis.

**hvplot**: A software library that provides a high level plotting API built on HoloViews that provides a general and consistent API for plotting data in all the abovementioned formats.

**Path**: A software that implements path objects as first-class entities, allowing common operations on files to be invoked on those path objects directly.

**sklearn**: A software with simple and efficient tools for predictive data analysis · Accessible to everybody, and reusable in various contexts · Built on NumPy, SciPy, and matplotlib.


---
## Installation Guide
The following installation must be performed before running the program:

*Install Jupyter Lab*

*Install -U scikit-learn*

*Install -c pyviz hvplot*

---
## Usage
This section is an explanation of how to use this program: 

We start this application by importing all the necessary libraries, dependencies and data.First, read the “crypto_market_data.csv” file from the Resources folder into a DataFrame, and use index_col="coin_id" to set the cryptocurrency name as the index. 
Next, use the StandardScaler module from scikit-learn to normalize the CSV file data. This will require you to utilize the fit_transform function.
After, you will use the elbow method to find the best value for k for the original data.
Next, you will use the K-Means algorithm with the best value for k found in the previous section to cluster the cryptocurrencies according to the price changes of cryptocurrencies provided.
Next, you will perform a principal component analysis (PCA) and reduce the features to three principal components.
After, you will use the elbow method to find the best value for k using the PCA data.
Next, you will use the PCA data and the K-Means algorithm with the best value for k found in the previous section to cluster the cryptocurrencies according to the principal components.
Finally, you will visually analyze the cluster analysis results by contrasting the outcome with and without using the optimization techniques.

---
## Contributors
*Contributors*: Saina Azimi

*Email*: azimi.sainaa@gmail.com

*LinkedIn*: https://www.linkedin.com/in/azimi-saina/ 

---
## License 
UC Berkeley

----