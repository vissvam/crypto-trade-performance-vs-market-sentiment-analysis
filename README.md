📊 trader-sentiment-analysis
Data analysis project exploring the relationship between crypto trading performance and Bitcoin market sentiment (Fear & Greed Index) using Python and exploratory data analysis (EDA).

📁 Datasets Used
Historical Crypto Data
Contains daily price, volume, and trade-related information.
Key columns: Coin, Date, Open, Close, High, Low, Volume

Fear & Greed Index
Provides daily market sentiment scores and classifications (Fear, Greed, etc.).
Columns: date, value, classification

🎯 Objective
Understand how different market sentiments (Fear, Greed, Extreme Fear, Extreme Greed) impact:

Price trends over time

Trading volume patterns

Relationship between sentiment scores and price movement

🧹 Data Preprocessing
Removed invalid or irrelevant rows (e.g., coins with @ in their name)

Converted timestamps/dates into proper datetime format

Merged both datasets on date to align price & sentiment data

📊 Key Insights
Most Frequent Sentiment: Extreme Greed

Strongest Price Growth Periods: Observed during Greed phases

Volume Trends: Noticeable spikes in trading volume during high Greed

Sentiment-Price Relationship: Clear short-term correlation patterns

🛠️ Tools Used
Python — Data processing & visualization

Pandas — Data cleaning & merging

Matplotlib & Seaborn — Plotting and trend analysis

📂 Output
Final merged dataset: merged_data.csv

Contains all historical data combined with sentiment scores for deeper analysis.
