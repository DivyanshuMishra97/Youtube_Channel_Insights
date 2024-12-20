# 📊 YouTube Channel Performance Dashboard

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
  - **Actionable Insights**: Identified least-performing videos and those with no tags.  

### Step 4: Dashboard Optimization  
- Enhanced the visual appeal by incorporating intuitive charts and a clear layout.  
- Included the YouTube logo and profile picture for branding.  

### Step 5: Insights and Recommendations  
- Derived actionable insights from the dashboard to guide content strategy.  
- Documented observations and recommendations for improving channel performance.

---

## Insights

### [1] Channel Overview  
- **Total Videos**: 86  
- **Total Views**: 5,85,587  
- **Total Likes**: 28,680  
- **Total Dislikes**: 302  
- **Total Comments**: 1,798  

- **Insight**: A balanced mix of regular videos and shorts contributes to total engagement.  

---

### [2] Shorts vs. Regular Videos Performance  

- **Views**: Regular videos outperform shorts with an average view count of 3,000+.  
- **Likes**: Regular videos receive higher average likes compared to shorts.  
- **Engagement**: Shorts have a higher average engagement rate despite lower views.  

- **Insight**: Shorts provide better engagement rates but require improved reach strategies.  

---

### [3] Correlation Between Views and Video Length  

- **Observation**: A logarithmic relationship exists between the length of regular videos and views. Videos between 8–10 minutes achieve optimal view counts.  

- **Insight**: Content length should be optimized to align with audience preferences.  

---

### [4] Immediate Action Required  

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
![image](https://github.com/user-attachments/assets/e4384804-bda2-4d98-9a46-c28b22ae3032)

### Full Dashboard 


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
- **GitHub**: [Divyanshu Mishra](https://github.com/DivyanshuMishra97)  

---

Feel free to adjust this as per your needs! Replace `upload_link_here` with actual links to your images or screenshots.
