# Walmart Customer Purchase Behavior Analysis

## Overview
This project analyzes customer purchase behavior during Black Friday at Walmart. The goal is to understand how factors like gender, marital status, and age influence spending habits. The analysis provides actionable insights to help Walmart improve customer experience and sales.

## Problem Statement
Walmart aims to analyze customer purchase behavior, specifically the purchase amount, against factors like gender, marital status, and age. The analysis will help Walmart make data-driven decisions to enhance customer experience and boost sales.

## Dataset Overview
The dataset contains transactional data of customers who purchased products during Black Friday. The features include:
- **User_ID**: Unique identifier for each user.
- **Product_ID**: Unique identifier for each product.
- **Gender**: Gender of the user (Male/Female).
- **Age**: Age group of the user (binned).
- **Occupation**: Occupation of the user (masked).
- **City_Category**: Category of the city (A, B, C).
- **Stay_In_Current_City_Years**: Number of years the user has stayed in the current city.
- **Marital_Status**: Marital status of the user (0 = Unmarried, 1 = Married).
- **Product_Category**: Category of the product purchased (masked).
- **Purchase**: Purchase amount in dollars.

## Key Findings
### Gender-Based Insights
- **Insight**: Male customers spend more on average than female customers.
- **Recommendation**:
  - Target male customers with high-value products or exclusive deals to maximize revenue.
  - Introduce loyalty programs or discounts for female customers to increase their average spending.

### Marital Status-Based Insights
- **Insight**: Married customers spend slightly more than unmarried customers.
- **Recommendation**:
  - Create family-oriented promotions or bundle deals to attract married customers.
  - Focus on trendy or individual-focused products for unmarried customers.

### Age-Based Insights
- **Insight**: Older customers (51-55 and 36-45) spend more than younger customers (0-17 and 18-25).
- **Recommendation**:
  - Target older customers with premium products or services.
  - Focus on affordable and trendy products for younger customers to increase their spending.

## Confidence Interval Analysis
Using the Central Limit Theorem (CLT), we calculated the confidence intervals for the average purchase amounts for male and female customers:
- **Female Customers**:
  - Sample Mean: $8,731
  - 95% Confidence Interval: [8,698, 8,764]
- **Male Customers**:
  - Sample Mean: $9,434
  - 95% Confidence Interval: [9,422, 9,453]

The confidence intervals for male and female customers do not overlap, indicating that the difference in average spending between genders is statistically significant.

## Repository Structure
- **Walmart_CentralLimitTheorm.ipynb**: Jupyter Notebook containing the detailed analysis and code.
- **Walmart_CentralLimitTheorm.pdf**: PDF version of the analysis.
- **walmart_data.csv**: Dataset used for the analysis.

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/walmart-customer-analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd walmart-customer-analysis
   ```
3. Open the Jupyter Notebook to view the analysis:
   ```bash
   jupyter notebook Walmart_CentralLimitTheorm.ipynb
   ```

## Dependencies
- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scipy

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments
- Dataset provided by [source].
- Special thanks to [contributors] for their valuable input.

---

For any questions or feedback, please open an issue or contact [your-email@example.com].
