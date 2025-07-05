# 🏏 Analysis of Players’ Performance in All Three International Formats (2013–2022)

## 📌 Project Overview  
This project analyzes the performance of international cricket players across **ODI**, **Test**, and **T20** formats from **2013 to 2022**. The goal is to identify top-performing **batsmen**, **bowlers**, and **all-rounders**, and build the **Best Playing XI** based on actual performance metrics.

## 🌐 Data Source  
The data was scraped directly from [**ESPNcricinfo**](https://www.espncricinfo.com/) using Python (see webscrapping.ipynb). The dataset includes :
- 🏏 **Runs, Strike Rate, Average** (for batsmen)  
- 🎯 **Wickets, Economy Rate, Bowling Average** (for bowlers)  
- 🧢 Combined metrics for all-rounders  

## 🎯 Objectives

- Identify **top performers** across all three formats (**Test, ODI, T20**)
- Select a balanced Best Playing XI for each format based on real stats
- Compare players’ performance over a 10-year period
- Visualize trends and highlight standout individual performances

## 🧪 Data Preparation

To prepare the scraped data for analysis:

- Removed unwanted characters (like commas in numbers) and cleaned HTML tags
- Standardized column names and player names for consistency
- Converted data types (e.g., strings to integers/floats)
- Filtered out irrelevant entries and incomplete rows

These steps ensured the dataset was ready for reliable and structured analysis.

## 📊 Exploratory Analysis

Key insights include:

- 🏏 **Top 10 Batsmen, Bowlers, and All-rounders** by format
- 🎯 **Year-wise dominance** of specific players
- 🧢 All-rounders with consistent contributions in both departments
- 📉 Notable **performance trends**, peaks, and declines

Visualizations created:

- 📊 Bar charts and 📈 line graphs to show trends and rankings
- Side-by-side comparisons of players across formats and years

## 🏆 Best XI Selection

The **Best Playing XI** was selected based on:

- Based purely on actual performance stats
- A **well-balanced team** including:
  - 🏏 Top-order and middle-order batsmen  
  - 🎯 Lead pace and spin bowlers  
  - 🧢 One or more quality all-rounders  
  - 🧤 A wicket-keeper with strong batting records  

## 🛠️ Tools & Technologies

| Tool/Library         | Purpose                        |
|----------------------|--------------------------------|
| Python               | Core programming language      |
| Pandas, NumPy        | Data handling and manipulation |
| Matplotlib, Seaborn  | Visualizations and charts      |
| BeautifulSoup, Requests | Web scraping               |

## 📁 Project Structure
```
📦 Analysis of Players Performance in all three International formats (2013 – 2022)
├── Final_PPT.pptx
├── all_odi.ipynb
├── all_t20.ipynb
├── all_test.ipynb
├── bat_odi.ipynb
├── bat_t20.ipynb
├── bat_Test.ipynb
├── bowling(odi).ipynb
├── bowling(t20).ipynb
├── bowling(test).ipynb
├── webscrapping.ipynb
├── batting(odi).csv
├── batting(t20).csv
├── batting(test).csv
├── bowling(odi).csv
├── bowling(T20).csv
├── bowling(Test).csv
├── allrounder(odi).csv
├── allrounder(t20).csv
├── allrounder(test).csv
├── top_5_bow_odi.csv
├── top_5_bow_t20.csv
├── top_5_bow_test.csv
├── odi_allrounder.csv
├── t20_allrounder.csv
└── test_allrounder.csv
```


## 🚀 How to Use
- Open Notebooks to explore format-wise player stats and visualizations.

- Check Presentation Final_PPT.pptx for quick project summary.

- Run webscrapping.ipynb to scrape fresh data from ESPNcricinfo (if needed).


## 📌 Key Learnings
 - Hands-on experience with web scraping from real-world websites

 - Cleaned and structured large sets of performance data for analysis

 - Gained insights into sports analytics and team building

 - Used visual storytelling to justify decisions in team selection
