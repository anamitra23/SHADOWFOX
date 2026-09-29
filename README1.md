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
