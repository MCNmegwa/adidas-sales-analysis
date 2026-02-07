# Adidas Sales Analysis

A comprehensive data analysis project examining Adidas sales performance across multiple dimensions including regions, products, and sales channels. This analysis combines descriptive statistics, advanced analytics, and predictive modeling to derive actionable business insights.

## 📊 Project Overview

This project provides an in-depth analysis of Adidas sales data, focusing on:
- Sales performance by region, product category, and sales method
- Operating margin and profitability analysis
- Statistical validation of performance differences
- Market segmentation using clustering algorithms
- Sales forecasting and scenario planning
- Strategic recommendations for revenue optimization

## 🎯 Key Features

### 1. **Descriptive Analytics**
- Sales trends and patterns across different dimensions
- Regional performance comparison
- Product category analysis
- Sales method effectiveness evaluation

### 2. **Advanced Analytics**
- **Statistical Validation**: ANOVA tests to confirm performance differences
- **Correlation Analysis**: Relationships between pricing, volume, and profitability
- **Market Segmentation**: K-Means clustering to identify distinct business segments
- **Sales Forecasting**: Holt-Winters exponential smoothing for demand prediction
- **Scenario Analysis**: Impact modeling for margin optimization strategies

### 3. **Key Insights**
- Identified top 10 segments for strategic investment
- Quantified potential profit gains from margin improvements
- Validated structural differences in regional and product performance
- Developed efficiency scoring methodology for portfolio prioritization

## 📈 Main Findings

### Top Performing Segments
1. **Women's Apparel - South (Outlet)**: $16.8M in sales, 53.6% operating margin
2. **Men's Street Footwear - Southeast (Online)**: $19.3M in sales, 48.3% operating margin
3. **Women's Apparel - Southeast (Online)**: $16.5M in sales, 50.1% operating margin

### Optimization Potential
- **Scenario Analysis**: Improving low-margin segments by 5 percentage points could generate an additional **$12.8M in profit**
- Current total profit: $332.1M
- Projected profit with optimization: $344.9M

### Strategic Recommendations
- Prioritize high-efficiency segments (Women's Apparel in South region)
- Focus on margin improvement rather than pure volume growth
- Leverage online channels for sustainable profitability
- Apply targeted strategies based on regional and product-specific characteristics

## 🛠️ Technologies Used

- **Python 3.x**
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib & Seaborn**: Data visualization
- **Scikit-learn**: Machine learning (K-Means clustering)
- **SciPy**: Statistical testing
- **Statsmodels**: Time series forecasting (Holt-Winters)
- **Jupyter Notebook**: Interactive development environment

## 📁 Project Structure

```
adidas-sales-analysis/
│
├── analysis.ipynb               # Main analysis notebook (HTML export)
├── README.md                    # Project documentation
├── QUICK_START.md               # Quick start guide
├── CONTRIBUTING.md              # Contribution guidelines
├── LICENSE                      # MIT License
├── requirements.txt             # Python dependencies
└── .gitignore                   # Git ignore file
```

## 🚀 Getting Started

### Prerequisites
- Python 3.7 or higher
- Jupyter Notebook or JupyterLab

### Installation

1. Clone the repository:
```bash
git clone https://github.com/MCNmegwa/adidas-sales-analysis.git
cd adidas-sales-analysis
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. View the analysis:
- Open `analysis.html` in your web browser
- Or see [QUICK_START.md](QUICK_START.md) for running the notebook

## 📊 Analysis Sections

### Section 1-4: Descriptive Analysis
- Data loading and preprocessing
- Exploratory data analysis
- Performance metrics calculation
- Visualization of key trends

### Section 5: Advanced Analytics Module
- Statistical validation (ANOVA)
- Correlation matrix analysis
- K-Means clustering for segmentation
- Time series forecasting
- Scenario and optimization analysis

## 💡 Business Impact

This analysis provides data-driven insights for:
- **Strategic Planning**: Identify high-value investment opportunities
- **Resource Allocation**: Optimize budget across products and regions
- **Pricing Strategy**: Balance volume growth with margin preservation
- **Inventory Management**: Forecast demand for seasonal planning
- **Risk Management**: Quantify uncertainty in projections

## 📝 Methodology

### Statistical Rigor
- One-way ANOVA for performance difference validation
- Non-parametric tests for robustness checks
- Confidence intervals for forecast uncertainty
- Efficiency scoring combining multiple metrics

### Clustering Approach
- Features: Sales scale, operating margin, units sold, profit efficiency
- Algorithm: K-Means with optimal cluster determination
- Validation: Silhouette analysis and business interpretability

### Forecasting Model
- Method: Holt-Winters exponential smoothing
- Components: Trend and seasonality
- Validation: Historical backtesting
- Output: Point forecasts with confidence bands

## 🔍 Key Metrics

- **Total Sales**: Revenue generated
- **Operating Profit**: Profit after operating expenses
- **Operating Margin**: Profitability ratio
- **Efficiency Score**: Composite metric combining sales and margins
- **Units Sold**: Volume metrics
- **Price Per Unit**: Pricing analysis

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👤 Author

Miracle Nmegwa
- GitHub: [@MCNmegwa](https://github.com/MCNmegwa)
- LinkedIn: [Miracle Nmegwa](https://linkedin.com/in/miracle-nmegwa)

## 🙏 Acknowledgments

- Data source: [https://www.kaggle.com/datasets/heemalichaudhari/adidas-sales-dataset]
- Inspired by real-world retail analytics challenges
- Built with open-source tools and libraries

## 📧 Contact

For questions or feedback, please open an issue or contact [nmegwamiracle@gmail.com]

---

