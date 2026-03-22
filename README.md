# Instagram-User-Engagement-and-Retention-Analysis
Instagram User Behavior & Engagement Quality Analysis

Kanche Susmitha | Data Analyst
Tools: Python · Pandas · NumPy · Matplotlib · Seaborn · Tableau

🎯 Business Problem
Instagram leadership wanted to shift focus from raw time spent to meaningful engagement. Raw activity metrics could not explain why users spending more time on the platform were still churning. The goal was to analyse user behaviour across 1.5M users to improve engagement quality and reduce dormancy risk.

📐 Custom Metrics Designed
MetricDefinition
1. Meaningful Engagement (ME)Weighted score of likes, comments, DMs and posts — weighted by effort per action
2. Attention (A)Total time spent across Feed, Reels, Explore and Messages
3. Engagement Quality Efficiency (EQE)ME ÷ A — meaningful engagement per unit of time spent

👥 User Segments Identified
Segment Profile
1. High EQELess time, more meaningful actions
2. Low EQEMore time, passive scrolling behaviour
3. High Dormancy RiskEfficient but login less often
4. Low Dormancy RiskFrequent logins but passive usage

📊 Key Findings

1. Users with fewer sessions had significantly higher EQE — quality of engagement matters more than frequency
2. High Reels time consistently drove Low EQE — confirming doom scrolling reduces meaningful engagement
3. Stress was the strongest lifestyle signal negatively correlated with EQE (~0.4 correlation)


📈 Tableau Dashboard
🔗 https://public.tableau.com/app/profile/kanche.susmitha4144/viz/NL_Instagram_17702281275140/InstagramUserEngagement

📁 Dataset
Source: Instagram Usage Lifestyle Dataset — 1.5M users across demographics, platform behaviour and lifestyle metrics
