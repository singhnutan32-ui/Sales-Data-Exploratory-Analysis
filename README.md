#Sales Data Analysis

## Overview
This project analyzes the Diwali sales data to uncover insights into customer purchasing patterns. The dataset contains 11,251 entries and 15 features, focusing on customer demographics and order details.

## Data Preprocessing
The data was cleaned by dropping missing values and converting the 'Amount' column to integer data type for accurate calculations.

## Exploratory Data Analysis (EDA)
The EDA focused on various aspects such as gender, age group, state, marital status, occupation, and product category to understand the sales trends.

### Gender Analysis
- A bar chart was plotted to count the number of purchases made by each gender.
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/1fe07f19-4637-4321-8e03-3ad6f2ef3587)
  From above graphs we can see that most of the buyers are females and even the purchasing power of females are greater than men
- Another bar chart displayed the total amount spent by each gender by their age group, indicating higher spending by females.
  ![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/e47baf14-85ca-49c8-b1cb-48e7fe9ec4ae)


### Age Analysis
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/a2fd99a1-5d1c-445c-967c-523f63e1ec05)

- The age group distribution was visualized, highlighting that most buyers belong to the 26-35 years age group.
- Total amount spent by each age group was also analyzed, with the same age group (26-35 years) spending the most.

### State Analysis
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/76a44f62-9f6f-407c-91d1-5bc2b6ede622)

- The top 10 states by the number of orders were visualized, showing Uttar Pradesh, Maharashtra, and Karnataka leading in orders and sales.

### Marital Status Analysis
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/40c0d0c7-c13c-439e-a40c-d68502a37359)

- The marital status of buyers was plotted, revealing that married women have a higher purchasing power as shown below
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/d9ce2411-c8a0-4912-b7ba-ed3a58b24b92)

### Occupation Analysis
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/6f77ba28-1b27-4757-81e8-6157fda607fb)
- The occupation distribution showed purchasing power of different sector workers

![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/d2e39c39-db5b-4831-b975-3b939ffb3398)

- The occupation distribution showed that most buyers work in IT, Healthcare, and Aviation sectors.

### Product Category Analysis
![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/b0c11c7c-5c6c-4dee-a3af-9aeac05f9107)
- Analysis was done to check number of product sold from each category.

![image](https://github.com/shobhitkumar0/Sales-Data-Exploratory-Analysis/assets/55182906/c85a14de-aaff-44d5-afb2-8aa0ce1958f9)

- The most sold product categories were Food, Clothing, and Electronics.

## Conclusion
The analysis concluded that married women in the age group of 26-35 years from UP, Maharashtra, and Karnataka, working in IT, Healthcare, and Aviation sectors, are more likely to purchase products from Food, Clothing, and Electronics categories.

## How to Run the Analysis
To run this analysis, ensure you have `pandas`, `matplotlib`, and `seaborn` installed in your Python environment. Use the following commands to install these libraries if you haven't already:

```bash
pip install pandas matplotlib seaborn

Then execute the analysis.py file.
