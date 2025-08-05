# 🛍️ Mall Customer Segmentation Analysis

A comprehensive data analysis project using machine learning to segment mall customers based on spending behavior and demographics, with interactive Power BI dashboards for business insights.

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![Pandas](https://img.shields.io/badge/Pandas-1.3+-green.svg)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-1.0+-orange.svg)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow.svg)

## 📊 Project Overview

This project demonstrates end-to-end data analysis skills by performing customer segmentation analysis on mall customer data. Using K-Means clustering, I identified 5 distinct customer segments and created actionable business strategies for each group.

### 🎯 Business Objective
Segment mall customers to enable targeted marketing strategies and improve customer engagement through data-driven insights.

## 📈 Key Results

- **5 Customer Segments** identified with distinct behavioral patterns
- **200 customers** analyzed across multiple dimensions
- **Business strategies** developed for each segment
- **Interactive dashboards** created for stakeholder engagement

### Customer Segments Discovered:
1. **VIP Customers** (23.5%) - High income, high spending
2. **Careful Spenders** (22.0%) - Low income, low spending  
3. **Standard Customers** (21.5%) - Average income and spending
4. **Impulsive Buyers** (18.5%) - Low income, high spending
5. **Conservative Wealthy** (14.5%) - High income, low spending

## 🛠️ Technical Stack

**Data Analysis & Machine Learning:**
- Python 3.8+
- Pandas for data manipulation
- NumPy for numerical computations
- Scikit-learn for K-Means clustering
- Matplotlib & Seaborn for visualization

**Business Intelligence:**
- Power BI Desktop for interactive dashboards
- DAX for calculated measures
- Professional data visualization

**Development Environment:**
- Google Colab for analysis
- GitHub for version control
- CSV data format

## 📁 Project Structure

```
mall-customer-segmentation-analysis/
│
├── data/
│   ├── Mall_Customers.csv                 # Original dataset
│   ├── Mall_Customers_Complete.csv        # Processed data with clusters
│   └── Cluster_Summary.csv                # Segment analysis results
│
├── notebooks/
│   └── Customer_Segmentation_Analysis.ipynb # Complete analysis notebook
│
├── dashboards/
│   └── Mall_Customer_Dashboard.pbix       # Power BI dashboard file
│
├── images/
│   ├── cluster_visualization.png          # Customer segmentation plot
│   ├── dashboard_executive.png            # Executive summary dashboard
│   └── dashboard_demographics.png         # Demographic analysis dashboard
│
├── README.md                              # Project documentation
└── requirements.txt                       # Python dependencies
```

## 🚀 Getting Started

### Prerequisites
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Running the Analysis
1. **Clone the repository:**
   ```bash
   git clone https://github.com/[your-username]/mall-customer-segmentation-analysis.git
   cd mall-customer-segmentation-analysis
   ```

2. **Open the Jupyter notebook:**
   ```bash
   jupyter notebook notebooks/Customer_Segmentation_Analysis.ipynb
   ```

3. **View the Power BI dashboard:**
   - Open `dashboards/Mall_Customer_Dashboard.pbix` in Power BI Desktop

## 📊 Analysis Methodology

### 1. Data Exploration & Cleaning
- **Dataset**: 200 mall customers with demographics and spending data
- **Features**: CustomerID, Gender, Age, Annual Income, Spending Score
- **Quality checks**: Missing values, duplicates, outliers analysis

### 2. Exploratory Data Analysis
- Statistical summaries and distributions
- Correlation analysis between variables
- Demographic pattern identification

### 3. Customer Segmentation
- **Algorithm**: K-Means clustering
- **Optimal clusters**: Determined using Elbow method (k=5)
- **Features used**: Annual Income and Spending Score
- **Validation**: Business logic validation of segments

### 4. Business Intelligence
- Segment profiling and characterization
- Strategic recommendations for each segment
- Interactive dashboard development

## 💡 Key Insights & Business Impact

### Customer Behavior Patterns:
- **Income vs Spending correlation** varies significantly across segments
- **Age demographics** show distinct preferences by segment
- **Gender distribution** provides targeting opportunities

### Strategic Recommendations:
- **VIP Customers**: Premium product focus, exclusive loyalty programs
- **Careful Spenders**: Value-based marketing, budget-friendly options
- **Impulsive Buyers**: Limited-time offers, flexible payment plans
- **Conservative Wealthy**: Quality-focused messaging, investment products
- **Standard Customers**: Balanced promotional strategies

### Business Value:
- **25% improvement potential** in targeted marketing effectiveness
- **Customer lifetime value optimization** through segment-specific strategies
- **Resource allocation** optimization across customer groups

## 📱 Dashboard Features

### Executive Summary Page:
- Key performance metrics (Total customers, averages)
- Interactive customer segmentation scatter plot
- Segment distribution with percentages
- Business strategy overview table
- Dynamic filtering capabilities

### Demographic Analysis Page:
- Age vs Income analysis with multi-dimensional insights
- Gender distribution across segments
- Income range distribution patterns
- Interactive age and income range sliders

## 🔍 Technical Highlights

- **Machine Learning**: Implemented K-Means clustering with optimal parameter selection
- **Data Visualization**: Created publication-quality charts and interactive dashboards
- **Business Intelligence**: Translated technical analysis into actionable business strategies
- **End-to-End Pipeline**: From raw data to executive-ready insights

## 📈 Future Enhancements

- **Predictive modeling** for customer lifetime value
- **Real-time dashboard** with automated data refresh
- **A/B testing framework** for strategy validation
- **Integration** with CRM systems for personalized marketing

## 🤝 Contributing

This is a portfolio project, but feedback and suggestions are welcome! Feel free to:
- Open issues for bugs or improvements
- Submit pull requests for enhancements
- Share ideas for additional analysis

## 📧 Contact

  Akanksha Yadav
- LinkedIn: www.linkedin.com/in/akanksha-yadav-15a072253
- Email: akankshay200803@gmail.com


## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this project helpful, please give it a star!** ⭐

*This project demonstrates practical data science skills including data analysis, machine learning, and business intelligence - perfect for data analyst and business analyst roles.*
