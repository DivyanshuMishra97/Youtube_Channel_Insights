# 📊 YouTube Channel Performance Dashboard

## Dashboard

Check out the dashboard here: [Dashboard Link](https://public.tableau.com/app/profile/divyanshu.mishra6295/viz/YoutubeChannelsInsights/ChannelsPerformance?publish=yes)

## Problem Statement

This dashboard provides valuable insights into the performance of a YouTube channel by analyzing data across multiple dimensions. It identifies trends in views, likes, comments, and engagement for both regular videos and shorts. By comparing performance metrics, it helps content creators optimize their strategy to increase overall engagement and audience retention.

Through visualizations, the dashboard highlights key metrics like total videos, views, likes, and dislikes while offering actionable insights, such as identifying underperforming videos, correlation between video length and views, and videos requiring immediate attention. The analysis was conducted by preprocessing data from a CSV file and leveraging ETL techniques.

---

## Steps Followed

### Step 1: Data Collection and Import  
- Imported the channel's performance data from a CSV file using Python.  
- Ensured the dataset included key metrics such as video type, views, likes, dislikes, comments, and video length.

### Step 2: Data Preprocessing (ETL)  
- **Extract**: Loaded the raw data into Python using Pandas.  
- **Transform**:  
  - Cleaned and validated the data (removed duplicates, handled missing values).  
  - Categorized video types into "Regular Videos" and "Shorts."  
  - Created additional calculated metrics (e.g., engagement rate).  
- **Load**: Exported the processed data for visualization in Tableau Public.  

### Step 3: Visualization Design  
- Designed the dashboard in Tableau Public to highlight key performance indicators (KPIs) and trends:  
  - **KPIs**: Total videos, views, likes, dislikes, and comments.  
  - **Comparisons**: Performance of shorts vs. regular videos across views, likes, comments, and engagement rate.  
  - **Correlation Analysis**: Logarithmic chart displaying the relationship between video length and views for regular videos.  
  - **Tooltips**: Enhanced user experience with interactive tooltips that display detailed insights about video type, title, length, and engagement.  

### Step 4: Dashboard Optimization  
- Enhanced the visual appeal by incorporating intuitive charts and a clear layout.  
- Included the YouTube logo and profile picture for branding.  

### Step 5: Insights and Recommendations  
- Derived actionable insights from the dashboard to guide content strategy.  
- Documented observations and recommendations for improving channel performance.

---

## Insights

### [1] Channel Overview  
- **Total Videos**: 86 (Regular: 36 | Shorts: 50)   
- **Total Views**: 5,85,587 (Regular: 3,69,333 | Shorts: 2,16,254)  
- **Total Likes**: 28,680 (Regular: 16877 | Shorts: 11803)  
- **Total Dislikes**: 302 (Regular: 131 | Shorts: 171)  
- **Total Comments**: 1,798 (Regular: 1350 | Shorts: 448)  

- **Insight**: A balanced mix of regular videos and shorts contributes to total engagement.  

**Tooltip Screenshot**:  
![image](https://github.com/user-attachments/assets/bba1bbff-8a8e-42f7-862d-2818c88563ce)

---

### [2] Shorts vs. Regular Videos Performance  

- **Views**: Regular videos outperform shorts with an average view count of 3,000+.  
- **Likes**: Regular videos receive higher average likes compared to shorts.  
- **Engagement**: Shorts have a higher average engagement rate despite lower views.  

**Tooltips**: Added insights into each bar for detailed view type and metrics.  
![image](https://github.com/user-attachments/assets/c988394e-1866-4d76-8b1a-c659ee74cfc1)
![image](https://github.com/user-attachments/assets/5db271c1-450b-4c19-846a-eb5981726774)

- **Insight**: Shorts provide better engagement rates but require improved reach strategies.  

---

### [3] Correlation Between Views and Video Length  

- **Observation**: A logarithmic relationship exists between the length of regular videos and views. Videos between 8–10 minutes achieve optimal view counts.  

**Tooltip Screenshot**:  
![image](https://github.com/user-attachments/assets/3d99f913-9777-4556-b997-db8defafb56b)

- **Insight**: Content length should be optimized to align with audience preferences.  

---

### [4] Popularity vs Engagement  

- **Popularity**: A video's popularity is measured by the **average views/likes/comments per video**, calculated by dividing the total likes by the number of videos. This reflects how well the videos perform overall.  

- **Engagement**: Engagement measures **likes/comments per view**, computed by dividing total likes or comments by total views. This shows how likely viewers are to interact with a video after watching it.  

**Tooltip Screenshot**:  
![image](https://github.com/user-attachments/assets/20d7019c-f47e-432e-9eeb-6ba666c967c6)

- **In short**: Popularity indicates overall likability, while engagement reflects viewer interaction per view.  

---

### [5] Immediate Action Required  

- **Videos with No Tags**:  
  - Certain videos lack tags, limiting discoverability.  

- **Least Performing Videos**:  
  - Regular Video: "I published 10 videos..." (257 views).  
  - Shorts: "Difference Data Analyst..." (182 views).  

- **Insight**: Adding relevant tags and improving metadata can boost visibility for underperforming videos.  

---

## Dashboard Snapshot  

### Channel Summary  
![image](https://github.com/user-attachments/assets/6e7d2811-c8e0-4be1-87dd-2ef7302bce39)

### Performance of Shorts vs. Regular Videos  
![image](https://github.com/user-attachments/assets/ea1715e3-a445-456d-a207-62ee520e0191)

### Correlation Analysis  
![image](https://github.com/user-attachments/assets/39ea4da9-9fe5-4cfa-b323-ca2c282466f4)

### Full Dashboard 
![1](https://github.com/user-attachments/assets/d79a9d26-23ff-4623-9d20-c3f9c3c1bb50)
![2](https://github.com/user-attachments/assets/25cf7b43-f360-4979-8f93-845127c5272c)

---

## Recommendations  

1. **Optimize Video Length**: Focus on creating regular videos between 8–10 minutes for maximum views.  
2. **Leverage Shorts**: Increase the number of shorts while improving their metadata to enhance engagement.  
3. **Improve Tagging**: Add relevant tags to all videos to improve discoverability.  
4. **Enhance Low-Performing Videos**: Identify and update thumbnails, titles, and descriptions for underperforming content.  
5. **Engagement Strategy**: Focus on encouraging more comments and likes to increase overall engagement rates.  

---

## Tools and Technology  

- **ETL**: Python (Pandas) for data preprocessing.  
- **Visualization**: Tableau Public for dashboard creation.  
- **Data Source**: CSV file containing YouTube channel metrics.  

---

## Contact  

- **Author**: Divyanshu Mishra  
- **Email**: [divyanshu.mishra@utdallas.edu](mailto:divyanshu.mishra@utdallas.edu)  

---
