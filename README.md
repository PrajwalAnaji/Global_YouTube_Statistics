# 📊 Global YouTube Statistics Analysis
<hr style="height:1px; border:none; background-color:#ccc;">

## 🌎 Project Overview

This project performs an in-depth **Exploratory Data Analysis (EDA)** on a dataset containing worldwide YouTube channel statistics.  
It uncovers hidden patterns and delivers actionable insights about **subscribers**, **video views**, **earnings**, **content categories**, and **country-specific trends** impacting YouTube growth and monetization.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📂 Dataset Information

- **File**: `Global_YouTube_Statistics.csv`
- **Encoding**: ISO-8859-1
- **Description**:
  - Country of operation
  - Content category
  - Subscriber count
  - Video views
  - Uploads
  - Estimated yearly earnings
  - Population and demographic statistics (e.g., education levels, unemployment rates)

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 🛠️ Technologies & Libraries Used

| Tool/Library        | Purpose                                              |
|----------------------|------------------------------------------------------|
| Python               | Main programming language                           |
| Pandas               | Data manipulation and preprocessing                 |
| NumPy                | Numerical computations                              |
| Matplotlib           | Basic data visualization (bar charts, plots)         |
| Seaborn              | Advanced visualization (heatmaps, scatter plots)     |
| Jupyter Notebook     | Interactive coding and visualization                |
| Plotly (optional)    | Interactive dashboards (optional)                   |

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📝 Analysis Workflow

- **Data Cleaning**:
  - Removed duplicate entries and irrelevant features.
  - Handled missing values by dropping incomplete records.
  - Reformatted and standardized feature names where necessary.

- **Feature Engineering**:
  - Created `avg_yearly_earning`:  
    Mean of `lowest_yearly_earnings` and `highest_yearly_earnings`.
  - Created `revenue_per_subscriber`:  
    Earnings divided by subscriber count.
  - Computed derived insights like **revenue efficiency** and **growth rates**.

- **Exploratory Data Analysis (EDA)**:
  - **Correlation Analysis**:
    - Heatmap showing relationships among numerical features.
  - **Scatter Plot Analysis**:
    - Subscribers vs Average Yearly Earnings (log-log scale)
    - Urban Population vs Uploads
    - Unemployment Rate vs Recent Subscriber Growth
    - Population vs Subscribers
    - Education Enrollment vs Average Yearly Earnings
  - **Ranking Analyses**:
    - Top 10 YouTubers by subscriber growth
    - Top countries by YouTuber count
    - Top YouTubers by revenue per subscriber
    - Top countries by monetization rates
  - **Category-wise Analysis**:
    - Content category vs Average Earnings
    - Views distribution across different content categories

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📊 Visualizations

- 📈 Correlation Heatmaps
- 📊 Bar Charts (e.g., Top YouTuber Countries, Content Categories)
- 🧮 Scatter Plots with regression lines
- 📉 Growth Trend Lines (Subscribers over time)
- 🌍 Geographical Maps (YouTuber distribution by country)
- 🍰 Pie Charts (Views distribution across categories)
- 🧩 Treemaps (Category distribution visualization)

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📌 Key Insights & Findings

- Strong positive correlation between **subscribers** and **views**.
- Content in **"Shows"** and **"Entertainment"** categories tends to earn higher than others.
- **Revenue per subscriber** significantly varies depending on the country.
- **Upload frequency** has a weaker impact compared to **content quality** on success.
- Macroeconomic indicators (e.g., unemployment, education rates) show **limited influence** on YouTube success metrics.
- Certain **outlier channels** achieve exceptional results despite fewer uploads, emphasizing the role of **content strategy**.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 🎯 Recommendations for Aspiring YouTubers

- Focus on **high-earning content categories** like Shows, Entertainment, and Comedy.
- Prioritize **content quality** over **upload quantity**.
- Maintain **consistent short-term activity** to boost visibility and earnings.
- Explore **underserved markets** with higher revenue per user.
- Analyze **outlier success strategies** to replicate effective growth patterns.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 🚀 Future Improvements

- Develop a **predictive model** to forecast subscriber growth based on country, category, and uploads.
- Build an **interactive dashboard** using **Plotly Dash** or **Power BI**.
- Integrate **sentiment analysis** of video comments to understand audience engagement.
- Perform **time series analysis** to predict future YouTube trends.

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">

## 📩 Contact

For any questions, feedback, or collaboration opportunities, feel free to reach out!

✨ **Thank you for visiting this project!** ✨

<hr style="height:2px; border:none; background-color:#e1e4e8; margin:24px 0;">
