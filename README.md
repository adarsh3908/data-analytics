# Data Analytics Portfolio

All of my Data Analytics projects are here!

## YouTube Data Collection and Analysis

This project analyzes YouTube trending videos data to extract insights and patterns.

### Files
- `YouTube Data Collection and Analysis.ipynb` - Main Jupyter notebook containing the analysis
- `trending_videos.csv` - Dataset containing YouTube trending videos data
- `.gitignore` - Git ignore file for Python/Jupyter projects

### Getting Started
1. Clone this repository
2. Install required dependencies (pandas, numpy, matplotlib, seaborn, etc.)
3. Open the Jupyter notebook and run the cells

## 🔹 Detailed Documentation

### **1. Introduction**
The project focuses on collecting and analyzing YouTube data using the YouTube Data API v3. The purpose is to understand content trends, audience engagement, and channel growth strategies.

### **2. Dataset**
- **Source**: YouTube API v3  
- **Data Collected**:  
  - Channel details (ID, title, subscriber count).  
  - Video details (title, views, likes, comments, publish date).  
  - Playlists.  
  - Comment threads.  

### **3. Methods**
1. **Data Collection**  
   - Used `google-api-python-client` to interact with YouTube API.  
   - Extracted JSON responses and stored in structured format.  

2. **Data Preprocessing**  
   - Converted JSON to Pandas DataFrame.  
   - Cleaned missing values.  
   - Standardized date/time fields.  

3. **Analysis**  
   - Descriptive statistics (views, likes, comments).  
   - Publishing frequency vs engagement.  
   - Top performing videos.  

4. **Visualization**  
   - Bar charts for top videos.  
   - Line charts for growth trends.  
   - Correlation between likes, views, and comments.  

### **4. Results**
- Found that **video consistency** strongly correlates with audience growth.  
- **Engagement (likes/comments)** varies widely across categories.  
- Channels posting frequently tend to grow faster in subscribers.  

### **5. Future Work**
- Implement real-time dashboards.  
- Add Natural Language Processing (NLP) for comment sentiment analysis.  
- Extend analysis to multiple channels for comparative studies.

### Requirements
- Python 3.x
- Jupyter Notebook
- Required libraries: pandas, numpy, matplotlib, seaborn, google-api-python-client (and others as specified in the notebook)
