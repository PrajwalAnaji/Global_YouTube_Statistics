📊 Global YouTube Statistics Analysis

This project performs an in-depth Exploratory Data Analysis (EDA) on a dataset containing worldwide YouTube channel statistics.
It uncovers hidden patterns and delivers actionable insights about subscribers, video views, earnings, content categories, and country-specific trends impacting YouTube growth and monetization.

📂 Dataset Information:
File: Global_YouTube_Statistics.csv
Encoding: ISO-8859-1
Description:
This dataset includes detailed information on YouTube channels across the globe, such as:
Country of operation
Content category
Subscriber count
Video views
Uploads
Estimated yearly earnings
Population and demographic statistics (e.g., education, unemployment rates)

🛠️ Technologies & Libraries Used:
Tool/Library	Purpose
Python	Main programming language
Pandas	Data manipulation and preprocessing
NumPy	Numerical computations
Matplotlib	Data visualization (basic plots)
Seaborn	Advanced data visualization (heatmaps, scatter plots)
Jupyter Notebook	Interactive coding and visualization
Plotly (optional for interactive plots)	(optional) Interactive dashboard creation

📝 Analysis Workflow:
1. Data Cleaning
Removed duplicate entries and irrelevant features.
Handled missing values by dropping incomplete records.
Reformatted and standardized feature names where necessary.
2. Feature Engineering
Created avg_yearly_earning:
The mean of the lowest_yearly_earnings and highest_yearly_earnings.
Created revenue_per_subscriber:
Earnings divided by subscriber count.
Computed derived insights like revenue efficiency and growth rates.
3. Exploratory Data Analysis (EDA)
Correlation Analysis:
Heatmap showing relationships among numerical features.
Scatter Plot Analysis:
Subscribers vs Average Yearly Earnings (log-log scale)
Urban Population vs Uploads
Unemployment Rate vs Recent Subscriber Growth
Population vs Subscribers
Education Enrollment vs Average Yearly Earnings
Ranking Analyses:
Top 10 YouTubers by subscriber growth
Top countries by YouTuber count
Top YouTubers by revenue per subscriber
Top countries by monetization rates
Category-wise Analysis:
Content category vs Average Earnings
Views distribution across different categories

📊 Visualizations:
📈 Correlation Heatmaps

📊 Bar Charts (e.g., Top YouTuber Countries, Content Categories)

🧮 Scatter Plots with regression lines

📉 Growth Trend Lines (Subscribers over years)

🌍 Geographical Maps (YouTuber distribution by country)

🍰 Pie Charts (Views distribution across categories)

🧩 Treemaps (Category distribution)

📌 Key Insights & Findings:
Subscribers and views have a strong positive correlation.
Content in the "Shows" and "Entertainment" categories tends to earn higher than others.
Revenue per subscriber significantly varies based on the country.
Upload frequency has a weaker impact compared to content quality in determining success.
Macroeconomic indicators (unemployment, education rates) show limited influence on YouTube success metrics.
Some outliers achieve exceptional results despite fewer uploads, highlighting the importance of content strategy.

🎯 Recommendations for Aspiring YouTubers:
Focus on high-earning content categories like "Shows," "Entertainment," and "Comedy."
Prioritize content quality over sheer upload quantity.
Consistent short-term activity boosts visibility and earnings.
Explore underserved markets with higher revenue per user.
Study outliers to understand unique growth strategies and replicate success patterns.

🚀 Future Improvements:
Develop a predictive model to forecast subscriber growth based on country, category, and uploads.
Build an interactive dashboard using Plotly Dash or Power BI.
Integrate sentiment analysis of video comments to understand engagement levels.
Perform time series analysis for predicting trends.

📩 Contact
For questions, feedback, or collaboration opportunities, feel free to reach out!

✨ Thank you for visiting this project! ✨

