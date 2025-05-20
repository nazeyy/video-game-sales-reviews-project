# video-game-sales-reviews-project  
DSA210 Project Fall 2025 – Sabancı University  

### **Video Game Sales & Player Reviews: What Makes a Good Game?**

## Introduction  
While it may not be obvious to everyone, the video game industry is a multi-billion-dollar market that continues to grow each year. As technology advances, the gaming industry evolves alongside it. By analyzing not only sales data but also player reviews, this project aims to understand the factors that define a “good” game from the gamers’ perspective. Exploring why certain titles perform better than others—and examining elements such as pricing, genre, marketing, and more—provides valuable insights not only for developers but also for players.

## Motivation  
For my DSA210 project, I’ve chosen a topic that intrigues me: video games. Through this analysis, we can uncover the correlation between raw sales figures and player experience. The findings will inform developers, publishers, and marketers about which factors resonate most with audiences, assist in crafting better games and marketing strategies, and guide players toward titles they’re likely to enjoy.

## Data Sources  
- **Game Sales**: Primarily from [VGChartz](https://www.vgchartz.com/) and other open datasets tracking game sales across various platforms.  
- **Game Reviews**: From sources such as [OpenCritic](https://opencritic.com/), Reddit discussions, and [Metacritic](https://www.metacritic.com/).  
- **Platform Metadata**: Potentially from Steam, Epic Games, and Origin, including information on genres, publishers, and user tags.  

## Project Goal

The main goal of this project is to identify the factors that affect or contribute to the success and player insight of video games. By using the data found from sales, reviews, and metadata it is aimed to:

- Find the key factors that relate with video games that have been successful in sales. 
- Understand the correlation in between the player reviews and performance of the sales.
- Get insights to help game developers and others enhance their games and game sale strategies.

## Data Sources and Preprocessing

The project uses content and datasets that are available to and made by others on the internet:

### 1. Game Sales Data:
- **Sources:** VGChartz, and Kaggle datasets.
- **Content:** Global and regional sales of games from multiple different platforms.

### 2. Game Review Data:
- **Sources:** OpenCritic, Metacritic, and Reddit.
- **Content:** Player reviews, and critic scores.

### 3. Platform Metadata:
- **Sources:** Steam, Epic Games Store, Origin.
- **Content:** Game genre, publisher information, release dates, and etc.

**Data Preprocessing Steps:**
- Data Cleaning (remove duplicates, and fill missing values).
- Data Integration (scale, and encode).
- Data Transformation (join, and merge).
- Data Reduction (sample, and reduce dimensionality).

## Data Analysis Methods

The data will be analyzed in three steps:

### Exploratory Data Analysis (EDA)
- Analyze and visualize sales, reviews, and etc.
- Visualize correlation through matrices and heatmaps.
- Identifying the trends and correlations.

### Correlation Analysis
- Analyze the correlaation bond in between reviews and sales.
- Determine factors that contribute to the success through the correlations.

### Visualization Techniques
- Use histograms and boxplots (for the distribution of sales, reviews).
- Use line charts and bar graphs (for how the trends change over time).
- Use heatmaps (for testing the strength of correlation).

## Hypothesis Testing

The project aims to test the following hypotheses:

1. **Hypothesis 1:** Games with higher user reviews have better sale numbers.
   - **Null hypothesis:** No significant difference in sale ratess based on the player reviews.
   - **Alternative hypothesis:** Games with more positive reviews have higher sale rates.

2. **Hypothesis 2:** Specific game genres preform better.
   - **Null hypothesis:** No significant difference in performance among genres.
   - **Alternative hypothesis:** Certain game genres have better performance rates than others.

## Machine Learning Techniques

These machine learning models will used to help predict game sales and determine the important factors:

- **Regression Models:** Linear Regression, Decision Trees, Random Forest.
- **Sentiment Analysis Models:** NLP techniques.
- **Evaluation Metrics:** Root Mean Squared Error, Coefficient of Determination, Mean Absolute Error.

## Limitations and Future Work

### Limitations:
- **Subjectivity in Data Reviews:** Player reviews may be biased or inaccurate since it depends on users.
- **Incomplete Metadata:** Limited data available of marketing, and developer information.
- **Data Granularity:** Lack of detailed temporal data might limit insights.

### Future Work:
- **Extended Data Collection:** Add additional data sources from other platforms such as YouTube, Twitter, etc for better and more detailed analysis.
- **Real-Time Predictive Modeling:** Observe trends and predict sales based on pre-release reviews and feedback.
- **Advanced Methods:** Use ther advanced techniques to get more sophisticated and detailed data analysis.

###  Disclosure
Data from internet and AI was used to  only help debug errors, and contribute in machine learning steps. There is no direct use of content other than the data that is cited.


