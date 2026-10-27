# TMDB Movies Exploratory Data Analysis (EDA)

An exploratory data analysis project examining the financial performance, genre efficiency, and runtime trends of the movie industry using Python (Pandas, Matplotlib).

## 🎯 Project Objective
To analyze the TMDB 5000 Movie Dataset from a product and business perspective, identifying key drivers of financial success (ROI) and historical trends in content duration to guide content acquisition and production strategies.

## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** Pandas, NumPy, Matplotlib
* **Environment:** VS Code, Jupyter Notebook

## 📊 Key Findings & Insights

1. **The Blockbuster ROI Paradox:** 
   * While high-budget blockbusters (e.g., *Avatar*, *Titanic*) dominate in terms of absolute Net Profit, they carry massive financial risks. 
   * Conversely, compact-budget genres—most notably **Horror**—demonstrate the highest median ROI (**3.7x**), proving to be the most capital-efficient category for production and acquisition.

2. **Genre Profitability Distribution:**
   * Genres with lower production overhead (Horror, Western, Sci-Fi) significantly outperform massive adventure/animation projects in terms of return on investment per dollar spent.

3. **Runtime Stabilization:**
   * Historical analysis of movie runtimes (1970–2016) reveals high volatility in the 1970s–80s, followed by a strong stabilization trend starting in the mid-2000s, with median runtimes consistently settling around **100–105 minutes**.

## 🚀 Quick Start & How to Run

### 👁️ View Results Instantly (No setup required)
* **GitHub Viewer:** Simply open `analysis.ipynb` directly in this GitHub repository to view all executed code, interactive outputs, and charts without running anything.
* **Open in Google Colab:** Click the badge below to run and explore the notebook instantly in your browser:
  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/analysis.ipynb)

---

### 💻 Run Locally
1. **Clone the repository:**
   ```bash
   git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   cd YOUR_REPO_NAME
2. **Download Dataset:**
   Get tmdb_5000_movies.csv from Kaggle TMDB 5000 Movie Dataset and place it in the project root folder.
3. **Install Dependencies:**
   pip install -r requirements.txt
4. **Open & Run:**
   Open analysis.ipynb in VS Code or Jupyter Notebook and run all cells (Run All).