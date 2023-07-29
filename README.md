## Analyzing Various Streaming Platforms

### Authors
Nicholas Hong: nhong1@uw.edu
Doryi Wang: mwang311@uw.edu
Nikki Yuan: yuan0709@uw.edu
Rebecca Wang: lufanw@uw.edu

### Date

Winter 2023
### Abstract

This project analyzes content offerings from Netflix, Hulu, Disney and Prime Video based on unique titles, age ratings, movie reviews, and release years. By doing so, customers can choose which service is best for them and platforms can play to their competitive advantages. 

### Keywords

Streaming platforms, Content diversity, User satisfaction, Competitive advantage


## Proposal:


### Introduction
With the rise of streaming platforms, the entertainment and media access has undergone tremendous changes. Streaming platforms have completely changed how we access and enjoy content, allowing us to quickly see many movies, TV programs, documentaries, etc. With the intensification of competition, various streaming platforms aim to differentiate themselves via unique offerings.

This study aims to analyze exclusivity, movie reviews, age ratings and move release years from major streaming platforms (Netflix, Hulu, Disney, and Prime Video) to understand their relative advantages and disadvantages. We will be analyzing 5 major questions:
1. **How does the content library of each streaming platform compare in terms of type diversity and original works?**
This question aims to understand how each platform plans its content and scope to cater to different users’ interests by comparing the quantity of unique titles per streaming service. 
2. **How do the average movie ratings differ across the various platforms?**
User experience and streaming quality are critical aspects of streaming platforms. By understanding the level of user satisfaction, it is possible to determine which platform might offer more favorable titles.
3. **What age does each platform cater to based on their average age rating?**
Streaming platforms typically differentiate themselves through unique titles targeted towards a specific demographic. This is important for users deciding which platform is most appropriate for their age group.
4. **How do the movie release years compare across platforms?**
While some users may prefer to watch the latest releases, others might want to watch classic titles from previous years as well.

### Related Work

<<<<<<< HEAD
The streaming platform has recently become an important component of popular entertainment, and people tend to use streaming media because of its convenience and wide range of content. Its commerciality and portability have gradually become a recent prevailing research topic. This project aims to analyze the difference in streaming platform information and its impact on user usage.

“Data Analysis of Streaming Services & Movie Rating” holds a similar purpose and analyzes which platform had higher rated movies and compared the year of movies, and their goal is that “to determine which streaming service has a movie collection with the highest average IMDb rating and which years had the highest rated movies”(Loesberg). The result shows that until the article's publication date of April 19, 2021, Disney + has higher average IMDB rated movies while Amazon prime video streaming has a higher percentage of movies.
=======
> Where did you find the data? Please include a link to the data source

We found the data from Kaggle. The link is https://www.kaggle.com/datasets/ruchi798/movies-on-netflix-prime-video-hulu-and-disney.

> Who collected the data?  

Ruchi Bhaia collected the data. She is a product marketing manager, data scientist at HP Pittsburgh.

> How was the data collected or generated?  

The data is scraped from different streaming platforms.

> Why was the data collected?  

The data is collected to show on which platform people can find their chosen movies. It is also collected to explore the relationship between movies of different age groups and platforms that include these movies.

>How many observations (rows) are in your data?  

Our data includes 9515 observations。

> How many features (columns) are in the data?  

Our data includes 11 attributes

> What, if any, ethical questions or questions of power do you need to consider when working with this data?  

The question of power relates to attributes of the dataset. First, the target age for a particular movie observation involves attitudes and power. The power source is hidden since we do not know who determines the target age for a particular movie. However, it does imply the power to make different age groups see the "right" movie. Second, the data uses Rotten Tomatoes as a platform that gives marks to different movies. It implicitly treats Rotton Tomatoes as source of power.

> What are possible limitations or problems with this data?   (at least 200 words)

The limitations of the data set are as follows: first, there are a lot of character type variables such as titles of movies, target age groups, and marks given by Rotten Tomatoes. It makes this dataset not very suitable for quantitative analysis. We need to apply some transformation and aggregation of data before analysis. For example, we can convert the string "94/100" into numeric 94 in the Rotten Tomatoes attribute; second, there are four dummy variables indicating the platform of a particular movie. It is okay if we focus on the analysis of specific movies, but it will require reshaping data if we need to look at the overall characteristics of each platform; third, the data set includes too few characteristics of platforms. It does not show the price range of streaming services. It does not have the user experience of different platforms. Moreover, I think the data set lacks categories of movies such as comedy, thriller, and so on. The categories of movies allow us to analyze which category of movies are popular on each platform. If we do not know the most popular movie category in each platform, we cannot compare strengths and weaknesses in terms of content between different platforms.

4. Implications
>>>>>>> 5f4cdc1ed24a4cd16a186bdf9e99987f4e4b407c

In the research “Factors Affecting Online Streaming Subscriptions” the researchers have used the regression model to analyze the co-relationship between different factors and the user choice of the streaming platform, and the study indicates that the "social trend (negative), cost and customer service factors were statistically significant"(Lee 2).

The article “Statistical Study of View Preferences for Online Videos With Cross-Platform Information” has a similar reaching topic about the streaming platform, and its analysis of the dataset from Douban which "includes feedbacks (e.g., movie ratings, comments, and reviews) from all users of different online video systems, and movie metadata (e.g., release date, actors, and directors)" (Zhou 1512). The author has statistically analyzed the data and concluded that there is a co-relationship between those factors and the view counts, and indicates that those studies could positively benefit the streaming platform that provides those videos.  


### The Dataset
We found the data from Kaggle [here.](https://www.kaggle.com/datasets/ruchi798/movies-on-netflix-prime-video-hulu-and-disney) The data was collected by Ruchi Bhaia who is a product marketing manager and data scientist at HP Pittsburgh. It was generated by directly scraping the information off of the different streaming platforms. The data was collected to show on which platform people can find their chosen movies. It is also collected to explore the relationship between movies of different age groups and platforms that include these movies. The data includes 9515 observations and 11 attributes. 

The question of power relates to attributes of the dataset. First, the target age for a particular movie observation involves attitudes and power. The power source is hidden since we do not know who determines the target age for a particular movie. However, it does imply the power to make different age groups see the "right" movie. Second, the data uses Rotten Tomatoes as a platform that gives marks to different movies. It implicitly treats Rotton Tomatoes as a source of power.

The limitations of the data set are as follows:
1. There are a lot of character type variables such as titles of movies, target age groups, and marks given by Rotten Tomatoes. It makes this dataset not very suitable for quantitative analysis. We need to apply some transformation and aggregation of data before analysis. For example, we can convert the string "94/100" into numeric 94 in the Rotten Tomatoes attribute.
2. There are four dummy variables indicating the platform of a particular movie. It is okay if we focus on the analysis of specific movies, but it will require reshaping data if we need to look at the overall characteristics of each platform.
3. The data set includes too few characteristics of platforms. It does not show the price range of streaming services. It does not have the user experience of different platforms. Moreover, I think the data set lacks categories of movies such as comedy, thriller, and so on. The categories of movies allow us to analyze which category of movies are popular on each platform. If we do not know the most popular movie category in each platform, we cannot compare strengths and weaknesses in terms of content between different platforms.


### Implications

Analyzing the differentiating factors among Hulu, Netflix, Disney and Amazon Prime Video would help these companies find out their market advantages and disadvantages and allow them to use these factors for their benefit. While maximizing diversity is important, it’s even more critical to offer movie titles that are attractive to their users. For example, one streaming platform might have the most exclusive titles. However, if all of these titles have poor user ratings, viewers will be quite dissatisfied and might change to a competing platform. Another instance would be if a platform has historically catered towards the youth, expanding to more mature titles might not be what the audience is looking for. 

Users will also benefit from this research. Being that all of these platforms are paid services, customers will want to ensure that their money is being spent to their best benefit. Depending on the specific customer, they might prioritize age ratings, reviews, exclusivity or release years. Through this data analysis, they can choose which platform is best suited for them. 

### Challenges and Limitations

A possible challenge could be a lack of significant differentiation across the platforms. Disney, Hulu, Amazon Prime Video and Netflix are all highly established names in the industry and have been growing their catalogs for years. All motivated with gaining a competitive advantage, their collections could be relatively similar by all offering a vast range of attractive titles. From a personal observation, it’s clear that there isn’t a clear dominating streaming service culturally.

Another limitation would be the inability to consider other streaming platforms that could be equally competitive, such as YouTube Plus or HBO Max. This could have an effect on the implications previously mentioned as it will be difficult for users of the data to gain a full perspective of the various offerings in the market. For example, finding that one of the platforms from our analysis has the newest movies doesn’t necessarily mean that this platform has the newest movies within the entire market. 

### Works Cited

Lee, C. Christopher; Nagpal, Pankaj; Ruane, Sinead G.; and Lim, Hyoun Sook (2018) "Factors Affecting Online Streaming Subscriptions," Communications of the IIMA: Vol. 16: Iss. 1, Article 2. DOI: https://doi.org/10.58729/1941-6687.1394

Loesberg, Sophie. “Data Analysis of Streaming Services & Movie Ratings.” Medium, 20 Apr. 2021, sophloes.medium.com/data-analysis-of-streaming-services-movie-ratings-5d8b7b1375c3

Y. Zhou, X. Gu, D. Wu, M. Chen, T. H. Chan and S. W. Ho, "Statistical Study of View Preferences for Online Videos With Cross-Platform Information," in IEEE Transactions on Multimedia, vol. 20, no. 6, pp. 1512-1524, June 2018, doi: 10.1109/TMM.2017.2769807. ieeexplore.ieee.org/abstract/document/8094954/citations?tabFilter=papers#citations

