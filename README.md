# YouTube Sports Channels Analysis 📊

## Project Overview

This project analyzes a dataset of **YouTube sports channels** to understand trends in channel growth, content strategy, and audience engagement.

The dataset contains information such as:

* Channel Name
* Channel Creation Date
* Subscriber Count
* Total Views
* Video Count

The goal of this project was to **clean the raw dataset, perform exploratory analysis, and build an interactive dashboard** to extract meaningful insights.

---

## Dataset Source

The dataset was obtained from the **Kaggle** and contains information about various sports-related YouTube channels.

Since the raw data contained formatting issues and inconsistencies, several data cleaning steps were required before analysis.

---

## Data Cleaning

The following steps were performed to prepare the dataset:

* Removed duplicate records
* Fixed encoding issues in channel names (special characters/symbols)
* Standardized column formatting
* Converted creation dates into proper date format
* Extracted **Year of Creation** from the date column
* Created a **Generation Category** for channels:

  * **Old Gen** (2005–2010)
  * **Mid Gen** (2011–2020)
  * **New Gen** (After 2020)

Additional helper columns were created to support analysis.

---

## Analysis Performed

Several metrics were created to better understand channel performance:

* **Views per Video** – measures content efficiency
* **Subscribers per Video** – shows subscriber growth relative to uploads
* **Channel Age** – years since channel creation
* **Subscribers per Year** – estimated channel growth speed

These metrics helped compare channels across different generations.

---

## Dashboard

An **Excel dashboard** was created to visualize the insights.

### Dashboard Features

* KPI cards showing:

  * Total Channels
  * Total Subscribers
  * Total Views
  * Average Video Count
* Channel creation trends over time
* Distribution of channels by generation
* Top channels by subscribers
* Content efficiency analysis (Views per Video)
* Scatter plot comparing **views vs video count**
* Interactive **slicers** for filtering data

---

## Key Insights

Some notable insights from the analysis include:

* Older channels generally have **higher total subscribers** due to longer platform presence.
* Newer channels often show **higher growth rates** relative to their age.
* Some channels generate **high views with fewer videos**, indicating highly efficient content strategies.
* The number of sports channels increased significantly during certain growth periods of YouTube.

---

## Tools Used

* **Microsoft Excel**

  * Data Cleaning
  * Pivot Tables
  * Power Query
  * Dashboard Visualization

---

## Project Structure

```
youtube-sports-channel-analysis/
├── dashboard/
│   └── YT sports.xlsx
│
└── README.md
```

---

## Future Improvements

Possible extensions for this project:

* Perform deeper statistical analysis
* Use **Python (Pandas, Matplotlib, Seaborn)** for advanced EDA
* Build an **interactive dashboard using Power BI or Tableau**
* Analyze engagement metrics such as likes, comments, or watch time

---

## Author
Musaiyab Sheikh

Musaiyab Sheikh
