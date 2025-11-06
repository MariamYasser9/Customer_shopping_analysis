# Customer-Shopping-Trends-Analysis 🛍️📊

## 📘 Overview
This project explores a **Customer Shopping Trends Dataset** to uncover demographic influences, purchasing patterns, category performance, and seasonal sales trends.

The analysis was conducted using **Python**, **Pandas**, **Matplotlib**, and **Seaborn**, focusing on key business insights that can help understand customer behavior better.

---

## 🧩 Dataset Information
**Source:** [Kaggle - Customer Shopping Trends Dataset](https://www.kaggle.com/datasets/iamsouravbanerjee/customer-shopping-trends-dataset)  
**Rows:** 3900  
**Columns:** 18  

**Main Features:**
- Customer Info: `Customer ID`, `Age`, `Gender`, `Location`
- Transaction Info: `Item Purchased`, `Category`, `Purchase Amount (USD)`, `Payment Method`
- Context: `Season`, `Subscription Status`, `Review Rating`

---

## 🧹 Data Cleaning & Preparation
- Downloaded and loaded the dataset using the `kagglehub` library.
- Inspected data integrity, data types, and checked for missing values (none found).
- Checked for and confirmed no duplicate entries.
- The dataset was found to be exceptionally clean and well-structured, requiring minimal preparation.

---

## 📊 Visualizations & Insights
Below are some of the key visualizations and findings from the analysis:

| Visualization | Description / Insight |
|---------------|------------------------|
| 🚻 **Customer Gender Distribution** | The customer base is predominantly male, representing 68% of all entries. |
| 🛍️ **Top 10 Product Categories** | **Clothing** is the most popular category (1737 sales), followed by **Accessories** (1240) and **Footwear** (599). |
| 💵 **Purchase Amount Distribution** | The average purchase is **$59.76**. Most purchases fall between $39 and $81 (IQR). |
| ♂️ vs ♀️ **Spending by Gender** | Despite the 68% male customer base, average spending is nearly identical (Male: $59.54, Female: $60.25). |
| ☀️ **Sales by Season** | **Spring** has the highest *volume* of sales (999), but average spend is slightly higher in **Fall** ($61.56). |
| 💳 **Spending by Subscription** | Subscription status has no significant impact on average purchase value. (Sub: $59.49, Non-Sub: $59.87). |

---

## 🪄 Tools & Libraries
- **Python**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **Kagglehub**
- **Jupyter Notebook**

---

## 📈 Key Insights
- The **top-performing categories** are 'Clothing', 'Accessories', and 'Footwear', indicating clear areas for inventory focus.
- **Gender does not predict spending value.** While the customer base is 68% male, marketing and promotions based on price should be equally effective for both genders.
- **Seasonal sales are nuanced.** Spring sees the most transactions, but marketing for higher-ticket items could be more effective in Fall and Winter when average spending ticks up.
- The **subscription program's value is not in single-transaction spending.** Its benefits likely lie in customer loyalty, purchase frequency, or other perks, as subscribers and non-subscribers spend the same amount per visit.

---

## 🧠 Future Improvements
- Develop a **predictive model** to forecast sales based on season and category.
- Build an **interactive dashboard** using Plotly or Power BI to filter insights by location.
- Analyze **customer behavior by `Location`** to identify regional preferences.
- Perform a **payment method analysis** to see if it correlates with purchase value.

---

## 🏁 Conclusion
This analysis provides a data-driven view of customer shopping behavior, helping understand **demographic trends**, **category performance**, and **seasonal impact**.  
It can assist retail platforms in optimizing their marketing strategies, managing inventory, and re-evaluating the perceived value of their subscription models.

---

## 🙌 Acknowledgments
This project is part of my data analysis learning journey. Grateful for the guidance from mentors, instructors, and the data community.

---

### 📂 Project Structure
├── Customer_Shopping_Analysis.ipynb # Jupyter notebook with full analysis
├── shopping_trends.csv # Dataset (downloaded via kagglehub)
├── README.md # Project documentation

---

### 📬 Connect with Me
If you’d like to discuss this project or collaborate:

- 💼 [LinkedIn]()
