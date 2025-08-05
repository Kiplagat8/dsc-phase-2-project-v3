# <b>Movie Genre Investment Analysis – A Data-Driven Approach</b>

## Project Overview

As the film industry becomes increasingly competitive and data-centric, companies are investing in original content production to maximize profitability and viewer engagement. This project simulates a scenario in which a company is establishing a new movie studio and wants to make informed decisions on the types of films to invest in.

The objective of this analysis is to explore historical film data to identify **which genres perform best** in terms of **box office returns, profitability, and audience reception**. The findings are used to provide clear, data-backed recommendations that guide the business in its content creation strategy.

The project adheres to the **CRISP-DM (Cross-Industry Standard Process for Data Mining)** methodology and includes:
- A comprehensive **Jupyter Notebook** for technical analysis and modeling
- A **Tableau dashboard** for interactive visualizations
- A **PDF presentation** for non-technical stakeholders
- A **GitHub repository** to showcase the entire workflow

---

## Business Problem Statement

> Your company now sees all the big companies creating original video content, and they want to get in on the fun. They've decided to create a new movie studio but don’t have the necessary experience. As a data analyst, you are tasked with exploring what types of films are currently doing the best at the box office and translating those findings into actionable insights for decision-making.

---

##  Repository Structure
---
##  Datasets Used

1. **Box Office Mojo Dataset (bom_df):**
   - Budget, gross revenue, and titles of various films.

2. **The Numbers Dataset (tn_df):**
   - Revenue, genre, and distributor information.

3. **IMDb Titles Dataset (im.db):**
   - Title basics, genre classification, ratings, and runtime info.
   - Integrated later in the analysis to enhance insights with film ratings and metadata.

All datasets were cleaned, standardized, and merged into one **final dataset (`final_movie_analysis.csv`)** which was then exported to Tableau for advanced visualization.

---

## Methodology – CRISP-DM Framework

### 1. Business Understanding
- Define what success looks like: high-grossing, profitable film genres.
- Align business goals with analytical objectives.

### 2. Data Understanding
- Explore each dataset's structure and value.
- Understand key attributes: genre, revenue, budget, ratings, etc.

### 3. Data Preparation
- Clean and merge datasets.
- Remove missing or irrelevant values.
- Create new metrics: **ROI (Return on Investment)**, **Profit**, and normalized ratings.

### 4. Exploratory Data Analysis (EDA)
- **Univariate Analysis**: Budget distribution, genre frequency, rating trends.
- **Bivariate Analysis**: ROI vs Budget, Profit vs Rating.
- **Multivariate Analysis**: Heatmaps and scatter matrices to uncover deeper correlations.
- Use of statistical summaries and correlation matrices.

### 5. Visualization (Tableau)
- Export final dataset to Tableau.
- Create interactive charts on genre performance, ROI distribution, top-rated films, and more.

### 6. Recommendations
- Translate results into business strategy.
- Suggest investment areas and budgeting guidelines.

---

## Tableau Dashboard

An interactive dashboard has been developed in Tableau to support business decision-making. It includes:
- ROI performance by genre
- Average rating per genre
- Revenue vs Budget trends
- Top performing movies

🔗 [Click here to view the Tableau Dashboard](https://public.tableau.com/views/Movie_Studio/Genre_Profit_Roi?:language=en-GB&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)  

---

## Summary of Key Insights

- **Genres like Animation, Adventure, and Horror** consistently achieve high ROI with manageable budgets.
- **Action and Sci-Fi genres**, while expensive to produce, often dominate total gross revenue.
- **Ratings and profitability** show a positive correlation but are not always aligned—some high-rated films underperform financially.
- **Shorter runtimes** (under 120 mins) tend to do better in terms of ROI.

---

## Recommendations

- Invest in **high-ROI genres** such as Horror and Animation for greater returns on smaller budgets.
- Use **Action and Adventure** films strategically with higher budgets to target blockbuster markets.
- Monitor audience **ratings and genre popularity trends** to optimize release windows and promotions.
- Develop a **balanced film portfolio**: mix of high-budget blockbusters and low-budget high-return productions.

---

## Technologies Used

- **Languages:** Python 3, SQL (SQLite3)
- **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, SQLite
- **Visualization:** Tableau Public
- **Platform:** Jupyter Notebook
- **Version Control:** Git & GitHub

---

## Author

**Kenneth Ronald Kiplagat**  
Data Science Student at Moringa School  
GitHub: [https://github.com/Kiplagat8](https://github.com/Kiplagat8)  
Phone: +254 729 244 545

---

##  How to Use This Project

1. Clone the repo:
   ```bash
   git clone https://github.com/Kiplagat8/dsc-phase-2-project-v3.git
   cd dsc-phase-2-project-v3
