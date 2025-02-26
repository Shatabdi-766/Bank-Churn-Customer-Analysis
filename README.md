# Bank Churn Customer Analysis and Customer Segmentation
## Overview :
## 📊 Exploring Bank Customer Behavior:

**Ever wondered why customers leave a bank or how financial institutions can better serve their clients? 
This project dives into two critical aspects of banking analytics :**

## 🔍 Bank Churn Analysis :
We investigate the key factors behind customer churn and develop predictive models to help banks retain their clients.

## 📊 Customer Segmentation : 
By analyzing customer demographics, account details, and behavioral patterns, we categorize customers into meaningful segments. This helps banks tailor their products and services to meet specific customer needs.

## 🚀 Project Workflow : 
1. **Data Collection & Cleaning** – Clean and prepare bank customer data for analysis, including handling missing values, encoding categorical variables, and scaling features.
2. **Exploratory Data Analysis (EDA)** – Identify trends and key insights.
3. **Modeling & Prediction** – Build predictive models(e.g., Logistic Regression, Random Forest) to predict analyze churn and evaluate 
     model performance using metrics like accuracy, precision, recall, and F1-score.
4. **Churn Analysis** – Analyze factors contributing to customer churn using exploratory data analysis (EDA) and statistical techniques.
5. **Customer Segmentation** – Apply clustering techniques(e.g., K-Means) to group customers.
6. **Insights & Recommendations** – Provide actionable strategies for customer retention and engagement.

# 🚀 Project Objectives  :
## 1️⃣ Bank Churn Analysis  
- 🔍 **Data Exploration:** Identify key patterns in customer churn by analyzing account activity, transaction history, and demographics.  
- 🛠 **Preprocessing & Feature Engineering:** Handle missing values, outliers, and inconsistencies to ensure high-quality data for modeling.  
- 🤖 **Predictive Modeling:** Build and evaluate machine learning models (Logistic Regression, Random Forest) for accurate churn prediction.  
- 📊 **Strategic Insights:** Provide actionable recommendations, such as personalized retention campaigns, improved customer support, and targeted offers.  

## 2️⃣ Customer Segmentation  
- 🏗 **Data Preparation:** Standardize, scale, and encode features for effective clustering.  
- 📌 **Clustering Techniques:** Apply K-Means to segment customers based on behavioral and demographic attributes.  
- 🔎 **Segment Analysis:** Identify distinct customer profiles to understand preferences and spending behavior.  
- 🎯 **Personalized Strategies:** Optimize marketing, services, and engagement tactics tailored to each segment to boost satisfaction and retention.  

## 🛠️ Technologies Used : 
- Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn)
- Google Colab
- Machine Learning Models (Logistic Regression, Random Forest,K-Means Clustering etc.)

## 📂 Datasets :

The dataset used in this project is available in the following formats:  

- 📄 **Excel (.xlsx):** [Download here](./Bank_Churn_Messy.xlsx)  
- 📊 **CSV (.csv):** [Download here](./Bank_Churn.csv)  

### 📊 Data Overview  
- **Customer Demographics:** Age, gender, location, and estimated salary.  
- **Account Information:** Account balance, tenure, number of products, Is Active Member, credit card usage, and churn status.

## Visualization Sample:

# Basic Sample:
![Exited Trend](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(11).png)

## 📉 **Exited (Churn Rate Trend)**  
**Description:**  
- A declining trend from **0.8 to 0.0**, labeled as **"Exited."**  

**Insight:**  
- Represents the **churn rate** or percentage of customers leaving over time.  

**🔍 Actionable Insights:**  
✅ Investigate key reasons for churn (e.g., poor service, lack of engagement).  
✅ Implement retention strategies like personalized offers or loyalty programs to reduce churn.  

![Geography Analysis](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(12).png)

## 🌍 **Geography-Based Analysis**  
**Description:**  
- A bar chart comparing values for **France, Spain, and Germany**, ranging from **0.00 to 0.35**.  
## Key Elements of the Chart

### Y-Axis (Vertical Axis)
- **Represents:** The metric value, ranging from `0.00` to `0.35`.
- **Possible Metrics:**
  - **Churn Rate:** Percentage of customers who stopped engaging.
  - **Conversion Rate:** Percentage of leads or visitors who made a purchase.
  - **Customer Satisfaction Score:** Average rating or score.

### X-Axis (Horizontal Axis)
- **Represents:** Geographic regions: **France**, **Spain**, and **Germany**.

### Bars
- Each bar corresponds to a region and shows the metric value for that region:
  - **France:** Highest value (~`0.35`).
  - **Spain:** Moderate value (~`0.20`).
  - **Germany:** Lowest value (~`0.10`).

## Insights

### France
- **Highest metric value** (e.g., highest churn rate or lowest conversion rate).
- **Potential Issues:** Customer retention, satisfaction, or engagement.
  
### Spain
- **Moderate metric value**, suggesting average performance compared to France and Germany.

### Germany
- **Lowest metric value** (e.g., lowest churn rate or highest conversion rate).
- **Indicates strong performance**, likely due to effective marketing, better customer service, or higher product satisfaction.

## Actionable Recommendations

### For France
- **Investigate** the reasons for the high metric value (e.g., poor customer service, lack of engagement).
- **Implement targeted strategies** to improve performance, such as:
  - Personalized marketing campaigns.
  - Enhanced customer support.
  - Localized product offerings.

### For Spain
- **Analyze** what’s working well and what needs improvement.
- **Replicate successful strategies** from Germany to boost performance.

### For Germany
- **Continue leveraging successful strategies** to maintain strong performance.
- **Share best practices** with other regions to improve overall results.

![Credit-Card](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(13).png)

## **Credit Card Usage Analysis** 

## 📊 Key Elements of the Chart

- **Y-Axis:** Represents customers who have a credit card (**"Yes"**).
- **X-Axis:** Represents customers who do not have a credit card (**"No"**).

## 🔍 Insight

The chart compares customer behavior or performance based on whether they have a credit card:

1. **Purchase Frequency:**
   - Customers with credit cards may show higher purchase frequency, suggesting they engage more often with the brand.
   
2. **Spending Patterns:**
   - Customers with credit cards may spend more per transaction, as they may have access to higher credit limits or prefer credit card payments over other methods.

3. **Churn Rate:**
   - Customers with credit cards might have a lower churn rate, possibly due to stronger brand loyalty or rewards tied to their card usage.

## 💡 Actionable Insight

If **customers with credit cards** show better performance metrics (e.g., higher spending, more frequent purchases, lower churn), the following actions can be considered:

1. **Promote Credit Card Usage:**
   - Offer incentives or rewards to encourage customers to sign up for or use their credit cards more frequently (e.g., discounts, cashback, loyalty points).

2. **Alternative Payment Options:**
   - For customers **without credit cards**, consider offering alternative payment methods (e.g., digital wallets, installments) to increase engagement and encourage purchases.

3. **Targeted Marketing Campaigns:**
   - Run campaigns targeting non-credit card users to highlight the benefits of having a credit card or explore ways to engage them in other ways.

![Active-Member](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(14).png)

## **Active-Member Analysis**
### Description
- A bar chart showing a metric (e.g., churn rate, engagement) by `IsActiveMember`:
  - **Yes (Active Members):** ~`0.25`
  - **No (Inactive Members):** ~`0.10`

### Insight
- **Active members** have a higher metric value (e.g., higher engagement or churn) compared to **inactive members**.

### Actionable Insight
- **For active members:**
  - Focus on **retention strategies** (e.g., loyalty programs).
- **For inactive members:**
  - Implement **re-engagement campaigns** (e.g., personalized offers).


![Gender](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(16).png)

## **Gender Analysis**
### Description
- A bar chart showing a metric (e.g., churn rate, satisfaction) by gender:
  - **Female:** ~`0.25`
  - **Male:** ~`0.20`

### Insight
- **Females** have a higher metric value (e.g., higher churn or lower satisfaction) compared to **males**.

### Actionable Insight
- **Investigate** why females show higher churn or lower satisfaction.
- **Tailor marketing or support strategies** to address gender-specific needs.

![Estimated-Salary](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(22).png)

## **Estimated-Salary Analysis**

## Key Insights

### Salary Range:
- The chart shows **EstimatedSalary** (ranging from $0–200,000) segmented by **Exited status** (0 = stayed, 1 = left).

### Trends:
- **Lower-income customers** (e.g., $25,000–$75,000) may have **higher churn** due to financial constraints.
- **Higher-income customers** (e.g., $100,000+) may show **better retention**, indicating satisfaction with premium services.

## Actionable Insights

### Lower-Income Customers:
- Offer **discounts**, **flexible payment plans**, or **loyalty rewards** to improve retention.

### Higher-Income Customers:
- Provide **premium offerings** or **exclusive perks** to maintain loyalty.

### General Strategy:
- Use **salary data** to **segment customers** and create **targeted retention campaigns** tailored to each income group.

![Num-of-Product-Analysis](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(18).png)

## **Num-of-Products Analysis**

## Description
- A chart showing **NumofProducts** (number of products owned), segmented by **Exited status** (0 = stayed, 1 = left).

## Key Insights

### Product Ownership:
- The chart shows **NumofProducts** (number of products owned) segmented by **Exited status** (0 = stayed, 1 = left).

### Trends:
- **Customers owning fewer products** may have **higher churn** due to lack of engagement.
- **Customers owning more products** may show **better retention**, indicating higher satisfaction or loyalty.

## Actionable Insights

### For Customers Owning Fewer Products:
- Offer **product bundles** or **discounts** to encourage additional purchases.
- Implement **re-engagement campaigns** to boost retention.

### For Customers Owning More Products:
- Provide **loyalty rewards** or **exclusive perks** to maintain their engagement.

## General Strategy:
- Use **product ownership data** to identify at-risk customers and tailor **retention strategies**.

![Credit-Score](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(20).png)

## **Credit-Score Analysis**

## Description
- A chart showing **CreditScore** ranges (400–800), segmented by **Exited status** (0 = stayed, 1 = left).

## CreditScore Insights

### CreditScore Ranges:
- The chart shows **CreditScore** (400–800) segmented by **Exited status** (0 = stayed, 1 = left).

### Trends:
- **Customers with lower credit scores** (e.g., 400–600) may have **higher churn** due to financial stress or limited access to services.
- **Customers with higher credit scores** (e.g., 700–800) may show **better retention**, indicating financial stability and satisfaction.

## Actionable Insights for CreditScore

### For Lower Credit Scores:
- Offer **flexible payment options** or **financial support** to reduce churn.
- Provide **educational resources** to improve financial literacy.

### For Higher Credit Scores:
- Focus on **premium services** or **exclusive perks** to maintain loyalty.

![Age](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(21).png)

## **Age Analysis**

## Description
- A chart showing **Age distribution**, segmented by **Exited status** (0 = stayed, 1 = left).

## Age Insights

### Age Distribution:
- The chart shows **Age** segmented by **Exited status** (0 = stayed, 1 = left).

### Trends:
- **Younger customers** (e.g., 20–30) may have **higher churn** due to changing preferences or financial instability.
- **Older customers** (e.g., 50+) may show **better retention**, indicating loyalty or satisfaction with services.

## Actionable Insights for Age

### For Younger Customers:
- Offer **discounts**, **student plans**, or **loyalty rewards** to boost retention.
- Use **targeted marketing** to align with their preferences.

### For Older Customers:
- Provide **personalized services** or **exclusive benefits** to maintain loyalty.

![Balance](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(17).png)

## **Balance Analysis**

## Description
The image appears to represent a long list of numerical values, likely related to **account balances** or **financial metrics**.

## Key Observations

### Data Range:
- Values range from **0 to 791**, with most values clustered between **0 and 500**.

### Patterns:
- Repeated sequences (e.g., **749–791**) suggest **cyclical trends** or **grouped categories**.
- Spikes (e.g., **796**, **797**) indicate potential **outliers** or **significant events**.

## Insights

### Low Balances (0–500):
- Likely represent **customers with minimal financial activity** or **low engagement**.
- May indicate **financial stress** or **limited access to services**.

### High Balances (500–791):
- Likely represent **customers with significant financial activity** or **high engagement**.
- May indicate **financial stability** or **satisfaction with services**.

### Outliers (e.g., 796, 797):
- Could represent **high-value transactions** or **anomalies** requiring further investigation.

## Actionable Insights

### For Low Balances:
- Offer **financial support** or **flexible payment options** to boost engagement.
- Implement **targeted campaigns** to re-engage inactive customers.

### For High Balances:
- Provide **premium services** or **exclusive perks** to maintain loyalty.

### For Outliers:
- Investigate the cause of spikes (e.g., **large transactions**, **data errors**).
- Replicate successful strategies if spikes represent **high-value activity**.

![Tenure](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(19).png)

## **Tenure Analysis**

## Description
The image is a bar chart showing the relationship between **Tenure** (how long customers have been with the business) and **Exited status** (whether they left or stayed).

## Key Elements

### Y-Axis:
- Represents a metric (e.g., **count**, **percentage**) ranging from **0 to 10**.

### X-Axis:
- Represents **Tenure**, segmented by **Exited status**:
  - **0**: Customers who stayed.
  - **1**: Customers who exited.

## Insights

### Customers Who Stayed (Exited = 0):
- Likely have **longer tenure**, indicating **loyalty** and **satisfaction**.
- Higher bars for this group suggest **strong retention** among long-term customers.

### Customers Who Exited (Exited = 1):
- Likely have **shorter tenure**, indicating **dissatisfaction** or **lack of engagement**.
- Lower bars for this group suggest **higher churn** among newer customers.

## Actionable Insights

### For Long-Tenure Customers:
- **Reward loyalty** with exclusive perks or personalized offers.
- Continue providing **high-quality service** to maintain satisfaction.

### For Short-Tenure Customers:
- Investigate reasons for **early churn** (e.g., poor onboarding, unmet expectations).
- Implement **re-engagement campaigns** or improved support to retain newer customers.

![Balance_vs_Salary](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(31).png)

## **Balance vs. Salary Analysis**

## Description
The image appears to be a scatter plot or chart comparing **Balance** (account balance) and **Salary**, segmented by **Exited status** (whether customers left or stayed).

## Key Elements

### Y-Axis:
- Likely represents **Balance**, ranging from **0 to 1.4**.

### X-Axis:
- Likely represents **Salary**, ranging from **0 to 1.2**.

### Exited Status:
- **0**: Customers who stayed.
- **1**: Customers who exited.

## Insights

### Customers Who Stayed (Exited = 0):
- Likely have **higher balances** and **higher salaries**, indicating **financial stability** and **satisfaction**.
- Clustered in the **upper-right quadrant** of the chart.

### Customers Who Exited (Exited = 1):
- Likely have **lower balances** and **lower salaries**, indicating **financial stress** or **dissatisfaction**.
- Clustered in the **lower-left quadrant** of the chart.

## Actionable Insights

### For High-Balance, High-Salary Customers:
- Focus on **premium services** or **exclusive perks** to maintain loyalty.

### For Low-Balance, Low-Salary Customers:
- Offer **financial support** or **flexible payment options** to reduce churn.
- Provide **targeted incentives** to boost engagement and satisfaction.


# Classification Sample :
![Classification-Heatmap](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(6).png)

## **Classification Heatmap Analysis**

## Description
The image appears to be a **heatmap** showing correlations between various customer attributes, likely used for **classification** or **predictive modeling**.

## Insights

### Strong Positive Correlations:
- **Attributes that increase together** (e.g., **Balance** and **EstimatedSalary**).
  - Indicates that **higher balances** may correlate with **higher salaries**.

### Strong Negative Correlations:
- **Attributes that move in opposite directions** (e.g., **Age** and **IsActiveMember_Yes**).
  - Suggests **older customers** may be **less active**.

### Weak or No Correlations:
- **Attributes with values close to 0.00** (e.g., **HasCrCard_Yes** and **Tenure**).
  - Indicates little to no relationship between these attributes.

## Actionable Insights

### For Positive Correlations:
- **Leverage relationships** (e.g., target high-salary customers with **premium services**).

### For Negative Correlations:
- **Address issues** (e.g., **re-engage older, less active customers**).

### For Weak Correlations:
- **Focus on other attributes** with stronger predictive power for classification.

![Income-vs-Products](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(7).png)

## **Income vs. Products Analysis**

## Insights

### Customers Who Stayed (Exited = 0):
- Likely have **higher income** and own **more products**, indicating **financial stability** and **engagement**.
- Clustered in the **upper-right quadrant** of the chart.

### Customers Who Exited (Exited = 1):
- Likely have **lower income** and own **fewer products**, indicating **financial stress** or **lack of engagement**.
- Clustered in the **lower-left quadrant** of the chart.

## Actionable Insights

### For High-Income, Multi-Product Customers:
- Focus on **premium services** or **exclusive perks** to maintain loyalty.

### For Low-Income, Few-Product Customers:
- Offer **discounts**, **bundled products**, or **financial support** to boost engagement.
- Implement **targeted campaigns** to encourage additional product adoption.

![ROC-Curve](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(8).png)

# **ROC Curve Analysis**

## Key Elements

- **X-Axis:** False Positive Rate (FPR) - Proportion of negative cases incorrectly classified as positive.
- **Y-Axis:** True Positive Rate (TPR) - Proportion of positive cases correctly classified as positive.

### Curves:
- **LR (Logistic Regression):**
  - AUC (Area Under Curve) = 0.77, indicating **good model performance**.
  
- **Random Guess:**
  - AUC = 0.50, representing a model with **no predictive power**.

## Insights

### Model Performance:
- The **Logistic Regression (LR)** model performs significantly better than random guessing, with an AUC of **0.77**.
- The curve is closer to the **top-left corner**, indicating a **good balance** between TPR and FPR.

### Trade-Off:
- The ROC curve shows the trade-off between **sensitivity (TPR)** and **specificity (1 - FPR)**.
- A **higher TPR** at **lower FPR** values is **desirable**.

![Precision-vs-Recall-Scores](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(9).png)

# Precision-Recall Curve Analysis

## Description
The image is a **Precision-Recall Curve**, which evaluates the trade-off between:
- **Precision:** Accuracy of positive predictions.
- **Recall:** Proportion of actual positives correctly identified.

## Key Insights

### Objective
- Find the threshold where **Precision** stays above `0.5` while maximizing **Recall**.
- At the intersection point:
  - **Recall** is ~`50%`, meaning the model captures **50% of churners**.

### Trade-Off
- **Higher Precision:**
  - Reduces false positives.
  - May lower **Recall**.
- **Higher Recall:**
  - Captures more churners.
  - May increase false positives.

## Actionable Insight
- Use the threshold where:
  - **Precision > 0.5**
  - **Recall ~50%**
- This balances **accurate predictions** with **effective churner identification**.
- **Model Fine-Tuning**: Depending on the business needs (e.g., minimizing false positives or maximizing churn detection),
  adjust this threshold to either prioritize Precision or Recall.

## Recommendations
- If want to reduce false positives and avoid reaching out to non-churners, prioritize **Precision**.
- If primary concern is identifying as many churners as possible (even at the cost of some false positives), prioritize **Recall**.

# **Random Forest Model Evaluation and Refinement** :

## Initial Performance and Overfitting Issue

After fitting the **Random Forest model** and performing **cross-validation**, the model's performance was evaluated using **test accuracy**, **AUC score**, and **feature importance**. Initially, the model exhibited **extreme overfitting**, as indicated by:

- **Train Accuracy:** 1.0 (perfect performance on training data)
- **Test Accuracy:** 0.866 (lower performance on unseen data)

This **significant disparity** between train and test accuracy highlighted the need for further model refinement.

## Hyperparameter Tuning and Model Refinement

To address the overfitting issue, **hyperparameter tuning** was performed, resulting in the following improvements:

- **Train Accuracy:** 0.87375 (lower, indicating better generalization)
- **Test Accuracy:** 0.8605 (slightly reduced, but more consistent with the train accuracy)

This optimization led to a **more balanced model**, reducing overfitting while maintaining robust predictive performance on unseen data.

## Key Takeway 
- **Random Forest** showed better performance in handling complex, non-linear relationships and, after hyperparameter tuning, achieved improved **generalization** without 
  significant overfitting.
- **Logistic Regression** is simpler and faster but may underperform if the dataset has complex relationships.
- For datasets with complex patterns, **Random Forest** is generally a better choice, while **Logistic Regression** is ideal for simpler or linearly separable data.

![Feature-Importance](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(10).png)

# **Feature-Importance-Analysis**

## Key Features and Importance

### Top Features:
- **Age**: Highest importance (~0.35).
- **NumOfProducts**: Second highest (~0.25).
- **Balance**: Third highest (~0.20).

### Moderate Features:
- **Income_v_Products**, **Balance_vs_Salary**, **Geography_Germany**: Moderate importance (~0.10–0.15).

### Lower Importance Features:
- **IsActiveMember_Yes**, **HasCrCard_Yes**, **EstimatedSalary**, **CreditScore**, **Tenure**, **Gender_Male**, **Geography_Spain**: Lower importance (<0.10).

## Insights

- **Age**, **NumOfProducts**, and **Balance** are the most influential factors in predicting churn.
- Features like **Geography_Germany** and **Income_v_Products** also contribute but to a lesser extent.
- Features such as **HasCrCard_Yes** and **Gender_Male** have minimal impact on churn.

## Actionable Insights

### Focus on Top Features:
- Prioritize strategies targeting **Age**, **NumOfProducts**, and **Balance** to reduce churn.

### Optimize Moderate Features:
- Leverage insights from **Income_v_Products** and **Geography_Germany** for targeted campaigns.

### Ignore or Deprioritize Low-Impact Features:
- Features like **HasCrCard_Yes** and **Gender_Male** may not significantly influence churn and can be deprioritized.


# Clustering Sample :

## **Customer Clustering Summary**  

## Cluster Averages  

| Cluster | Credit Score | Gender | Age  | Tenure | Balance  | Num of Products | Has Credit Card | Active Member | Estimated Salary | France | Germany | Spain | Products/Year | Exited |
|---------|-------------|--------|------|--------|----------|-----------------|-----------------|---------------|------------------|--------|---------|-------|---------------|--------|
| 0       | 651.20      | 0.46   | 38.92 | 6.03   | 78730.20 | 1.48            | 0.00            | 0.52          | 101285.72        | 0.50   | 0.24    | 0.26  | 0.29          | 0.21   |
| 1       | 649.38      | 0.43   | 39.04 | 5.98   | 123236.38 | 1.24            | 1.00            | 0.50          | 99856.40         | 0.42   | 0.38    | 0.20  | 0.25          | 0.23   |
| 2       | 650.24      | 0.46   | 38.52 | 6.17   | 11731.06 | 1.83            | 1.00            | 0.51          | 99487.18         | 0.62   | 0.07    | 0.31  | 0.34          | 0.16   |
| 3       | 651.88      | 0.47   | 39.19 | 1.18   | 75279.81 | 1.69            | 0.69            | 0.55          | 99837.12         | 0.49   | 0.27    | 0.24  | 1.32          | 0.21   |

## Explanation of Features  

- **Credit Score**: Average credit rating of customers in each cluster.  
- **Gender**: Proportion of male customers (0 = Female, 1 = Male).  
- **Age**: Average age of customers.  
- **Tenure**: Average number of years the customer has been with the bank.  
- **Balance**: Average account balance of customers.  
- **Num of Products**: Average number of products used by customers.  
- **Has Credit Card**: Proportion of customers in the cluster who have a credit card.  
- **Active Member**: Proportion of customers who are active members.  
- **Estimated Salary**: Average estimated salary of customers.  
- **France, Germany, Spain**: Proportion of customers from each country.  
- **Products/Year**: Average number of banking products used per year.  
- **Exited**: Proportion of customers who have left the bank.  

## Round-01 :
![Number-of-clusters vs Inertia (01)](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(1).png)

# Key Observations: Number of Clusters vs. Inertia Analysis

## Inertia Trend
- As the number of clusters (**K**) increases, **Inertia decreases**.
- This is expected because more clusters lead to tighter groupings.

## Elbow Point
- The curve starts to flatten after a certain point (e.g., around **K = 4–6**).
- This "elbow" indicates the **optimal number of clusters**, where adding more clusters provides diminishing returns.

## Insights

### Optimal Clusters
- The best choice for **K** is likely around **4–6**, where the trade-off between cluster tightness and simplicity is balanced.

### Overfitting Risk
- Choosing too many clusters (e.g., **K > 6**) may lead to **overfitting** and less meaningful groupings.

## Actionable Insight
- Use **K = 4–6** for clustering to achieve **meaningful and interpretable customer segments**.

![Customer-Segment](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(2).png)

# Customer Segmentation Analysis

## Customer Segments

### Segment 0
- **Behavior:** Many products purchased in a short time.
- **Insight:** Likely **high-engagement customers** who make frequent purchases.

### Segment 1
- **Behavior:** French customers with few products and high balance.
- **Insight:** May represent **financially stable customers** who are not highly engaged with products.

### Segment 2
- **Behavior:** German customers with a high balance.
- **Insight:** Likely **high-value customers** who maintain large account balances.

### Segment 3
- **Behavior:** French customers with more products and low balance.
- **Insight:** May represent customers who are **product-engaged but have limited financial resources**.

### Segment 4
- **Behavior:** Spanish customers.
- **Insight:** Likely represents a **geographic segment** with distinct purchasing or financial behavior.

## Actionable Insights

### Segment 0
- Reward frequent purchasers with **loyalty programs** or **exclusive offers**.

### Segment 1
- Encourage product adoption through **targeted campaigns**.

### Segment 2
- Focus on **premium services** or **exclusive perks** to retain high-value customers.

### Segment 3
- Offer **financial support** or **discounts** to boost engagement.

### Segment 4
- Tailor marketing strategies to align with **regional preferences**.

## Round-02 :
![Number of Clusters vs. Inertia Analysis](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(3).png)

**Number of Clusters vs. Inertia Analysis(Round-02)**

![Customer-Segment-Recommand](https://raw.githubusercontent.com/Shatabdi-766/Bank-Churn-Customer-Analysis/main/images/download%20(4).png)

# Customer Segmentation Analysis

## Customer Segments

### Segment 0
- **Behavior:** Customers who do not have a credit card but have relatively high tenure.
- **Insight:** These customers may have been with the business for a long time but are not utilizing credit facilities.
- **Action:** Encourage credit card adoption by highlighting benefits (e.g., rewards, discounts) to increase engagement and spending.

### Segment 1
- **Behavior:** Customers with a high balance, few products, and credit card ownership.
- **Insight:** These are likely financially stable customers who are not highly engaged with multiple products.
- **Action:** Promote additional products or services to increase product adoption and maximize their potential value.

### Segment 2
- **Behavior:** Customers with low balance, more products, and credit card ownership.
- **Insight:** These customers are product-engaged but may have limited financial resources.
- **Action:** Offer financial support (e.g., flexible payment plans) or discounts to retain them and boost their spending.

### Segment 3
- **Behavior:** Customers who purchase many products in a short period of time.
- **Insight:** These are high-engagement customers who make frequent purchases.
- **Action:** Reward their loyalty with exclusive perks, early access to new products, or personalized offers.

## Strategic Recommendations

### Segment-Specific Campaigns
- Tailor marketing and retention strategies to address the unique needs of each segment.

### Credit Card Promotion
- Target **Segment 0** with incentives to adopt credit cards, enhancing their engagement and spending potential.

### Product Upselling
- Focus on **Segment 1** to increase product adoption and maximize their financial potential.

### Financial Support
- Provide **Segment 2** with flexible payment options or discounts to retain them and boost their spending.

### Loyalty Programs
- Reward **Segment 3** for their high engagement with exclusive perks or personalized offers.





















