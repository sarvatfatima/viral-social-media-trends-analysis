# Social Media Trends Analysis

## Objective

Analyzing [dataset](https://www.kaggle.com/datasets/atharvasoundankar/viral-social-media-trends-and-engagement-analysis) of viral social media trends to understand engagement patterns across platforms, content types, and regions.

## Dataset

The dataset contains metrics for social media posts, including:

-   **`Post_ID`**: Unique identifier for each post
    
-   **`Platform`**: Social media platform (TikTok, Instagram, YouTube, Twitter)
    
-   **`Hashtag`**: Trending hashtag used in the post
    
-   **`Content_Type`**: Type of content (Video, Shorts, Post, Live Stream)
    
-   **`Region`**: Geographical origin of the post (e.g., UK, India, Brazil)
    
-   **`Views`**: Total views
    
-   **`Likes`**: Number of likes
    
-   **`Shares`**: Number of shares
    
-   **`Engagement_Level`**: High/Medium/Low classification

## Libraries Used

-   **Pandas**: Data manipulation and cleaning
    
-   **Matplotlib/Seaborn**: Visualizations (bar charts, heatmaps)
    
-   **SQLite**: Database management and SQL queries
    
-   **Scikit-learn**: Machine learning (engagement prediction)

## Methodology

1.  **Data Cleaning**:
    
    -   Handled missing values in  `Engagement_Level`  and  `Views`
        
    -   Encoded categorical features (`Platform`,  `Content_Type`)
        
2.  **SQL Analysis**:
    
     Using simple and Basic Queries to make the project simpler and understanding.
    
3.  **Exploratory Analysis**:
    
    -   Visualized platform distribution, regional engagement, and content performance
        
4.  **Machine Learning**:
    
    -   Trained a  `RandomForestClassifier`  to predict engagement levels

## Key Findings

1.  **Platform Dominance**: TikTok and YouTube had the highest number of viral posts.
    
2.  **Content Types**: Videos and Shorts received 2x more engagement than text-based posts.
    
3.  **Regional Trends**: Posts from India and USA had the highest average shares.
    
4.  **Hashtags**: `#Fitness`  and `#Education`  were the most frequently used viral hashtags.
## Conclusion

Content type (**videos/shorts**) and platform choice (**TikTok/Instagram**) significantly impact engagement. Regional trends highlight opportunities for localized marketing strategies.

## Visualizations

-   **Bar Charts**: Platform distribution, top hashtags
    
-   **Heatmaps**: Correlation between views, likes, and shares
    
-   **Pie Charts**: Engagement levels by region


## References
Viral_Social_Media_Trends Kaggle Dataset 
    
