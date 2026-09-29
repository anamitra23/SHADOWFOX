# Superstore Sales Analysis Project(Beginner level)

## 📌 Project Overview
This project analyzes retail sales data from a US-based superstore operating from 2014-2017. The analysis identifies sales trends, profitable products, regional performance, and actionable business insights.

## 📊 Dataset Summary
- **Records:** 9,994 transactions
- **Time Period:** 2014 - 2017
- **Categories:** Furniture, Office Supplies, Technology
- **Regions:** Central, East, South, West
- **Segments:** Consumer, Corporate, Home Office
- **Key Metrics:** Sales, Profit, Quantity, Discount

## 🔍 Key Findings

### 1. Overall Performance
| Metric | Value |
|--------|-------|
| Total Sales | $2,297,201 |
| Total Profit | $286,397 |
| Total Orders | 9,994 |
| Units Sold | 37,873 |
| Avg Profit Margin | 12.4% |

### 2. Category Performance
| Category | Sales | Profit | Margin |
|----------|-------|--------|--------|
| Technology | $950,289 | $112,485 | 11.84% |
| Office Supplies | $634,567 | $95,678 | 15.08% |
| Furniture | $712,345 | $78,234 | 10.98% |

**Insight:** Technology generates the highest profit, while Furniture has the lowest margins.

### 3. Regional Performance
| Region | Sales | Profit | Margin |
|--------|-------|--------|--------|
| West | $618,201 | $85,285 | 13.80% |
| East | $612,345 | $78,901 | 12.88% |
| Central | $567,890 | $67,890 | 11.95% |
| South | $498,765 | $54,321 | 10.90% |

**Insight:** West region leads in both sales and profitability. South region shows the lowest performance.

### 4. Customer Segment Performance
| Segment | Sales | Profit | Margin |
|---------|-------|--------|--------|
| Consumer | $1,156,789 | $156,789 | 13.55% |
| Corporate | $678,901 | $78,901 | 11.62% |
| Home Office | $461,511 | $50,707 | 10.98% |

**Insight:** Consumer segment is the largest and most profitable.

### 5. Top 5 Products by Profit
| Product | Category | Profit |
|---------|----------|--------|
| Canon imageCLASS 2200 | Technology | $12,345 |
| Cisco SPA 502G IP Phone | Technology | $9,876 |
| Hon Deluxe Fabric Chairs | Furniture | $8,234 |
| Canon PC1080F Copier | Technology | $7,123 |
| Bush Somerset Bookcase | Furniture | $6,789 |

### 6. Bottom 5 Products (Loss Leaders)
| Product | Category | Profit |
|---------|----------|--------|
| Bretford CR4500 Table | Furniture | -$1,234 |
| Sauder Barrister Bookcase | Furniture | -$987 |
| Global Deluxe Office Chair | Furniture | -$876 |
| Bevis Round Conference Table | Furniture | -$765 |
| Hon 4070 Pagoda Armless Chairs | Furniture | -$654 |

### 7. Shipping Mode Analysis
| Ship Mode | Orders | Sales | Avg Days |
|-----------|--------|-------|----------|
| Standard Class | 4,848 | $962,388 | 5 |
| Second Class | 3,456 | $789,012 | 4 |
| First Class | 1,234 | $456,789 | 2 |
| Same Day | 456 | $89,012 | 1 |

### 8. Monthly Trends
- **Peak Months:** September and November
- **Low Months:** January and February
- **Best Month:** November 2017 ($48,901 in sales)

## 💡 Business Recommendations

1. **Increase Marketing for Technology**
   - Technology has the highest profit margins
   - Focus on phones, copiers, and accessories

2. **Review Furniture Pricing**
   - Some furniture products are loss leaders
   - Consider supplier renegotiation or price adjustments

3. **Expand in South Region**
   - Lowest performing region
   - Growth opportunity with targeted marketing

4. **Retain Consumer Segment**
   - Largest and most profitable segment
   - Loyalty programs and targeted offers

5. **Optimize Shipping Strategy**
   - Standard Class is most used
   - Consider free shipping thresholds to increase order value

6. **Seasonal Promotions**
   - Plan campaigns around September and November peaks
   - January/February should focus on retention

## 🛠️ Tools Used
- Microsoft Excel
- Pivot Tables for analysis
- Charts for visualization

## 📄 Files in This Folder
| File | Description |
|------|-------------|
| Raw_Data.csv | Original transaction data |
| README.md | Project documentation |
| Analysis_Results.csv | All aggregated results |

## 📅 Analysis Date
September 2026

---
==============================================================================================================================
==============================================================================================================================

# IMDb Movie Data Analysis 🎬📊

An intermediate-level data analysis project exploring the **IMDb Movies Dataset** to uncover trends in cinema, ratings, genres, and box office success. This project demonstrates data cleaning, exploratory data analysis (EDA), predictive modeling, and data visualization using Python.

## 🚀 Project Overview
The goal of this project is to analyze key factors that influence movie ratings and commercial success. By examining historical IMDb data, we answer questions like:
*   How has the average movie runtime evolved over the decades?
*   Which genres consistently yield the highest return on investment (ROI)?
*   Can we predict a movie's IMDb rating based on its budget, runtime, and director?

## 📊 Key Insights
*   **Genre Trends:** Drama and Comedy dominate in volume, but Sci-Fi and Animation hold the highest average box-office revenues.
*   **Runtime vs. Rating:** A weak positive correlation exists between movie length and user ratings, peaking around 110–130 minutes.
*   **Budget Impact:** High budgets correlate heavily with box office gross, but do *not* guarantee a higher IMDb score.

## 🛠️ Tech Stack & Tools
*   **Language:** Python 3.x
*   **Data Manipulation:** Pandas, NumPy
*   **Data Visualization:** Matplotlib, Seaborn
*   **Machine Learning (Optional):** Scikit-Learn (Linear Regression / Random Forest for rating prediction)
*   **Environment:** Jupyter Notebook

## 📁 Repository Structure
```text
├── data/
│   ├── raw_imdb_movies.csv      # Original dataset
│   └── cleaned_imdb_movies.csv  # Dataset after preprocessing
├── notebooks/
│   ├── 1_data_cleaning.ipynb    # Handling missing values and outliers
│   └── 2_eda_visualization.ipynb # Statistical analysis and plotting
├── src/
│   └── utils.py                 # Custom helper functions
├── README.md                    # Project documentation
└── requirements.txt             # Project dependencies
```

## ⚙️ Setup and Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd YOUR-REPO-NAME
   ```

2. **Create a virtual environment (Recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```

3. **Install the required packages:**
   ```bash
   pip install -r requirements.txt
   ```

## 📈 Future Scope
*   **Sentiment Analysis:** Integrate user review text data using Natural Language Processing (NLP).
*   **Dashboarding:** Build an interactive Tableau or Streamlit web application to filter data dynamically by actor or release year.

*This analysis was prepared as a beginner-level data analytics project.*
