# Final Project Proposal

Please complete your proposal following the outline below.

## Project title

Give your project a concise, interesting title that summarizes the entirety of your project. (Your title can change on subsequent deliverables.)

### Authors

Names of your team members and contact information (email addresses).
### Date

Winter 2023
## Abstract

No more than three sentences that summarize your project. Focus on the very most important aspects. For example: (1) "Our main question is .... This question is important because .... To address the question, we will ...." (2) "We are concerned with ..., because .... To address this concern, we plan to ...." (3) "Consider that .... This is important because .... Accordingly, we plan to ...."

## Keywords

3-5 keywords that summarize your project.
(e.g., "Keywords: human physiology; bicycle exercise; Gen Z; times-series data")

## Proposal

1. Introduction  

> Briefly introduce your project.  Include 3-5 research questions. What motivates the questions? Why are they important? (at least 200 words)

2. Related Work  

> Describe your topic and related work in this space. You must include 3 citations to related work (URLs to similar work, high quality articles from the popular press, research papers, etc. ) Please use a standard citation style of your choice. (at least 200 words)

3. The Dataset

> Where did you find the data? Please include a link to the data source

I find the data from Kaggle. The link is https://www.kaggle.com/datasets/ruchi798/movies-on-netflix-prime-video-hulu-and-disney.

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

The question of power relates to attributes of the dataset. First, the target age for a particular movie observation involves attitudes and power. The power source is hidden since we do not know who determines the target age for a particular movie. However, it does implies power to make different age groups see the "right" movie. Second, the data uses Rotten Tomatoes as a platform that gives marks to different movies. It implicitly treats Rotton Tomatoes as source of power.

> What are possible limitations or problems with this data?   (at least 200 words)

The limitations of the data set are as follows: first, there are a lot of character type variables such as titles of movies, target age groups, and marks given by Rotten Tomatoes. It makes this dataset not very suitable for quantitative analysis. We need to apply some transformation and aggregation of data before analysis. For example, we can convert the string "94/100" into numeric 94 in the Rotten Tomatoes attribute; second, there are four dummy variables indicating the platform of a particular movie. It is okay if we focus on the analysis of specific movies, but it will require reshaping data if we need to look at the overall characteristics of each platform; third, the data set includes too few characteristics of platforms. It does not show the price range of streaming services. It does not have the user experience of different platforms. Moreover, I think the data set lacks categories of movies such as comedy, thriller, and so on. The categories of movies allow us to analyze which category of movies are popular on each platform. If we do not know the most popular movie category in each platform, we cannot compare strengths and weaknesses in terms of content between different platforms.

4. Implications

> Assuming you answer your research questions, briefly describe the expected or possible implications for technologists, designers, and policymakers. (at least 150 words)

5. Limitations & Challenges
>What challenges or limitations might you need to address with your project idea more broadly? Briefly discuss. (at least 150 words)

Acknowledgements
> Is there anyone you would like to thank? A librarian who helped you with your research? A Teaching Assistant? A friend who helped you find your data? Say thank you in this section.
