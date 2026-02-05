# Quick Start Guide

## Viewing the Analysis

The easiest way to view the analysis is to open the HTML file:

1. Download or clone this repository
2. Open `analysis.html` in your web browser
3. No installation required!

## Running the Notebook (Optional)

If you want to modify or re-run the analysis:

### Step 1: Set Up Environment

```bash
# Clone the repository
git clone https://github.com/yourusername/adidas-sales-analysis.git
cd adidas-sales-analysis

# Create a virtual environment (recommended)
python -m venv venv

# Activate virtual environment
# On Windows:
venv\Scripts\activate
# On macOS/Linux:
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt
```

### Step 2: Get the Data

Place your Adidas sales dataset in the project directory. The expected format is a CSV file with the following columns:
- Retailer
- Retailer ID
- Invoice Date
- Region
- State
- City
- Product
- Price per Unit
- Units Sold
- Total Sales
- Operating Profit
- Operating Margin
- Sales Method

### Step 3: Run the Analysis

```bash
# Start Jupyter Notebook
jupyter notebook

# Open the notebook file and run all cells
```

## Project Structure

```
adidas-sales-analysis/
│
├── analysis.html              # HTML export of the analysis (ready to view)
├── README.md                  # Main documentation
├── QUICK_START.md            # This file
├── CONTRIBUTING.md           # Contribution guidelines
├── LICENSE                   # MIT License
├── requirements.txt          # Python dependencies
└── .gitignore               # Git ignore rules
```

## Key Sections in the Analysis

1. **Data Loading & Cleaning**: Initial data preparation
2. **Exploratory Analysis**: Understanding the dataset
3. **Performance Metrics**: Sales and profitability analysis
4. **Regional Analysis**: Geographic performance breakdown
5. **Advanced Analytics**: Statistical validation, forecasting, and optimization

## Need Help?

- Check the main [README.md](README.md) for detailed documentation
- Open an issue on GitHub
- Review the [CONTRIBUTING.md](CONTRIBUTING.md) for contribution guidelines

---

Happy analyzing! 📊
