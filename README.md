# Customer Behaviour Data Analytics

A comprehensive analysis project focused on understanding customer shopping behavior, identifying patterns, and deriving actionable insights from transactional data.

## 📋 Project Overview

This project analyzes customer shopping behavior across various dimensions including demographics, purchase patterns, seasonal trends, and payment preferences. The analysis uncovers key insights that can drive strategic business decisions and improve customer engagement.

## 🎯 Business Objectives

- **Understand Customer Demographics**: Analyze age groups, gender distribution, and their impact on purchasing behavior
- **Identify Purchase Patterns**: Discover trends in product categories, purchase frequency, and spending habits
- **Seasonal Analysis**: Evaluate how seasons influence customer buying decisions
- **Payment & Subscription Trends**: Analyze preferred payment methods and subscription adoption rates
- **Customer Segmentation**: Group customers based on behavior for targeted marketing strategies
- **Review & Satisfaction Analysis**: Correlate purchase characteristics with customer satisfaction ratings

## 📊 Dataset

**File**: `customer_shopping_behavior.csv`

**Size**: 3,900 customer records

**Key Features** (18 attributes):
- **Customer Information**: Customer ID, Age, Gender
- **Purchase Details**: Item Purchased, Category, Purchase Amount (USD)
- **Product Attributes**: Size, Color
- **Contextual Data**: Location, Season
- **Customer Engagement**: Review Rating, Subscription Status
- **Transaction Details**: Shipping Type, Payment Method, Frequency of Purchases
- **Promotions**: Discount Applied, Promo Code Used
- **Purchase History**: Previous Purchases

## 📁 Repository Structure

```
Customer_Behaviour_Data_Analytics/
├── 1. Business Problem Document.pdf
│   └── Detailed problem statement and project requirements
├── 2. customer_shopping_behavior.csv
│   └── Raw dataset with 3,900 customer records
├── 3. Customer_Shopping_Behaviour_Analysis.ipynb
│   └── Jupyter notebook with Python analysis, visualizations, and insights
├── 4. Customer_Behaviour_SQL.sql
│   └── SQL queries for data extraction and aggregation
├── 5. Customer_Behaviour_Dashboard.pbix
│   └── Interactive Power BI dashboard for data visualization
├── 6. Customer Shopping Behavior Analysis.pdf
│   └── Detailed analysis report with findings and recommendations
├── 7. Customer-Shopping-Behavior-Analysis.pptx
│   └── Executive presentation of key findings
└── README.md
    └── Project documentation
```

## 🔍 Analysis Components

### 1. **Data Exploration & Cleaning**
   - Data quality assessment
   - Missing value analysis
   - Outlier detection
   - Data type validation

### 2. **Descriptive Analytics**
   - Customer demographic profiles
   - Purchase amount distributions
   - Category-wise sales analysis
   - Geographical insights

### 3. **Behavioral Patterns**
   - Purchase frequency analysis
   - Seasonal trends
   - Product preference by demographics
   - Subscription adoption patterns

### 4. **Customer Segmentation**
   - Age-based segmentation
   - Purchase value clustering
   - Frequency-based categorization
   - Engagement level analysis

### 5. **Correlation & Insights**
   - Review rating correlation with purchase factors
   - Discount impact on sales
   - Payment method preferences by segment
   - Promo code effectiveness

## 🛠️ Tools & Technologies

- **Data Analysis**: Python (Pandas, NumPy, Scikit-learn)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Database**: SQL
- **Business Intelligence**: Power BI
- **Notebook**: Jupyter Notebook

## 📈 Key Findings

The analysis reveals:
- **Customer Demographics**: Distribution across age groups and gender
- **Purchase Patterns**: Most popular categories, average purchase values, and seasonal variations
- **Customer Segments**: High-value customers, frequent buyers, seasonal shoppers
- **Satisfaction Metrics**: Review ratings across different customer segments and product categories
- **Operational Insights**: Popular shipping methods, payment preferences, and subscription trends

## 📊 Deliverables

1. **Analysis Notebook** (`3. Customer_Shopping_Behaviour_Analysis.ipynb`)
   - Complete Python analysis with code and visualizations
   - Reproducible and well-documented

2. **SQL Queries** (`4. Customer_Behaviour_SQL.sql`)
   - Database queries for key metrics
   - Aggregations and statistical calculations

3. **Interactive Dashboard** (`5. Customer_Behaviour_Dashboard.pbix`)
   - Power BI visualizations
   - Drill-down capabilities
   - Real-time filtering options

4. **Detailed Report** (`6. Customer Shopping Behavior Analysis.pdf`)
   - Comprehensive analysis findings
   - Data-driven recommendations
   - Executive summary

5. **Executive Presentation** (`7. Customer-Shopping-Behavior-Analysis.pptx`)
   - Key insights in presentation format
   - Visual storytelling
   - Actionable recommendations

## 🚀 Usage

### Exploring the Analysis:
1. Start with the **Business Problem Document** for context
2. Review the **Python Notebook** for detailed analysis code
3. Check the **PDF Report** for summary findings
4. Use the **Power BI Dashboard** for interactive exploration
5. Refer to the **Presentation** for stakeholder communication

### Running the Analysis:
```bash
# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn plotly jupyter

# Run the Jupyter notebook
jupyter notebook "3. Customer_Shopping_Behaviour_Analysis.ipynb"
```

### Database Setup (SQL):
```bash
# Load and execute SQL queries from:
# 4. Customer_Behaviour_SQL.sql
```

## 💡 Key Recommendations

Based on the analysis:
1. Develop targeted marketing strategies for high-value customer segments
2. Optimize seasonal inventory based on purchase patterns
3. Enhance subscription programs to increase customer lifetime value
4. Personalize offers based on customer purchase history and preferences
5. Improve customer satisfaction through category-specific initiatives

## 📚 Data Dictionary

| Column | Type | Description |
|--------|------|-------------|
| Customer ID | Integer | Unique customer identifier |
| Age | Integer | Customer age in years |
| Gender | String | Male/Female |
| Item Purchased | String | Name of purchased item |
| Category | String | Product category (Clothing, Footwear, Accessories, Outerwear) |
| Purchase Amount (USD) | Float | Transaction amount in US dollars |
| Location | String | US state of customer |
| Size | String | Product size (XS, S, M, L, XL) |
| Color | String | Product color |
| Season | String | Season of purchase (Winter, Spring, Summer, Fall) |
| Review Rating | Float | Customer satisfaction rating (0-5) |
| Subscription Status | String | Yes/No - subscription status |
| Shipping Type | String | Type of shipping selected |
| Discount Applied | String | Yes/No - whether discount was applied |
| Promo Code Used | String | Yes/No - whether promo code was used |
| Previous Purchases | Integer | Number of previous purchases |
| Payment Method | String | Method of payment used |
| Frequency of Purchases | String | Purchase frequency category |

## 📝 License

This project is provided as-is for educational and analytical purposes.

## 👤 Author

**Ash Legend** - [GitHub Profile](https://github.com/Ash-legend7)

## 📧 Contact & Collaboration

For questions, suggestions, or collaboration opportunities related to this project, feel free to reach out.

---

**Last Updated**: September 2026

**Status**: ✅ Analysis Complete
