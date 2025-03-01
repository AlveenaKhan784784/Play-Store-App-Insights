# Play-Store-App-Insights

**DataSet**: [Here](https://www.kaggle.com/datasets/lava18/google-play-store-apps)

#### Step 1: Data Preprocessing
1.Handling Missing Values
- Identify missing values in each column.
- If an app has a missing value in Type, Category, or Android Version, we search and replace it based on real-world data or similar apps.

2.Handling Duplicates
- Some apps may have duplicate entries due to data collection errors.
- We remove duplicates while keeping the first occurrence.

3.Handling Outliers
- Ratings range from 1 to 5, but some may appear as outliers.
- We analyze whether outliers should be removed based on their impact on analysis.

#### Step 2: Exploratory Data Analysis (EDA)
1.Rating Distribution
- Most apps have high ratings (4.0+), but some have lower ratings.
- Understanding rating trends helps identify user preferences.

2.Free vs Paid Apps
- Do paid apps have higher ratings than free apps?
- Comparing ratings between free and paid apps can provide insights into app quality.

3.Most Popular App Categories
- Checking the most common categories helps understand market trends.

4.Top 10 Rated Apps
- Identifying the highest-rated apps gives insights into what users prefer.

#### Final Thoughts
- Data preprocessing ensures accuracy in analysis.
- EDA helps uncover patterns and trends in app ratings and popularity.
