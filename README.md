# ****Analyzing the Ted talk data****

> **Founded in 1984 by Richard Saulman as a non profit organization that aimed at bringing experts from the fields of Technology, Entertainment and Design together, TED Conferences have gone on to become the Mecca of ideas from virtually all walks of life. As of 2015, TED and its sister TEDx chapters have published more than 2000 talks for free consumption by the masses and its speaker list boasts of the likes of Al Gore, Jimmy Wales, Shahrukh Khan and Bill Gates.**
> 
> 
> **Ted, which operates under the slogan 'Ideas worth spreading' has managed to achieve an incredible feat of bringing world renowned experts from various walks of life and study and giving them a platform to distill years of their work and research into talks of 18 minutes in length. What's even more incredible is that their invaluable insights is available on the Internet for free.**


# Description

> As a data analyst, I performed a thorough analysis of the Google Play Store data. This included cleaning the data by removing null values and duplicates by utilizing the Pandas, NumPy and Matplotlib, Seaborn, Scipy libraries to create comprehensive data visualizations. Through this process, I was able to uncover valuable insights and provide meaningful answers to challenging problem statements. My technical expertise and attention to detail allowed me to effectively analyze and present the data, providing valuable contributions to the project.


# **Interesting questions that we can ask**

- Which are the top 15 most viewed talks of all time?
- Find out the distribution of views and comments
- Views and comments on the 10 most commented TED Talks
- Which talks tend to attract the largest amount of discussion?
- Who are the top speakers?
- Tags that have most views, tags that have duration of talk more than average
- No of languages vs rating.
- Occupation vs Views
- Name vs Related Talks
- Month of publication vs views


# Important Insights

- **Ken Robinson's talk on Do Schools Kill Creativity? is the most popular TED Talk of all time with 47.2 million views.**
- **Also coincidentally, it is also one of the first talks to ever be uploaded on the TED Site (the main dataset is sorted by published date).**
- **Robinson's talk is closely followed by Amy Cuddy's talk on Your Body Language May Shape Who You Are. There are only 2 talks that have surpassed the 40 million mark and 4 talks that have crossed the 30 million mark.**
- **The average number of views on TED Talks in 1.6 million. and the median number of views is 1.12 million. This suggests a very high average level of popularity of TED Talks. We also notice that the majority of talks have views less than 4 million. We will consider this as the cutoff point when constructing box plots in the later sections.**
- **On average, there are 191.5 comments on every TED Talk. Assuming the comments are constructive criticism, we can conclude that the TED Online Community is highly involved in discussions revolving TED Talks.**
- **There is a huge standard deviation associated with the comments. In fact, it is even larger than the mean suggesting that the measures may be sensitive to outliers. We shall plot this to check the nature of the distribution.**
- **The minimum number of comments on a talk is 2 and the maximum is 6404. The range is 6402.. The minimum number, though, may be as a result of the talk being posted extremely recently.**
- **Hans Rosling, the Swiss Health Professor is clearly the most popular TED Speaker, with more than 9 appearances on the TED Forum. Juan Enriquez comes a close second with 7 appearances. Rives and Marco Tempest have graced the TED platform 6 times.**
- **Writers are the most popular with more than 45 speakers identifying themselves as the aforementioned.**
- **Artists and Designers come a distant second with around 35 speakers in each category.**
