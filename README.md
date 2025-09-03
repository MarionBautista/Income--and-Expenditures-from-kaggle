# 📊 Philippines Income & Expenditure Analysis  
*Data Source: Kaggle*

## 💰 Regional Income Disparity  
This visualization highlights stark income differences across Philippine regions. Economic activity is heavily concentrated in:

- **Top Earners**: NCR, CALABARZON, and Central Luzon lead in average monthly income.  
- **National Benchmark**: A dashed line marks the national average—only a few regions surpass it.  
- **Lowest Incomes**: Bicol, SOCCSKSARGEN, and BARMM fall well below the average, underscoring regional inequality.

![Average Monthly Income](PNG/1.png)

## 🛒 Family income Distribution  
Histogram and KDE plots reveal how Filipino families spend monthly:

- **Skewed Distribution**: Most families income in the lower-to-middle range; a few outliers spend significantly more.  
- **Central Tendency**: Peak income falls between PHP 20,000–30,000.  
- **High Income**: A long right tail (above PHP 50,000) reflects a small group with elevated expenditures.

![Expenditure Histogram](PNG/2.png)  
![Expenditure KDE](PNG/3.png)


## 🔗 Income vs. Expenditure Correlations  

### 🧮 Correlation Matrix Overview  
The heatmap below visualizes the correlation coefficients between various household income and expenditure categories. It helps identify which spending behaviors are most closely tied to income levels.

- 🔴 **Red Shades**: Strong positive correlations (closer to +1.0)  
- 🔵 **Blue Shades**: Strong negative correlations (closer to -1.0)  
- ⚪ **White Areas**: Weak or no correlation (around 0)

Each cell shows how two categories relate—for example, how **Total Household Income** correlates with **Transport Expenditure**, or how **Medical Care** relates to **Education Spending**. The diagonal line is always 1.0, showing perfect correlation with itself.

This matrix is useful for spotting patterns across all variables, not just income.

![Correlation Matrix](PNG/your_heatmap_image.png)

---

### 📊 Top Income Correlations  
To simplify interpretation, the horizontal bar chart below highlights the **strongest correlations with Total Household Income**:

- 🗣️ **Communication Expenditure** (0.71): Strongest link—higher income families spend more on connectivity.  
- 🏠 **Housing & Utilities** (0.68): Reflects increased capacity for rent, electricity, and water costs.  
- 🛍️ **Miscellaneous Goods & Services** (0.67): Captures flexible spending on non-essential items.

Other notable correlations:
- 🍽️ **Food Expenditure** (0.66)  
- 🚗 **Transport** (0.64)  
- 👗 **Clothing & Footwear** (0.61)

These patterns suggest that as income rises, spending increases across nearly all categories—especially in lifestyle, housing, and access-related areas.

![Top Income Correlations](PNG/your_bar_chart_image.png)
