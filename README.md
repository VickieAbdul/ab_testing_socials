#  A/B Testing for Social Media Ads
 
This project takes a closer look at an anonymous company's social media ad campaign through the lens of A/B Testing. Our aim? To pinpoint the ad campaign that really hits the mark by evaluating metrics like Click-Through Rate (CTR), Conversion Rate (CR), and Cost Per Conversion (CPCo).

By applying real-world A/B testing methods, we can figure out whether the differences we see in campaign performance are statistically significant.

## Dataset Information
The dataset contains 1143 observations and 11 features, including:

- Ad & Campaign Info: ad_id, xyz_campaign_id, fb_campaign_id

- User Demographics: age, gender, interest

- Ad Performance Metrics: Impressions, Clicks, Spent, Total conversion, Approved conversion

## Key Metrics Calculated:
- Click-Through Rate (CTR) = (Clicks / Impressions) * 100

- Conversion Rate (CR) = (Approved Conversions / Clicks) * 100

- Cost Per Conversion (CPCo) = Spent / Approved Conversions

## A/B Testing Approach
1. Exploratory Data Analysis (EDA): Clean and summarize the dataset.
2. Compare Campaigns: Aggregate key metrics for each campaign.
3. Statistical Testing: Use the Chi-Square Test to check if the difference in conversions is statistically significant.
4. Data Visualization: Plot Conversion Rate across campaigns.
5. Business Insights & Recommendations: Identify the best-performing campaign and suggest improvements.

## Key Findings
- Campaigns were tested to see if they significantly differed in conversion rates.
- A Chi-Square Test was used to determine if performance differences were due to chance or a real effect.
- Based on our analysis, we provide data-driven recommendations on ad spending and strategy.

## Visualizations
- Bar Chart: Conversion Rate comparison across campaigns.
- Performance Metrics Table: CTR, CR, and CPCo for each campaign.

## Technologies Used
- Python (Pandas, NumPy, SciPy, Matplotlib, Seaborn)
- Statistical Testing (Chi-Square Test for significance)

## How to use this project. Type the following on your Git bash
1. Clone this repository
   git clone https://github.com/VickieAbdul/ab_testing_socials.git
2. Install the required libraries
   pip install pandas numpy scipy matplotlib seaborn
3. Run the Jupyter Notebook or Python script to see the analysis.
   python ab_test.py

## Next Steps
- You can extend the A/B test to analyze age groups & gender impact.
- Also, use other statistical tests like T-Test for deeper insights.
- Finally, apply machine learning to predict which users are likely to convert.

## About Me
I’m a Junior Data Scientist passionate about A/B testing, experimentation, NLP, and data-driven decision-making. This project is part of my portfolio to showcase my ability to analyze business problems and derive insights using statistical methods.

I’m always excited to share knowledge and learn from others. Feel free to connect with me on LinkedIn (https://www.linkedin.com/in/victoriajabdul/) or check out my GitHub for more projects!
