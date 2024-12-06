# **Business Analysis on PhonePe Data**

### Overview of the Project
This project involves analyzing transaction and user data from PhonePe, a leading digital payments platform in India. The analysis spans across various datasets to extract insights on transaction trends, user demographics, and market opportunities. Reports and dashboards are created to aid decision-making and highlight opportunities for growth and optimization.

### Introducing PhonePe
PhonePe, launched in December 2015 is a top-notch digital payments app powered by the Unified Payments Interface (UPI). It lets you send money instantly, pay bills, recharge mobiles, and even invest in financial products like insurance and mutual funds.

With a massive merchant network and user-friendly features, PhonePe is driving India toward a cashless economy by simplifying transactions for everyone from metro cities to small towns. Its mission is to make digital payments secure, transparent, and accessible, creating a financially inclusive India for businesses and individuals alike.

### Objective of the Project
To analyze PhonePe’s transaction and user data, uncover trends and patterns, and provide actionable insights to enhance the platform's performance, customer engagement, and regional growth.

### Business Case Problem
As a data/business analyst, the focus of this project is to address key challenges like:

* Identifying underperforming regions and untapped markets.
* Understanding transaction and user behavior to optimize offerings.
* Evaluating the adoption of insurance and financial products.

### Data source - https://github.com/PhonePe/pulse
### Data Description
The project uses data stored in JSON format, representing various attributes related to transactions, users, and locations.

* **Conversion of JSON to DataFrame** - 
    1. The data is extracted and processed using Python. 
    2. The following libraries were used - OS, Pandas, and JSON
* **Data Tables Created** - Data is structured into the following 9 CSV tables for analysis

    1. *Aggregate Transaction Table*
    2. *Aggregate Insurance Table*
    3. *Aggregate User Table*
    4. *Map User Table*
    5. *Map Transaction Table*
    6. *Top Transaction District*
    7. *Top Transaction Pincode*
    8. *Top User District*
    9. *Top User Pincode*
These tables contain State-wise, District-wise and Pincode-wise Total Transaction Count and Amount sent Yearly and Quartely. Type of transaction made? Who took Insurance? using PhonePe their total Amount & Count. How many Registered Users are there? What type of Mobile brand they are using? also Top 10 Districts and Pincodes from Top table. In Map tables Districts of each State information is also included.

### Exploratory Data analysis
EDA is performed on all the tables individually to find insights using python and for visualization Matplotlib, Seaborn is used. Discreptive analysis is done because data is in aggregate form. Steps followed are:
* Data Profiling
* Univarient Analysis
* Bivarient & Multivarient Analysis
    1. Correlation Analysis
    2. Cross table
    3. Pivot Table

### EDA Insights

* Users in Karnataka are actively using PhonePe to take Insurance policies.                     
* Usage of phone pe for merchant payments is more and Karnataka has the highest record in it.  
* Xiaomi is the most popular brand used by many PhonePe users across various states then next is Vivo, Samsung, Oppo and then Realme.         
* Pune district has highest number of registered users and app openers in Maharashtra.   
* Top district with highest sum of transaction amount is Hyderabad in Telangana.


### Visualized Insights
* Insurance-Specific Dashboard: Tracks insurance growth through digital payments.
* State-Level Analysis: Compares transaction and user metrics across states.
* District-Level Analysis: Identifies top-performing districts and patterns of adoption.
* Brand Performance Trends: Analyzes device usage and its impact on transactions.

### Conclusion
The Business Analysis on PhonePe Data project revealed key insights into transaction trends and user behavior, highlighting areas for growth and optimization.
* *Urban Dominance*: Cities like Bengaluru Urban, Hyderabad, and Pune lead in digital transactions.
* *Growth Opportunities*: States like Uttar Pradesh and Bihar present untapped potential for user engagement and financial product adoption.
* *Device Impact*: Xiaomi and Samsung dominate PhonePe’s mid-range user base, while Apple reflects growing premium adoption.
* *Insurance Adoption*: Karnataka leads in using PhonePe for insurance, signaling opportunities to expand such offerings nationwide.

