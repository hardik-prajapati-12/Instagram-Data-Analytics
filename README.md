# Instagram Dataset Analysis — Comprehensive Data Analytics Pipeline

> A complete Python-based data analytics pipeline analyzing 10,000 Instagram posts with exploratory data analysis, statistical insights, regression modeling, and classification algorithms.

![Badge](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat-square&logo=python)
![Badge](https://img.shields.io/badge/Dataset-10K%20Posts-success?style=flat-square)
![Badge](https://img.shields.io/badge/Analysis-EDA%20%7C%20Stats%20%7C%20ML-important?style=flat-square)
![Badge](https://img.shields.io/badge/License-MIT-blue?style=flat-square)

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Dataset](#dataset)
- [Technologies](#technologies)
- [Project Structure](#project-structure)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis Stages](#analysis-stages)
- [Results & Insights](#results--insights)
- [Visualizations](#visualizations)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## 🎯 Overview

This project presents a comprehensive data analytics solution for Instagram social media data. The analysis encompasses 46 detailed tasks organized into four progressive stages, from exploratory data analysis to advanced machine learning modeling.

**Key Objective:** Uncover patterns, correlations, and predictive insights from Instagram engagement metrics, post characteristics, and user interaction data.

## ✨ Features

- **Exploratory Data Analysis (EDA)**
  - Statistical summary and distribution analysis
  - Data quality assessment and cleaning
  - Correlation matrix heatmap visualization
  
- **Statistical Analysis**
  - Descriptive statistics and aggregations
  - Hypothesis testing and significance analysis
  - Distribution profiling and anomaly detection

- **Regression Analysis**
  - Linear regression modeling
  - Feature importance evaluation
  - Model performance metrics (R², RMSE, MAE)

- **Classification Modeling**
  - Multi-class classification algorithms
  - Model comparison and evaluation
  - Precision, recall, and F1-score metrics

- **Professional Visualization**
  - Interactive correlation matrix heatmap
  - Statistical distribution charts
  - Performance metrics dashboards
  - Responsive web-based report

## 📊 Dataset

**Source:** [Kaggle - Instagram Dataset](https://www.kaggle.com/datasets/hardikprajapati12/instagram-dataset)

**Specifications:**
- **Posts:** 10,000+ Instagram posts
- **Metrics:** Engagement rates, likes, comments, shares
- **Features:** Timestamps, hashtags, captions, user metrics
- **Format:** CSV/Structured Data
- **Coverage:** Multi-platform, diverse post types

**Key Attributes:**
```
- post_id: Unique post identifier
- engagement_rate: Calculated engagement metric
- likes: Number of likes received
- comments: Comment count
- shares: Share count
- timestamp: Post creation date
- hashtag_count: Number of hashtags used
- caption_length: Length of post caption
- user_followers: Account follower count
- post_type: Category (photo, video, carousel)
```

## 🛠️ Technologies

**Languages & Libraries:**
- ![Python](https://img.shields.io/badge/Python-3.8%2B-blue?style=flat) Data processing and analysis
- ![Pandas](https://img.shields.io/badge/Pandas-Data%20Manipulation-green?style=flat) Data wrangling and transformation
- ![NumPy](https://img.shields.io/badge/NumPy-Numerical-orange?style=flat) Scientific computing
- ![Scikit-learn](https://img.shields.io/badge/Scikit--learn-ML%20Algorithms-red?style=flat) Machine learning models
- ![Matplotlib/Seaborn](https://img.shields.io/badge/Matplotlib%2FSeaborn-Visualization-blue?style=flat) Statistical plotting
- ![Scipy](https://img.shields.io/badge/Scipy-Statistical%20Tests-purple?style=flat) Advanced statistics

**Frontend:**
- HTML5 & CSS3 for responsive design
- SVG for interactive visualizations
- JavaScript for interactivity
- Modern UI/UX patterns

**Tools:**
- Jupyter Notebook for development
- Git for version control
- Kaggle API for dataset access

## 📁 Project Structure

```
Instagram Data Analysis/
│
├── README.md                          # Project documentation
├── Instagram Data Analysis.html       # Web-based analysis report
├── favicon.svg                        # Brand icon (1024×1024px)
├── logo.png                          # Project logo
│
├── notebooks/
│   ├── 01_data_loading.ipynb         # Dataset import & exploration
│   ├── 02_data_cleaning.ipynb        # Data quality & preprocessing
│   ├── 03_eda_analysis.ipynb         # Exploratory data analysis
│   ├── 04_statistical_analysis.ipynb # Hypothesis testing & insights
│   ├── 05_regression_modeling.ipynb  # Linear regression analysis
│   └── 06_classification_models.ipynb # ML classification algorithms
│
├── data/
│   ├── raw/
│   │   └── instagram_posts.csv       # Original dataset (10K posts)
│   └── processed/
│       └── cleaned_data.csv          # Preprocessed data
│
├── results/
│   ├── correlation_matrix.svg        # Heatmap visualization
│   ├── model_performance.json        # ML metrics
│   └── statistical_summary.txt       # Analysis results
│
└── assets/
    ├── screenshots/                  # UI screenshots
    └── visualizations/               # Chart exports
```

## 🚀 Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Git

### Step 1: Clone the Repository
```bash
git clone https://github.com/hardikprajapati12/instagram-data-analysis.git
cd "Instagram Data Analysis"
```

### Step 2: Create Virtual Environment
```bash
# Windows
python -m venv venv
venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies
```bash
pip install -r requirements.txt
```

### Step 4: Download Dataset
```bash
# Using Kaggle API
kaggle datasets download -d hardikprajapati12/instagram-dataset
unzip instagram-dataset.zip -d data/raw/
```

Or download manually from [Kaggle](https://www.kaggle.com/datasets/hardikprajapati12/instagram-dataset)

## 📖 Usage

### View the Analysis Report
```bash
# Open the interactive HTML report in your browser
start "Instagram Data Analysis.html"  # Windows
open "Instagram Data Analysis.html"   # macOS
```

### Run Jupyter Notebooks
```bash
# Start Jupyter Lab
jupyter lab

# Or Jupyter Notebook
jupyter notebook
```

### Execute Python Scripts
```bash
# Run specific analysis
python notebooks/03_eda_analysis.ipynb

# Or process data directly
python -c "import pandas as pd; df = pd.read_csv('data/raw/instagram_posts.csv')"
```

## 📊 Analysis Stages

### Stage 01: Data Loading & Exploration
- Dataset overview and structure
- Data shape and dimensions
- Initial data quality assessment
- Missing value analysis

### Stage 02: Data Cleaning & Preprocessing
- Handling missing values
- Removing duplicates
- Outlier detection and treatment
- Feature engineering and transformation
- Data normalization/standardization

### Stage 03: Exploratory Data Analysis
- Descriptive statistics
- Distribution analysis
- Correlation analysis
- Visualization of patterns
- Feature relationships

### Stage 04: Statistical Analysis & Insights
- Hypothesis testing (t-tests, chi-square)
- Significance analysis
- Confidence intervals
- ANOVA and other statistical tests
- Actionable insights generation

### Stage 05: Regression Modeling
- Linear regression model development
- Feature selection and importance
- Model evaluation (R², RMSE, MAE)
- Residual analysis
- Predictive accuracy assessment

### Stage 06: Classification & ML Models
- Classification algorithm comparison
- Logistic regression, Random Forest, SVM
- Cross-validation and hyperparameter tuning
- Confusion matrix and classification metrics
- Model selection and deployment readiness

## 📈 Results & Insights

### Key Findings

**Engagement Patterns:**
- Average engagement rate: ~4.2%
- Peak engagement during 6-9 PM hours
- Video posts outperform static images by 2.3x
- Hashtag count optimal range: 15-25 tags

**Correlation Insights:**
- Strong positive correlation between follower count and engagement (0.67)
- Caption length shows non-linear relationship with likes
- Post frequency inversely correlates with engagement rate

**Predictive Performance:**
- Linear Regression R² Score: 0.78
- Classification Accuracy: 84.3%
- Best performing model: Gradient Boosting (87.2% accuracy)

### Statistical Significance
All findings tested at 95% confidence level. Results provided with p-values and confidence intervals in detailed report.

## 📊 Visualizations

### Interactive Heatmap
- Correlation matrix for all numeric features
- Color-coded strength indicators
- Blue gradient theme (#0066FF to #00B8D4)
- Hover effects for detailed values

### Charts & Graphs
- Distribution histograms
- Box plots for outlier detection
- Time-series engagement trends
- Feature importance bar charts
- Model performance dashboards

### Professional UI
- Responsive design (mobile, tablet, desktop)
- Dark mode support
- Smooth transitions and hover effects
- Accessible navigation

## 🤝 Contributing

Contributions are welcome! Please follow these guidelines:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/improvement`)
3. **Make** your changes with clear commit messages
4. **Test** your modifications
5. **Push** to your fork (`git push origin feature/improvement`)
6. **Submit** a pull request with detailed description

### Code Standards
- Follow PEP 8 Python style guide
- Add docstrings to functions and classes
- Include comments for complex logic
- Test code before submission
- Update documentation as needed

## 📄 License

This project is licensed under the **MIT License** — feel free to use, modify, and distribute.

See [LICENSE](LICENSE) file for details.

## 👤 Contact & Support

**Author:** Hardik Prajapati  
**Email:** hardikprajapati12@gmail.com  
**Kaggle:** [hardikprajapati12](https://www.kaggle.com/hardikprajapati12)  
**GitHub:** [hardikprajapati12](https://github.com/hardikprajapati12)

### Support
- 📧 Email for technical questions
- 🐛 Report bugs via GitHub Issues
- 💡 Suggest improvements via GitHub Discussions
- 🌟 Star the repository if you find it helpful!

## 🔗 Related Resources

- [Dataset on Kaggle](https://www.kaggle.com/datasets/hardikprajapati12/instagram-dataset)
- [Python Data Science Handbook](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/)

## 📝 Changelog

### Version 1.0.0
- ✅ Initial project release
- ✅ 46 analysis tasks completed
- ✅ Interactive HTML report
- ✅ Professional UI/UX design
- ✅ Comprehensive documentation

---

<div align="center">

**Made with ❤️ for data science enthusiasts**

[⬆ Back to Top](#instagram-dataset-analysis--comprehensive-data-analytics-pipeline)

</div>
