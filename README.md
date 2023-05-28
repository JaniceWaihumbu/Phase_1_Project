# Phase_1_Project
# Overview
The film industry has been one of the fastest growing markets in recent years. According to research by the "[Global News Wire]""(https://www.globenewswire.com/news-release/2022/03/08/2398616/0/en/Film-And-Video-Global-Market-Report-2022.html)", the global movies and entertainment market size was valued at USD 94.451 Billion in 2022. Movies are a significant part of culture and a major source of entertainment for a large part of the global population and with regards to revenue, the market is predicted to grow to an estimated USD 169.62 Billion by 2030 with a compound annual growth rate of roughly 7.21% between 2023 and 2030.This makes it a valuable investment to consider.

# Business Understanding
The growth in popularity of original video content has inspired Microsoft to create a new movie studio to take advantage of this opportunity. However, this may pose a challenge as it is a fairly new industry for them and they lack the necessary insights on what movies to create.

Since Microsoft has no prior experience in creating movies, this exploratory data analysis seeks to find what types of films are currently topping the box office. The findings from this analysis, will be used to come up with recommendations on the best course of action for Microsoft to take when creating their own movies.

The major questions that this analysis is looking to answer are:
>How does average rating vary with movie genres? With respect to that, what genre should Microsoft venture in?
>How does number of votes vary with movie genre? In which case, which movies have a larger audience base?
>Should Microsoft venture in domestic or foreign production, or both?

# Data Description
The dataset used for this anaysis contains information about movie sites. The data has four files bom_movies, tmdb_movies, and IMDB with the following set of information about the movies:


Genres

Domestic and Foreign Gross Income

Average Movie Ratings

Number of Votes

Movie Runtime

Popularity

Movie titles

# Data understanding
In this process, a thorough analysis was conducted to understand the structure and content of the data. The goal was to identify any missing values, or duplicates that need to be addressed. By handling these issues appropriately, the data could be prepared for further analysis and utilized effectively.


# Data Analysis
After cleaning the data, the next step in the process was to study the refined dataset and derive meaningful insights and recommendations from it. This involved conducting data analysis using various techniques, including data visualization.

## Data Visualization
Data visualization played a crucial role in gaining a deeper understanding of the dataset. Bar graphs were utilized to visualize categorical variables, providing a clear representation of the distribution and frequency of different categories. This allowed for easy comparison and identification of any patterns or trends within the data.

https://github.com/JaniceWaihumbu/Phase_1_Project/blob/master/output%201.png
The bar plot above indicates that there are not significant differences in average ratings across various movie genres. However, it is worth noting that movies that fall under the combination of Adventure, Animation, and Comedy have the highest average rating. As does the Documentary category. On the other hand, the genres of Horror and Thriller, as well as History and a combination of Comedy and Drama, tend to have lower average ratings.

https://github.com/JaniceWaihumbu/Phase_1_Project/blob/master/output%202.png
The bar plot above indicates that the movie genre with the highest number of votes is the Drama genre, indicating that it has a larger audience base.

https://github.com/JaniceWaihumbu/Phase_1_Project/blob/master/output%203.png
The data points are quite spread out in the scatter plot above. Which indicates there is no trend to the data and thus, there is no correlation between Runtime in Minutes and Average Rating.

https://github.com/JaniceWaihumbu/Phase_1_Project/blob/master/output%204.png
"Toy Story 3" exhibits the lowest foreign gross income but the highest domestic income. Conversely, "Shrek Forever After" showcases the lowest domestic income but the highest foreign income. Therefore, when Microsoft explores movie creation opportunities, it becomes crucial to prioritize whether they aim to cater to the foreign or domestic market. By doing so, they can determine the type of movie that would potentially yield the highest income.

# Conclusions
>From the data analysis above it is clear that movies that fall under the combination of Adventure, Animation, and Comedy have the highest average rating. As does the Documentary category. On the other hand, the genres of Horror and Thriller, as well as History and a combination of Comedy and Drama, tend to have lower average ratings.

>It is also clear that the movie genre with the highest number of votes is the Drama genre, suggesting that the genre has a larger audience base and thus greater potential reach.

>We also see that "Toy Story 3" exhibits the lowest foreign gross income but the highest domestic income. Conversely, "Shrek Forever After" showcases the lowest domestic income but the highest foreign income. This indicates that "Shrek Forever After" had a stronger international appeal that "Toy Story 3".

# Recommendations
>Considering the data, it is evident that adventure, animation, and comedy genres receive higher average ratings compared to other genres. This indicates they have a better reception among viewers.Therefore, Microsoft should consider focusing on creating videos within these genres. As for the runtime, as it appears to have less significance in determining the quality and appeal of movies within the genres, Microsoft has the flexibility of choosing a low or high runtime for their videos without worrying about their potential success.

>In addition to adventure, animation, and comedy genres, Microsoft should also consider creating videos within the Drama genre. The genre's high number of votes suggests its significant popularity and engagement level, indicating a large potential audience reach. Thus, including Drama genre videos in their content lineup can help Microsoft tap into a wide and enthusiastic viewer base.

>The data above also illustrates the performance of movies in both domestic and foreign markets. The data clearly indicates that movies tend to have varying levels of success in these two markets. However venturing into both markets will allow Microsoft to increase their revenue. Therefore, it is crucial for Microsoft to distinguish their strategies for international distribution and marketing. This will enhance the chances of their movies resonating with audiences and achieving favorable results in both domestic and foreign markets.


