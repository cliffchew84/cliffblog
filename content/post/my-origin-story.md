## Before
When I was a student, I hated how statistics was taught to me in such an abstract way, and I never felt I had a flair for programming. So it always feels like some poetic karma that my daily work involves writing scripts to analyse huge corpus of data. All this changed after I experienced my first end-to-end empirical research, which can be seen as the prequel to my data science journey. In modern terms, this is my origin story.

## My first data experience
In 2010, I had to finish an economics research thesis to complete my master’s in Economics at NUS. I had two conditions in mind: 
I wanted to do empirical research because I felt it would have a direct impact on a real world issue as compared to a theoretical paper
I wanted a topic on urban economics / issues as that was my area of interest

## Hunting for a suitable topic
My topic hunt was longer than expected, and this was solved only when I reverse engineered my solution by looking at what data was available. This was where I found a large, structured set of Singapore’s historical private resale housing transactions that was available online. Next, I was looking for an economic event to study my data with, and I identified the North-East Line train construction that took place from 1995 to 2003. The idea was that after accounting for all other variables, I will be able to isolate the impact of this train line construction on neighbouring housing prices. This became my [thesis](https://scholarbank.nus.edu.sg/handle/10635/30739).

## Data processing
I focused only on private resale condominiums and apartments because I had no public housing data and felt that landed property was difficult to handle. The data set had transacted home addresses, prices, size, storey, transaction month and zoning area, but no proximity to amenities data. So for a month, I painstakingly mapped out each transacted home’s straight line distance to neighbouring amenities like malls, schools and parks on Google Maps. It was a slow, tedious and inaccurate process, but that was the only way I knew to capture this data.

> **What I would do now:** I know now that I can calculate the straight line distances between the transacted houses and neighbouring amenities using the latitude and longitude data from the government supported OneMap API service, or even get the different distance types (walking, car, public transport) from it and iterate my models with those data. Better data quality with less chances of errors and done with less effort. And I take pride in knowing that a few years of data science work taught me how some technical tooling can potentially improve the methodologies in applied econometrics research. **#lifelonglearning**

## The statistical software
Up to this point, I had only used Eviews for my econometrics assignments at NUS. However, iterating my models with Eviews’ user-interface was so painful that I decided to self-learn STATA and redo my modeling with STATA scripts called .do files. With STATA, I saw the benefits of automating repetitive tasks through scripts. When written well, these scripts also become documentation for your work, which allows easier reproduction during further iterations.

> Since using Eviews and STATA, I have gone on to learn other statistical software, including SAS, SPSS, Python and R. The positive externalities of learning STATA was that it gave me the can-do attitude to pick up new skills, and this is something I believe is an important meta-skill for our current Information Economy.

## The models
Many of the academic journals that I read wrote about spatial autocorrelation when modeling for housing prices. This is because prices of homes in close proximity are not statistically independent, and this will make traditional regression analysis on them statistically invalid. And while I had hopes of using some of these advanced geospatial models, I eventually stuck to a simpler maximum likelihood model because that was what I could run in STATA.

Being a data analyst has since removed me from such econometric approaches. I have stopped hunting for natural phenomena and their data, or check whether the data I have fit certain modeling assumptions. Since then, I began splitting data into training and testing data sets and set up A/B testing experiments. I have also learned to extract large volumes of data from systems and manage analytics workflows that need frequent updating. And while both disciplines have a strong foundation in mathematics and data modeling, their differing approaches and philosophy to tackling their unique data problems has enriched my perspectives about the use of data in our societies today.

## Final reflections
My thesis took one year to reach this conclusion: 

> The announcement to construct the North-East Line had a larger positive impact on neighbouring housing prices than when the line became operational, suggesting that home buyers were overly bullish about the positive impact of the train line right after its announcement. In addition, housing prices during the line’s construction dropped to below pre-announcement levels, suggesting that disturbances from such a huge infrastructure construction had a negative impact on the housing prices.

The experience of getting an inference based on data and models inspired me so much that I almost went into academia. These days, I do different types of analyses in data science, but these are built from my foundation in empirical economic research. In both economics and data science, I see great possibilities of using data for the betterment of our societies, and it is this view that makes me so intrigued about the use of data in general. 

Lastly, I hope that by sharing my personal stories, I can make my sharings more relatable and to contribute to the overall intellectual community of our civilization.

> This piece is also in memory of A/P Anthony Chin, my thesis supervisor who passed away from cancer in 2014.