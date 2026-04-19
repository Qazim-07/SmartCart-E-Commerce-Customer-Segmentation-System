## 📊 Dataset Documentation

### Overview
The dataset `smartcart_customers.csv` contains customer information used for segmentation analysis. Each row represents a unique customer with attributes that describe their shopping behavior and spending patterns.

### Columns Description
| Column Name        | Type     | Description |
|--------------------|----------|-------------|
| CustomerID         | Integer  | Unique identifier for each customer |
| Age                | Integer  | Age of the customer |
| Gender             | String   | Gender (Male/Female) |
| AnnualIncome       | Float    | Annual income in local currency |
| SpendingScore      | Integer  | Spending behavior score (higher = more spending) |
| PurchaseFrequency  | Integer  | Number of purchases in a given period |
| TotalSpend         | Float    | Total amount spent |

### Usage Notes
- Handle missing values before clustering.  
- Normalize numerical features for better clustering.  
- Use clustering algorithms (KMeans, DBSCAN, Hierarchical) to group customers.

### Example Insights
- Cluster 1 → High‑value customers (big spenders).  
- Cluster 2 → Budget shoppers (low spend, frequent).  
- Cluster 3 → Occasional buyers.  

