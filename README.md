# Regression-Based Business Insights \& Model Interpretation



### \## Project Overview



This project applies regression analysis to identify the business factors that most strongly influence monthly sales performance across retail stores. The objective is to evaluate different regression models, compare their predictive performance, and provide data-driven recommendations to support strategic business decision-making.



The analysis was performed using Microsoft Excel Regression Analysis and includes data preparation, dummy variable creation, simple regression models, multiple regression modelling, residual analysis, model comparison, and executive business recommendations.



### \# Business Problem Summary



Retail leadership wants to understand which operational and business factors have the greatest influence on monthly sales performance.



The analysis aims to answer questions such as:



\* Which variables most strongly influence monthly sales?

\* Does marketing investment significantly improve sales?

\* Does customer footfall have a greater impact than marketing?

\* Does inventory availability affect store performance?

\* Which regression model provides the best business insights?

\* How can leadership use regression outputs to improve decision-making?



The final objective is to identify the most suitable regression model for supporting sales forecasting and operational planning.



### \# Dataset Description



The dataset contains monthly operational information for retail stores.



#### \### Variables Included



| Variable                   | Description                         |

| -------------------------- | ----------------------------------- |

| store\_id                   | Unique store identifier             |

| month                      | Reporting month                     |

| region                     | Business region                     |

| store\_type                 | Store format                        |

| marketing\_spend            | Monthly marketing expenditure       |

| footfall                   | Monthly customer visits             |

| avg\_discount\_pct           | Average monthly discount percentage |

| staff\_count                | Number of employees                 |

| inventory\_availability\_pct | Product availability percentage     |

| competitor\_distance\_km     | Distance to nearest competitor      |

| holiday\_flag               | Holiday indicator (0/1)             |

| customer\_rating            | Average customer rating             |

| monthly\_sales              | Monthly sales (Dependent Variable)  |

| monthly\_profit             | Monthly profit                      |



### \# Dependent and Independent Variables



#### \## Dependent Variable



\* \*\*Monthly Sales\*\*



This is the target variable predicted by all regression models.



#### \## Independent Variables



\* Marketing Spend

\* Footfall

\* Inventory Availability Percentage

\* Average Discount Percentage

\* Staff Count

\* Customer Rating

\* Competitor Distance

\* Holiday Flag

\* Region

\* Store Type



### \# Regression Approach



Three regression models were developed and compared.

#### 

#### \## Model 1



Simple Linear Regression



Dependent Variable:



\* Monthly Sales



Independent Variable:



\* Marketing Spend



Purpose:



To evaluate whether marketing expenditure independently explains sales performance.



#### \## Model 2



Simple Linear Regression



Dependent Variable:



\* Monthly Sales



Independent Variable:



\* Footfall



Purpose:



To evaluate customer traffic as an individual predictor of monthly sales.

#### 

#### \## Model 3



Multiple Linear Regression



Dependent Variable:



\* Monthly Sales



Independent Variables:



\* Marketing Spend

\* Footfall

\* Inventory Availability

\* Region Dummy Variables

\* Store Type Dummy Variables



Purpose:



To evaluate multiple business drivers simultaneously and identify the strongest predictive model.



### \# Dummy Variable Approach



Categorical variables cannot be used directly within regression models.



Therefore, dummy variables were created for:



\* Region

\* Store Type



Reference categories were selected to avoid the Dummy Variable Trap.



#### \### Reference Categories



| Variable   | Reference Category |

| ---------- | ------------------ |

| Region     | East               |

| Store Type | Airport            |



The remaining categories were converted into binary dummy variables.



### \# Model Comparison Summary



| Model               | Variables Used                                                        |   R²  | Business Assessment       |

| ------------------- | --------------------------------------------------------------------- | :---: | ------------------------- |

| Simple Regression 1 | Marketing Spend                                                       | 0.167 | Weak standalone predictor |

| Simple Regression 2 | Footfall                                                              | 0.736 | Strong predictor          |

| Multiple Regression | Marketing Spend, Footfall, Inventory Availability and Dummy Variables | 0.827 | Best performing model     |



The Multiple Regression Model achieved the highest explanatory power and therefore provides the strongest support for business decision-making.



### \# Final Model Selected



#### \## Multiple Linear Regression



Reasons for selection:



\* Highest R² (0.827)

\* Highest Adjusted R² (0.822)

\* Strongest explanatory power

\* Incorporates multiple operational variables

\* Supports strategic business planning

\* Provides the most reliable sales predictions



### \# Business Recommendation



Based on the regression analysis, leadership should prioritize:



\* Increasing customer footfall.

\* Maintaining high inventory availability.

\* Optimizing marketing investment.

\* Monitoring regional sales performance.

\* Periodically retraining the regression model using updated business data.



These initiatives are expected to improve sales forecasting accuracy and overall retail performance.



### \# Assumptions and Limitations



This analysis assumes:



\* Linear relationships between predictors and monthly sales.

\* Independent observations.

\* Reliable source data.

\* Minimal multicollinearity after dummy variable creation.



Limitations include:



\* Regression identifies association rather than causation.

\* External factors such as weather, economic conditions, competitor promotions, and customer demographics were not included.

\* Model performance may improve with additional business variables and historical observations.



### \# Repository Structure



```text

part3\_regression\_insights/

├── data/

│   └── business\_regression\_data.xlsx

├── analysis/

│   ├── regression\_workbook.xlsx

│   ├── model\_comparison.md

│   └── residual\_analysis.md

├── outputs/

│   ├── regression\_summary.xlsx

│   ├── final\_recommendation.md

│   └── model\_equations.md

├── screenshots/

│   ├── simple\_regression\_output.png

│   ├── multiple\_regression\_output.png

│   ├── residuals\_preview.png

│   └── model\_comparison\_preview.png

└── README.md

```

### 

### \# Screenshots Included



The repository includes the following supporting screenshots:



\* Simple Regression Output

\* Multiple Regression Output

\* Residual Analysis Preview

\* Model Comparison Summary



These screenshots provide visual evidence of the regression models and support the analytical findings presented in this project.


### \# Conclusion



Regression analysis identified customer footfall, inventory availability, and marketing spend as the most influential business factors associated with monthly sales performance.



Among the evaluated models, the \*\*Multiple Linear Regression Model\*\* demonstrated the highest explanatory power and was selected as the preferred analytical model for supporting strategic retail decision-making.



This project demonstrates how statistical modelling can be combined with business interpretation to produce practical, evidence-based recommendations that improve forecasting, operational planning, and management decision-making.



