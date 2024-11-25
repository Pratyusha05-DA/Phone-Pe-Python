# Exploratory Data Analysis on PhonePe Dataset
### Objective
To analyze and extract meaningful insights from PhonePe’s transactional data, focusing on state-wise performance, transaction types, and payment modes to inform strategic decision-making.

### Dataset Description
* Source: PhonePe dataset.
* Scope: 9 tables covering aggregate transactions, user data, and insurance metrics across states, districts, and payment types.
* Key Attributes: Transaction amount, type, state, quarter, and payment method.
### EDA Methodology

#### Data Profiling
1. Checked dataset structure (`df.shape`).  
2. Assessed missing values (`df.isnull().sum`) and addressed them.  
3. Removed duplicate entries (`df.drop_duplicates`).  
4. Summarized data statistics (`df.describe`).  
5. Validated data types (`df.dtypes`).  
         

#### Univariate Analysis
Explored individual variables to understand distribution and central tendencies.              

#### Bivariate and Multivariate Analysis

* Correlation Analysis - Examined relationships between numerical variables.
* Cross Tables - Analyzed state-wise transaction counts and total amounts.
* Evaluated transaction type performance by count and amount.
* Pivot Tables - Analyzed state-wise distribution of payment modes.

#### Tools and Technologies Used
* Programming - Python.
* Libraries - Pandas, Matplotlib, Seaborn, Numpy.

#### Key Findings
1. High-performing states were identified with significant transaction volumes.
2. Insights into payment preferences across states highlighted potential growth areas.
3. Correlation analysis revealed key relationships between variables, aiding trend identification.

#### Conclusion
The EDA provided actionable insights into state-wise performance, transaction behaviors, and payment preferences. These insights can assist PhonePe in tailoring its strategies to enhance user engagement and expand market reach.




