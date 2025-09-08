# 📊 Philippines Income & Expenditure Analysis

*Data Source: Kaggle*

## 💰 Average Income Levels Across Philippine Regions

This chart shows the average monthly income across different regions in the Philippines. It clearly highlights major income disparities. 
![Average Monthly Income](PNG/1.png)

- **Top Earners**: The National Capital Region (**NCR**), **CALABARZON**, and **Central Luzon** have the highest average incomes.
- **National Benchmark**: The dashed line shows the national average (PHP 19,481). Only a few regions are above this line.
- **Lowest Incomes**: **Bicol**, **SOCCSKSARGEN**, and **BARMM** have the lowest average incomes, showing significant regional inequality.



---

## 🛒 Family Income Distribution

These graphs show how household income is distributed across the country. 
![Expenditure Histogram](PNG/2.png)  
![Expenditure KDE](PNG/3.png)

- **Most Common Income**: The majority of families fall into the lower-to-middle income bracket, with a peak income between **PHP 20,000–30,000**.
- **Skewed Distribution**: The data is skewed to the right, meaning a small number of families have very high incomes, creating a long "tail" on the graph. This shows that most of the population earns less than the average, while a few outliers with high incomes pull the average up.

---

### 🧮 Full Correlation Matrix (All Variables)

This chart shows how different types of income and spending are connected. Each box compares two categories — like wage income and education spending — and shows whether they tend to increase or decrease together.

- 🔴 **Red** = Strong positive relationship (they rise together)
- 🔵 **Blue** = Strong negative relationship (one rises, the other falls)
- ⚪ **White** = Little or no relationship

The diagonal line of red boxes simply shows that each category is perfectly related to itself — that’s expected.

This matrix helps reveal patterns in household behavior, such as which income sources are linked to specific types of spending. These insights can support better budgeting, planning, and policy decisions.

![Correlation Matrix](PNG/4.png)




--




## 🔗 Income vs. Expenditure Correlations

This section explores how different types of spending are related to a family's total income.

### 📊 Top Income Correlations

This chart simplifies a larger correlation matrix to show which spending categories are most strongly linked to household income. 
![Top Income Correlations](PNG/5.png)

- 🗣️ **Communication** (0.71), 🏠 **Housing** (0.68), and 🛍️ **Miscellaneous Goods** (0.67) have the strongest positive correlation with income. This means as a family's income goes up, their spending on things like internet, phone bills, rent, and non-essential items increases significantly.
- Other notable categories like **food** (0.66) and **transportation** (0.64) also have a strong link. This suggests that rising income leads to increased spending on all types of goods and services, particularly on lifestyle and essential services.

---

## 🧭 Main Source of Income

This pie chart shows where Filipino households get their money. 
![Main Source of Income Distribution](PNG/6.png)

- **Wages & Salaries (49.1%)**: Almost half of the households rely on formal employment as their main source of income.
- **Other Sources (26.1%)**: A significant portion comes from sources like remittances from abroad, pensions, and investments.
- **Entrepreneurial Activities (24.8%)**: About a quarter of households depend on self-run businesses or informal trade. This shows a diverse economy where many people create their own income.

---

## 👨‍👩‍👧‍👦 Family Size

This chart shows how many members are in an average Filipino family. 
![Number of Family Members](PNG/7.png)

- **Typical Family Size**: The most common family size is between **2 to 6 members**.
- **Average Size**: The average Filipino family has about **4 members**.
- **Distribution**: Most families are small-to-medium sized, while larger families of seven or more members are less common. This context is important for understanding household income and spending, as family size directly impacts expenses.
