# phase2project

**Building a Multi-Variate Linear Regression Model using King County,House Prices Dataset**


**Introduction**

In this data science project, we aim to build a multiple linear regression model to predict house sale prices in King County, leveraging the King County House Sales dataset. The project's objective is to provide accurate estimates of property values to homeowners and potential buyers, enabling informed decision-making in the real estate market.

**Problem Statement**

-How can we make sure to maximize profitability when attempting to sell a home in King County

-Seach for auctionable insights that will serve to guide the sellers

-Develop an understanding of the dynamics of the house market which will drive calculated decisions

**Main Objective**

The purpose of this project is to come up with ways in which to maximize profitability for sellers attempting to sell a home in King County,WA. We will search for actionable insights that will serve guidance to these sellers, but we need a thorough understanding of the dynamics of the housing market in order to drive our calculated decisions.

**Experimental Design**

**.** Data Collection

**.** Read and check data

**.** Cleaning the data

**.** Exploratory Data Anaylsis

**.** Modelling

**.** Conclusions 

**.** Recommendations

**Data Understanding**

The King County House Sales dataset contains comprehensive information about house sales, including features such as the number of bedrooms, number of bathrooms, square footage of living space in the home, number of floors in the house, how good the overall condition of the house is, overall house grade which is related to design and construction, and year when the house was built. To better understand the dataset, we will perform exploratory data analysis, examine distributions, identify correlations, and assess feature importance.

**Business Understanding**

The real estate agency needs to understand the relationship between various features of the houses and their sale prices in order to provide accurate advice to homeowners. By performing multiple linear regression analysis on the King County House Sales dataset, the agency can identify which home renovation factors significantly impact the sale price.

**Data Cleaning and  Preparation**

This involves checking data to check if there exists any possible problems that makes data unsuitable for analysis.The problems may include missing data , duplicated data , handling categorical variables and obtaining the relevant subset from our dataset that are likely to have a significant impact on the target variable.Data cleaning and preparation done in our datasets include checking for missing values, dropping unnecessary columns, getting rid of duplicates,handling categorical variables and creating new dataframes that suit our study including subsetting our datasets.Each datacleaning process is described in details in each cell based on the dataset.

Feature Selection:

Selection of relevant features that are likely to have a significant impact on the target variable (sale price) has been done. Consider both numerical and categorical variables based on domain knowledge and correlation analysis. Drop any unnecessary or redundant columns.I will focus on a subset of the overall dataset.These features are:

price: sale price which is our prediction target

bedrooms: number of bed rooms in the house

bathrooms: number of bathrooms in the house
sqft_living: square footage of living space in the home

sqft_lot: square footage of the lot

floors: number of floors or the levels in the house

waterfront: whether the house is located on a water front

grade: overall house grade in relation to design and construction

**Conclusion**

Houses that are situated at the waterfront and have luxurious features will have their prices increasing prices  substantial amount

A larger living space in the home tends to be associated with higher prices.Buyers typically consider more square footage as desirable and are willing to pay a premium for it.Thus a larger living space is an essential requirement


**Recommendation**

My first recommendation to sellers would be to make living space square footage their focal point. Correlation between square footage of living space and price of the home is fairly high compared to the other features. It is clear that larger homes mandate higher asking prices. Selling homes on the larger-end of the spectrum are guaranteed to generate the most revenue.

My second recommendation would be to pay particular attention to the locality of the home. House prices are clustered according to zipcode. Many factors and variables, tied into the zipcode, may influence the price either positively or negatively and we must be mindful of that.

My third recommendation would be to attend to the grade given by King County to the home. It is very influential in the price of the home. In general, as the grade increases, the price increases as well. This highlights the positive linear correlation between the two.

**Non Technical Presentation**

To access the slides,click on this link:https://docs.google.com/presentation/d/1Xg5wT1tNlmG-sYwg20J8V3GdkhHDaZl1/edit#slide=id.p1


