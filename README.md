# 🎬 MyAnimeList Data Analysis & Dashboard 🌌

## 📌 Project Overview

This is a personal data analysis project based on my anime watch history from MyAnimeList. The goal of this project is to explore viewing patterns, preferences, and trends using data analysis techniques.

The project takes exported raw data, cleans it for privacy and usability, and transforms it into a comprehensive, high-resolution data dashboard. The final output is a fully customized **Dark Mode Dashboard** inspired by the aesthetics of *The Eminence in Shadow*, *One Piece*, and *Dragon Ball Z*.

## 🎯 Objectives

  * Analyze personal anime watching trends over time.
  * Identify favorite genres, themes, and rating patterns.
  * Build visual, actionable insights from raw dataset exports.
  * Create an automated, aesthetically pleasing tracking dashboard.

## 📈 Project Status

  * ✔️ **Data collection completed**
  * ✔️ **Data cleaning completed**
  * ✔️ **Exploratory Data Analysis (EDA) completed**
  * ✔️ **Python Visualization & Dashboard creation completed**
  * 🔜 **Power BI / Tableau integration (Planned)**

-----

## 📂 Data Source & Files

The dataset was obtained from my personal MyAnimeList account export. It contains information about watched anime, ratings, genres, and watch status.

  * **`myanimelist.xml`** – The raw data export directly from MyAnimeList.
  * **`myanimelist_cleaned.csv`** – The processed, cleaned dataset used for analysis.
  * **`MyAnimeList.ipynb`** – The Jupyter Notebook documenting the full workflow (data cleaning, EDA, and visualization).

## 🧹 Data Cleaning

Before analysis, the raw XML/CSV dataset was strictly processed to ensure privacy and usability:

  * Removed all personal and sensitive user information.
  * Handled missing, null, and inconsistent values.
  * Standardized column formats and date-times.
  * Filtered relevant fields specifically for statistical analysis.

-----

## ✨ Dashboard Features

  * ⏱️ **Dynamic KPIs:** Automatically calculates total watch time (in hours), highest-rated anime, and total completion stats.
  * 🎨 **Custom Color Palette:** Features a bespoke hex palette including "Goku Orange", "Super Saiyan Gold", "Grand Line Blue", and "Shadow Purple".
  * 🧩 **9-Grid Layout:** Utilizes Matplotlib's `GridSpec` to beautifully organize diverse data visualizations into a single exportable graphic.
  * ⚙️ **Advanced Styling:** Includes custom bounding boxes, expanded coordinate frames to prevent pie chart text overlap, and native text-wrapping for long anime titles.

## 📊 Visualizations Included

The Python dashboard generates the following 9 modular plots:

1.  📈 **Distribution of Anime Scores** *(Histogram with KDE)*
2.  📉 **Watching Progress Over Time** *(Time-series Line Chart)*
3.  ☄️ **Watched vs. Total Episodes** *(Scatter Plot with Trendline)*
4.  🏆 **Top 10 Rated Anime Series** *(Custom Formatted Table)*
5.  🍩 **Anime Watching Status** *(Donut Chart with external labels)*
6.  📊 **Completion Rate by Series Type** *(Bar Chart)*
7.  📝 **Series Type Notes** *(Formatted Text Box)*
8.  📦 **Score Distribution by Series Type** *(Box Plot without outliers)*
9.  🎯 **Episodes Watched vs. Score** *(Scatter Plot with Regression Line)*

-----

## 🛠️ Tools & Technologies

  * **Python** (Core logic and scripting)
  * **Pandas & NumPy** (Data cleaning, manipulation, and statistical analysis)
  * **Seaborn & Matplotlib** (Advanced data visualization and dashboard grid creation)
  * **Power BI / Tableau** (Exploratory tools for future interactive dashboard iterations)

## 💻 Installation & Setup

**1. Clone the repository** 📥

```bash
git clone https://github.com/yourusername/MyAnimeList-Dashboard.git
cd MyAnimeList-Dashboard
```

**2. Install required dependencies** 📦
Make sure you have Python installed, then run:

```bash
pip install pandas numpy matplotlib seaborn
```

**3. Add your data** 📁
Ensure your cleaned dataset is named `myanimefile.csv` and is placed in the same directory as the Jupyter Notebook.

**4. Run the Notebook** ▶️
Open `MyAnimeList.ipynb` in Jupyter Notebook, JupyterLab, or VS Code and execute all cells to generate your dashboard.

-----

## 🚀 Future Work

  * Build fully interactive dashboards via Power BI or Tableau.
  * Add deeper trend analysis regarding seasonal anime drops.
  * Compare personal ratings vs. global MyAnimeList popularity scores.
  * Automate data updates via API rather than manual XML exports.

## 📎 Note

*This is a hobby project combining my interest in anime and data analysis. The dataset is anonymized and used only for personal learning and portfolio purposes.*