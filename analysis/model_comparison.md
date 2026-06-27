# \# Model Comparison

### 

### \## Executive Summary



Three regression models were developed and evaluated to identify the factors most strongly associated with monthly sales across retail stores. Each model was assessed based on explanatory power (R²), statistical significance, business usefulness, and practical applicability. The objective was to identify the model that provides the most reliable support for business decision-making.



### \# Model 1 – Simple Linear Regression



\*\*Dependent Variable:\*\* Monthly Sales



\*\*Independent Variable:\*\* Marketing Spend



#### \### Model Results



\* \*\*R²:\*\* 0.167

\* Marketing spend shows a positive and statistically significant relationship with monthly sales.

\* The model explains approximately \*\*16.7%\*\* of the variation in monthly sales.

\* Although marketing investment contributes to sales performance, it should not be used as the sole predictor because several operational factors remain unaccounted for.



#### \### Business Interpretation



Marketing investment positively influences sales; however, relying only on marketing spend provides limited predictive capability. Additional operational variables are required for better business forecasting.

### 

### \# Model 2 – Simple Linear Regression



\*\*Dependent Variable:\*\* Monthly Sales



\*\*Independent Variable:\*\* Footfall



#### \### Model Results



\* \*\*R²:\*\* 0.736

\* Footfall demonstrates a strong positive relationship with monthly sales.

\* The model explains approximately \*\*73.6%\*\* of the variation in monthly sales.

\* This model performs substantially better than the marketing-only model.

#### 

#### \### Business Interpretation



Customer traffic is one of the strongest drivers of monthly sales. Improving store visits through customer acquisition campaigns and loyalty initiatives can significantly enhance sales performance.



### \# Model 3 – Multiple Linear Regression



\*\*Dependent Variable:\*\* Monthly Sales



\*\*Independent Variables\*\*



\* Marketing Spend

\* Footfall

\* Inventory Availability Percentage

\* Region Dummy Variables

\* Store Type Dummy Variables



#### \### Model Results



\* \*\*R²:\*\* 0.827

\* \*\*Adjusted R²:\*\* 0.822

\* The model explains approximately \*\*82.7%\*\* of the variation in monthly sales.

\* Multiple business drivers collectively improve prediction accuracy compared with individual predictor models.



#### \### Business Interpretation



The Multiple Regression Model provides the strongest analytical framework because it simultaneously considers marketing effectiveness, customer traffic, inventory performance, and store characteristics.

### 

### \# Comparative Evaluation



| Model               | Independent Variables                                                          |   R²  | Business Usefulness | Overall Assessment                            |

| ------------------- | ------------------------------------------------------------------------------ | :---: | ------------------- | --------------------------------------------- |

| Simple Regression 1 | Marketing Spend                                                                | 0.167 | Low                 | Suitable for evaluating marketing impact only |

| Simple Regression 2 | Footfall                                                                       | 0.736 | High                | Strong operational predictor                  |

| Multiple Regression | Marketing Spend, Footfall, Inventory Availability, Region \& Store Type Dummies | 0.827 | Very High           | Best overall analytical model                 |





### \# Final Model Selection



The \*\*Multiple Regression Model\*\* was selected as the final analytical model because it achieved the highest explanatory power (\*\*R² = 0.827\*\*), incorporated multiple statistically significant predictors, and provided the strongest support for strategic business decision-making.

### 

### \# Limitations



Although the selected model explains a large proportion of sales variation, several external factors remain outside the scope of this analysis, including:



\* Local economic conditions

\* Competitor activities

\* Seasonal events

\* Weather conditions

\* Customer demographics

\* Store management quality



Furthermore, regression analysis identifies \*\*statistical associations rather than causal relationships\*\*. Therefore, management decisions should combine model outputs with business expertise and operational judgement.

### 

### \# Business Recommendation



Leadership should adopt the \*\*Multiple Regression Model\*\* as the primary analytical model for sales forecasting and strategic planning. Business initiatives should prioritise:



\* Increasing customer footfall

\* Maintaining high inventory availability

\* Optimizing marketing investment

\* Monitoring regional performance

\* Periodically retraining the model using updated business data



This approach provides the strongest evidence-based foundation for improving monthly sales performance while recognising the practical limitations of statistical modelling.



