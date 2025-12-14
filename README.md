# Connor T - Finance & Data Portfolio

> A curated portfolio of investment research, portfolio analytics, and data-driven projects featuring Python, Power BI, and finance-focused modeling with reproducible workflows, clear documentation, and publish-ready outputs.

## 👋 About Me

I'm a finance and data professional passionate about leveraging data science, analytics, and automation to drive investment insights and operational efficiency. This portfolio showcases my ability to build end-to-end data pipelines, create interactive dashboards, perform rigorous quantitative analysis, and deploy automated solutions.

## 🛠️ Technical Skills

**Programming & Analysis:**
- Python (pandas, numpy, scipy, scikit-learn, statsmodels)
- SQL (PostgreSQL, SQLite)
- R (for statistical modeling)
- VBA (Excel automation)

**Data Visualization & BI:**
- Power BI (DAX, Power Query)
- Tableau
- Matplotlib, Seaborn, Plotly
- Excel (advanced functions, pivot tables)

**Finance & Quantitative Analysis:**
- Portfolio optimization and risk management
- Financial modeling and valuation
- Time series analysis and forecasting
- Statistical analysis and hypothesis testing

**Tools & Technologies:**
- Git/GitHub (version control)
- Jupyter Notebooks
- APIs (REST, financial data providers)
- ETL pipelines
- CI/CD (GitHub Actions)

## 📁 Featured Projects

### 1. [News Email Bot](/projects/news-email-bot/)
An automated Python bot that scrapes financial news, filters by relevance, and sends daily digest emails. Features intelligent content summarization and scheduled execution.

**Tech Stack:** Python, BeautifulSoup, Selenium, SMTP, Schedule  
**Key Features:** Web scraping, NLP text processing, email automation, task scheduling

### 2. [Portfolio Analytics](/projects/portfolio-analytics/)
Comprehensive portfolio analytics toolkit for calculating risk metrics, optimizing asset allocation, and backtesting investment strategies. Includes interactive Jupyter notebooks with detailed analysis.

**Tech Stack:** Python, pandas, numpy, scipy, matplotlib, yfinance  
**Key Features:** Sharpe ratio, VaR, CVaR, efficient frontier, Monte Carlo simulation

### 3. [Data Cleaning & EDA](/projects/data-cleaning-eda/)
Real-world examples of data cleaning, exploratory data analysis, and feature engineering on financial datasets. Demonstrates best practices for handling missing data, outliers, and data validation.

**Tech Stack:** Python, pandas, numpy, seaborn  
**Key Features:** Data profiling, outlier detection, imputation strategies, visualization

### 4. [Interactive Dashboards](/projects/dashboards/)
Collection of interactive dashboards built with Power BI and Python (Plotly Dash) for visualizing market trends, portfolio performance, and economic indicators.

**Tech Stack:** Power BI, Python, Plotly Dash, DAX  
**Key Features:** Real-time data updates, interactive filters, drill-down capabilities

## 🚀 Getting Started

### Prerequisites

- Python 3.9 or higher
- pip or conda for package management
- Git for version control
- (Optional) Power BI Desktop for dashboard projects

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/ConnorT1997/ConnorT.git
   cd ConnorT
   ```

2. **Set up a virtual environment:**
   ```bash
   # Using venv
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
   # Or using conda
   conda create -n portfolio python=3.9
   conda activate portfolio
   ```

3. **Install dependencies:**
   ```bash
   # Install project-specific dependencies
   # Each project has its own requirements.txt
   cd projects/<project-name>
   pip install -r requirements.txt
   ```

4. **Configure environment variables:**
   ```bash
   # Copy the example environment file
   cp .env.example .env
   
   # Edit .env with your API keys and configurations
   # See .env.example for required variables
   ```

### Running Projects

Each project contains its own README with specific instructions. General pattern:

```bash
# Navigate to project directory
cd projects/<project-name>

# Run Python scripts
python src/main.py

# Or launch Jupyter notebooks
jupyter notebook notebooks/
```

## 📊 Project Structure

```
ConnorT/
├── projects/                      # All project folders
│   ├── news-email-bot/           # Automated news aggregation
│   ├── portfolio-analytics/      # Investment portfolio analysis
│   ├── data-cleaning-eda/        # Data preparation examples
│   └── dashboards/               # Visualization projects
├── .env.example                  # Environment template
├── .gitignore                    # Git ignore rules
├── CODE_OF_CONDUCT.md           # Community guidelines
├── CONTRIBUTING.md              # Contribution guidelines
├── LICENSE                       # Project license
├── README.md                     # This file
└── SECURITY.md                   # Security policy
```

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

## 📧 Contact

**Connor T**  
- GitHub: [@ConnorT1997](https://github.com/ConnorT1997)
- LinkedIn: [Connect with me](https://linkedin.com/in/your-profile)
- Email: your.email@example.com

## 📄 License

This project is licensed under a custom license based on MIT - see the [LICENSE](LICENSE) file for details.

## 🔒 Security

Please see [SECURITY.md](SECURITY.md) for information on reporting security vulnerabilities.

---

⭐ **If you find this portfolio helpful, please consider giving it a star!**
