# ⚽ Football Performance Analysis: Messi vs Ronaldo vs Haaland vs Mbappé

![Python](https://img.shields.io/badge/Python-3.12-blue?logo=python)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas)

A statistical comparison of four of football's greatest forwards using Python, hypothesis testing, and exploratory data analysis.

---

## 📊 Results at a Glance

* ⚽ **All four players scored at statistically similar rates** when adjusted for playing time.
* 🎯 **Messi separated himself through significantly greater creative output**, particularly in assists, dribbles, and key passes.
* 📈 **Mbappé ranked second overall**, highlighting an exceptional career trajectory despite being much earlier in his career.

---

## 📸 Visual Highlights

> *Replace the image paths below with your exported PNG files.*

|               Radar Chart               |                Goals vs Assists               |
| :-------------------------------------: | :-------------------------------------------: |
| ![Radar Chart](figures/radar_charts.png) | ![Scatter Plot](figures/Scatter_Plot.png) |

|               Four Player Comparison              |              Composite Rankings             |
| :-----------------------------------------------: | :-----------------------------------------: |
| ![Comparison](figures/trend_lines_all_four.png) | ![Rankings](figures/Final_Composite_Rankings.png) |

---

# 📖 Overview

Football's greatest player debate is often driven by opinions, trophies, or raw goal totals.

This project approaches the discussion from a data science perspective by comparing the attacking performances of **Lionel Messi**, **Cristiano Ronaldo**, **Erling Haaland**, and **Kylian Mbappé** using statistical analysis.

Rather than asking:

> **Who scored the most goals?**

this project explores:

* Do elite forwards actually differ in goal-scoring efficiency?
* Does creativity separate the world's best players?
* Can statistical analysis provide a more objective perspective on football's biggest debate?

---

# 🎯 Objectives

The project aims to:

* Compare attacking performance across four elite forwards.
* Standardize statistics using per-90-minute metrics.
* Apply statistical hypothesis testing to evaluate performance differences.
* Develop an overall attacking profile using multiple performance indicators.
* Demonstrate the application of data science within sports analytics.

---

# 📂 Dataset

The analysis uses season-by-season player statistics across **All Competitions**, including:

* Goals
* Assists
* Minutes Played
* Appearances
* Goal Contributions
* Dribbles Completed
* Key Passes

To ensure fair comparisons, all attacking metrics were normalized using **per-90-minute statistics**.

---

# 🧠 Methodology

The project follows a complete data science workflow.

## 1. Data Preparation

* Data Cleaning
* Missing Value Handling
* Feature Engineering
* Per-90 Metric Calculation

## 2. Exploratory Data Analysis

* Descriptive Statistics
* Comparative Visualisations
* Distribution Analysis
* Career Performance Trends

## 3. Statistical Analysis

To determine whether observed differences were statistically significant, the following tests were performed:

* **Mann–Whitney U Test** (Messi vs Ronaldo)
* **Kruskal–Wallis Test** (Four-player comparison)

These non-parametric tests were selected because they do not assume normally distributed data.

## 4. Performance Evaluation

Players were evaluated using:

* Goals per 90
* Assists per 90
* Goal Contributions per 90
* Dribbles per 90
* Key Passes per 90
* Standardized Composite Performance Score

---

# 🛠 Libraries Used

* Python
* pandas
* NumPy
* SciPy
* Matplotlib
* scikit-learn
* Jupyter Notebook

---

# 📈 Key Findings

## Goal Scoring

After adjusting for playing time, **Messi, Ronaldo, Haaland, and Mbappé scored at statistically similar rates.**

## Creativity

The greatest differences emerged in creative metrics.

Messi consistently recorded significantly higher:

* Assists
* Key Passes
* Successful Dribbles

while maintaining elite goal-scoring output.

## Overall Attacking Profile

Using the standardized composite performance score:

🥇 Lionel Messi

🥈 Kylian Mbappé

🥉 Cristiano Ronaldo

4️⃣ Erling Haaland

Messi achieved the highest overall attacking profile by combining elite scoring with significantly greater creative contribution.

---

# 🚀 Getting Started

Clone the repository:

```bash
git clone https://github.com/yourusername/football-goat-analysis.git
```

Install the required packages:

```bash
pip install pandas numpy scipy matplotlib scikit-learn jupyter
```

Run the notebook:

```bash
jupyter notebook
```

---

# ⚠️ Limitations

Although this project provides an objective statistical comparison, several limitations should be considered.

* Different career lengths among players.
* Different leagues and football eras.
* Advanced metrics such as Expected Goals (xG) and Expected Assists (xA) were unavailable.
* League strength and tactical differences were not controlled for.
* Results compare attacking contribution rather than providing a definitive ranking of player quality.

---

# 🔮 Future Improvements

Future versions of the project could include:

* Expected Goals (xG)
* Expected Assists (xA)
* Progressive carries and passes
* Defensive contribution metrics
* League-strength adjustments
* Interactive dashboards using Plotly or Streamlit.

---

# 👤 Author

**Ingavi Kilavuka**

Marketing & Data Analytics enthusiast with a passion for Data Storytelling.

If you enjoyed this project, consider leaving a ⭐ on the repository or sharing your thoughts by opening an issue or starting a discussion.


If you found this project interesting or have suggestions for improving the analysis, feel free to connect or open an issue.
