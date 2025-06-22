# ⚾ MLB Player KPI & Predictive Ranking Model (2024 Season)

## 📌 Objective

This project analyzes **2024 season MLB batter statistics** to identify **Key Performance Indicators (KPIs)** that contribute to player success—particularly their **expected contribution to team wins**. Using advanced metrics such as **xWOBA, Barrel Rate**, and **Hard Hit Rate**, the project builds a **predictive model** and **ranks players** based on these KPIs.

---

## 📊 Dataset

* **Scope**: 129 MLB players with **≥500 plate appearances** in the 2024 season

* **Features**:

  * **Basic Info**: Player Name, ID, Season Year, Plate Appearances (PA)
  * **Plate Discipline**: Strikeout Rate, Walk Rate, Swing Rate, Whiff Rate
  * **Statcast Metrics**: WOBA, Expected WOBA (xWOBA), Barrel Rate, Hard Hit Rate,
    Sweet Spot %, Average Best Speed, Average Hyper Speed

* **Source**: Statcast & Baseball Savant (2024 season data)

---

## 🔍 Exploratory Data Analysis

### 🔑 Key Analyses

* **Distribution of xWOBA**: Understands the spread of expected offensive performance
* **Swing vs Whiff Rate Scatterplot**: Visualizes plate discipline and power potential
* **Correlation Matrix**: Evaluates interrelationships between all numerical features
* **Top Performers**: Identifies top players by Expected WOBA
* **Overperformers & Underperformers**: Compares actual WOBA vs. xWOBA to find discrepancies

### 📌 Sample Insights

* **Top Expected Performers**:

  * Aaron Judge
  * Juan Soto
  * Shohei Ohtani

* **Underperformers** (xWOBA > WOBA):

  * Juan Soto
  * Corey Seager

* **Overperformers** (WOBA > xWOBA):

  * Daulton Varsho
  * Trea Turner

---

## 📈 Visualizations

* 📊 Distribution plot of **Expected WOBA**
* 🔍 Scatterplot of **Swing Rate vs Whiff Rate**
* 🔥 Heatmap of **correlation matrix** for feature relationships
* 📉 Regression plot: **Hard Hit Rate vs Barrel Rate**
* 📋 Tables of **Top 10 Overperformers and Underperformers** (WOBA differential)

---

## 🔧 Next Steps

* **Modeling**:
  Train predictive models (e.g., Linear Regression, Random Forest) to estimate WAR or team contribution from KPIs.

* **Ranking System**:
  Build a composite score that combines the most predictive KPIs to rank player value.

* **Validation**:
  Compare predicted player value against actual WAR, team wins, or external ranking systems.

---

## 🧰 Tools Used

* Python 3.11+
* **Pandas**, **NumPy** — data cleaning & transformation
* **Seaborn**, **Matplotlib** — data visualization
* **Jupyter Notebook** — exploratory and modeling environment

