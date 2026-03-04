# 📊 E-commerce Sales Data Analysis

## 🎯 Project Overview
Comprehensive analysis of e-commerce sales data (2023) to uncover business insights and identify optimization opportunities for revenue growth, customer retention, and operational efficiency.

**Author:** Junior Data Analyst Portfolio Project  
**Tools:** Python, Pandas, NumPy, Matplotlib, Seaborn, Jupyter Notebook

---

## 📁 Project Structure

```
├── data/
│   ├── raw/                    # Original dataset
│   └── clean/                  # Cleaned and processed data
├── notebooks/
│   ├── 01_data_Cleaning.ipynb                          # Data cleaning process
│   ├── 02_data_cleaning_feature_engineering.ipynb      # Feature creation
│   ├── 03_eda_overview.ipynb                           # Dataset overview
│   ├── 04_eda_order.ipynb                              # Order analysis
│   ├── 05_eda_delivered.ipynb                          # Delivery analysis
│   ├── 06_Revenue by AgeGroup.ipynb                    # Age group revenue
│   ├── 07_Top Product per AgeGroup.ipynb               # Product preferences
│   ├── 08_Purchase vs Cancel Rate per AgeGroup.ipynb   # Cancellation analysis
│   ├── 09_Monthly Revenue Trend.ipynb                  # Time series analysis
│   ├── 10_Correlation with Discount&&Shipping.ipynb    # Correlation analysis
│   └── 11_Business Recomendation.ipynb                 # Strategic recommendations
└── README.md
```

---

## 🔍 Key Findings

### 📈 Revenue Insights
- **Total Revenue Analysis:** Identified top 10% of orders contribute **82.43%** of total revenue
- **Peak Performance:** January 2023 showed highest order volume
- **Product Distribution:** Electronics category drives majority of high-value transactions

### 👥 Customer Segmentation
- Analyzed purchasing behavior across 6 age groups (<20, 20-29, 30-39, 40-49, 50-59, 60+)
- Identified key demographics with highest purchase rates vs. cancellation rates
- Regional distribution analysis (North, South, East, West)

### 📦 Operational Metrics
- **Delivery Status:** Analyzed shipping performance and return rates
- **Order Trends:** Monthly and daily patterns in 2023
- **Product Categories:** Electronics, Accessories, Wearables performance

---

## 💡 Business Recommendations

1. **Focus on High-Value Customers:** Top 10% generate 82%+ revenue - implement VIP retention program
2. **Optimize Peak Periods:** January shows highest orders - prepare inventory and staffing
3. **Age-Specific Marketing:** Tailor campaigns based on age group preferences
4. **Reduce Returns:** Analyze return patterns to improve product quality and descriptions

---

## 🚀 How to Run

### Prerequisites
```bash
Python 3.8+
Jupyter Notebook
```

### Installation
```bash
# Clone repository
git clone https://github.com/yourusername/Eccomerce-DS-analyst.git

# Navigate to project directory
cd Eccomerce-DS-analyst

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook
```

### Run Notebooks
Execute notebooks in sequential order (01 → 11) for complete analysis workflow.

---

## 📊 Dataset Information

**Source:** E-commerce Sales Dataset  
**Period:** 2023 (Primary) + 2024 (Partial)  
**Records:** 1,000+ transactions  
**Features:** 19 columns including Customer ID, Product, Revenue, Demographics, Shipping Status

### Key Columns:
- Customer ID, Gender, Age, Region
- Product Name, Category, Unit Price, Quantity
- Total Price, Revenue, Shipping Fee
- Order Date, Shipping Status, Delivered
- AgeGroup (engineered), OrderID (engineered)

---

## 🛠️ Technical Skills Demonstrated

✅ **Data Cleaning:** Handling missing values, data type conversion, outlier detection  
✅ **Feature Engineering:** Created AgeGroup, OrderID, extracted Date components  
✅ **Exploratory Data Analysis:** Statistical analysis, distribution analysis  
✅ **Data Visualization:** Matplotlib, trend analysis, comparative charts  
✅ **Business Analytics:** Revenue analysis, customer segmentation, trend forecasting  
✅ **Documentation:** Clear structure, markdown documentation, code comments  

---

## 📌 Next Steps

- [ ] Create interactive dashboard using Tableau/PowerBI
- [ ] Implement predictive modeling for revenue forecasting
- [ ] Add statistical hypothesis testing
- [ ] Expand to 2024 full-year analysis

---

## 📫 Contact

**LinkedIn:** [Your LinkedIn]  
**Email:** [Your Email]  
**Portfolio:** [Your Portfolio Website]

---

## 📄 License

This project is for educational and portfolio purposes.

---

**⭐ If you find this project helpful, please consider giving it a star!**
