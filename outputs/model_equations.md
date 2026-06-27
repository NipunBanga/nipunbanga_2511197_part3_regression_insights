# \# Model Equations



## \## Executive Summary



Three regression models were developed to identify the business factors most strongly associated with monthly sales across retail stores. Two Simple Linear Regression models evaluated the impact of individual business drivers, while one Multiple Linear Regression model combined operational and location-based variables to provide a more comprehensive explanation of sales performance.



The Multiple Regression Model was selected as the final analytical model because it demonstrated the highest explanatory power (\*\*R² = 0.827\*\*) and provided the strongest support for business decision-making.

### 

### \# Simple Regression Model 1

#### 

#### \## Dependent Variable



\*\*Monthly Sales\*\*



#### \## Independent Variable



\*\*Marketing Spend\*\*



#### \## Regression Equation



\*\*Monthly Sales = β₀ + β₁(Marketing Spend)\*\*



#### \### Business Interpretation



\* Marketing spend has a positive association with monthly sales.

\* The coefficient represents the expected change in monthly sales for every additional unit of marketing investment.

\* The model explains approximately \*\*16.7%\*\* of sales variation (\*\*R² = 0.167\*\*), indicating that marketing alone cannot fully explain store performance.

### 

### \# Simple Regression Model 2



#### \## Dependent Variable



\*\*Monthly Sales\*\*



#### \## Independent Variable



\*\*Footfall\*\*

#### 

#### \## Regression Equation



\*\*Monthly Sales = β₀ + β₁(Footfall)\*\*

#### 

#### \### Business Interpretation



\* Customer footfall has a strong positive relationship with monthly sales.

\* Stores receiving more customer visits generally generate higher revenue.

\* This model explains approximately \*\*73.6%\*\* of sales variation (\*\*R² = 0.736\*\*), making footfall one of the strongest standalone predictors.

### 

### \# Multiple Linear Regression Model



#### \## Dependent Variable



\*\*Monthly Sales\*\*



#### \## Independent Variables



\* Marketing Spend

\* Footfall

\* Inventory Availability Percentage

\* Region Dummy Variables

\* Store Type Dummy Variables



#### \## General Regression Equation



\*\*Monthly Sales = β₀ + β₁(Marketing Spend) + β₂(Footfall) + β₃(Inventory Availability) + Region Dummies + Store Type Dummies\*\*



### \# Coefficient Interpretation



| Variable                   | Business Interpretation                                                                               |

| -------------------------- | ----------------------------------------------------------------------------------------------------- |

| Marketing Spend            | Higher marketing investment is associated with increased monthly sales.                               |

| Footfall                   | More customer visits generally result in higher sales revenue.                                        |

| Inventory Availability     | Better product availability supports improved sales performance by reducing lost sales opportunities. |

| Region Dummy Variables     | Measure the expected sales difference between each region and the reference region.                   |

| Store Type Dummy Variables | Measure the expected sales difference between each store format and the reference store type.         |

### 

### \# Dummy Variable Strategy



Categorical variables cannot be directly included in a regression model. Therefore, dummy variables were created to represent categorical information while avoiding perfect multicollinearity (Dummy Variable Trap).



#### \### Reference Categories



\*\*Region:\*\* East



\*\*Store Type:\*\* Airport



These reference categories were intentionally excluded from the regression equation. The coefficients of the remaining dummy variables therefore represent differences relative to these baseline categories.

### 

### \# Final Model Selection



The \*\*Multiple Linear Regression Model\*\* was selected because:



\* It achieved the highest explanatory power (\*\*R² = 0.827\*\*).

\* It incorporates multiple operational and business drivers simultaneously.

\* It provides stronger prediction accuracy than either Simple Regression model.

\* It supports strategic decision-making across marketing, operations, inventory management, and store performance.

### 

### \# Key Business Insights



The regression analysis indicates that:



\* Footfall is the strongest standalone predictor of monthly sales.

\* Marketing spend contributes positively but performs best when analysed together with operational variables.

\* Maintaining high inventory availability supports stronger sales outcomes.

\* Regional and store format differences influence sales performance and should be considered during planning.

### 

### \# Important Note



Regression analysis identifies \*\*statistical associations\*\* between business variables and monthly sales. It does \*\*not\*\* establish direct cause-and-effect relationships.



Leadership should therefore combine regression insights with operational expertise, business judgement, and continuous performance monitoring before implementing strategic decisions.



