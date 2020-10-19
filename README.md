# NYC-Shootings-since-2005
​
​
​
​
# Project 2 - Team 3
​
## Team Members
* Steven Cherry II
* Sasha Flores
* Fred Fu
* James Menacho
---
​
# NYC Shootings since 2005
​
---
​
## Project Goal
 
* Use Statistical Model for Predictive Purposes
​
**What are we trying to solve for?**
​
- [X] Seek to Use the Most Relevant Features of Shootings Dataset to Predict Future Period Shootings
- [X] Combine Macroeconomic Data along with Primary Dataset to deduct causality between economic datapoints and NYC shootings
- [X] Utilize NLP to Assess News Story sentiment and Marry to the Rest of the Dataset
​
## What is hypothesis?
​
Exhibit a link between NYC Shootings and the Economic Cycle
---
​
## Process
​
* Bring in and Clean Data
* Assess various Features in dataset and attempt to intuitively maintain Relevant Ones
* Visualize correlation Matrix
* Run Linear Regression and Assess Model
* Perform PCA to determine Correct Features to be Used
* Visualize Uplift in Model Change
* Run and Evaluate Decision Tree Regression
* Run and Evaluate Random Forrest Regression
* Run and Evaluate Gradient Boosting Regressor
* Change Feautres to be more Intuitive and Discrete
* Rerun and Evaluate Linear Regression, Decision Tree, and Random Forrest Models
* Perform NLP Analysis and attempt to incorporate into Dataset 
​
---
## What Data/Modeling issues did we Run into?
​
![Regr](DeadEnd.JPG)
​
* NLP - API Data Permissioning and Inability to Attain Long-Term Historical Data
    * NewsAPI, NYT, and Bloomberg deadends
​
* Initial Regression Model proved to be too perfect because of Linearity between Features and Labels
​
![Regr](regression.JPG)
​
## Where did we get our data?
​
NYC ????????????
Bloomberg
​
## Caveats and Considerations
* General Economic Prosperity enjoyed over scope of Dataset
* Different Crime-battling regimes and Methods (i.e. Stop-And-Frisk)
* Is Social Unrest that is Independant of Economic Malaise skewing Data?
