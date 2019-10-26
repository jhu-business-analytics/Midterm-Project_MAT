# Explaining the Trash Crisis in Baltimore
By: Mofe Barrow, Angie Lao, Tiffany Thomas

Does Baltimore have a trash crisis? After conducting an in-depth analysis, we found certain hotspots where the city can improve on trash disposal locations and services. Through addressing this issue with solutions proposed below, millions of taxpayer dollars can be saved each year.  

# Why is this challenge a problem?

President Trump began attacking Representative Elijah Cummings in a series of tweets in July 2019, which led to an attack on the “rat-infested” Baltimore City. We were hence inspired to dig deeper and see if Trump’s claims were substantiated by any data. In an article by the [Baltimore Sun in June 2019](https://www.baltimoresun.com/maryland/baltimore-city/bs-md-ci-illegal-dumping-20190620-story.html), an estimated 10,000 tons of trash are illegally dumped in Baltimore every year. In FY 2018, the Department of Public Works released a [report](https://publicworks.baltimorecity.gov/sites/default/files/Illegal%20Dumping%20Remediation%20Report%20FY2018.pdf) stating their government expenditures were at $22,666,770 on right-of-way cleaning services, which includes street and alley cleaning, mechanical street sweeping, marine operations, graffiti removal, and cleaning of business districts. From a public health perspective, it is crucial to prioritize the environmental health and safety of this city because illegal dumping and other forms of environmental pollution can lead to contaminated water, health hazards, increased spread of disease, and unattractive areas that deter investment. This problem is most relevant to Baltimore residents, as it affects Baltimore’s public image (as seen by the political ramifications of Trump’s tweets), but it also affects residential/commercial owners, the public sector, tourists, and residents living near dumping zones or alleys. By identifying citations with the highest frequency and specific Baltimore regions with higher prevalence of environmental issues--such as illegal trash dumping and inability to dispose trash correctly--then we can implement better plans to help those highly affected regions, save taxpayer dollars, and preserve the beauty and safety of a cleaner Baltimore City. 

# Our Solution

Our business question is analyzing whether or not Baltimore has a trash problem. Based on our data analysis, the highest number of citations occurred under ‘high grass and weeds’ and ‘trash accumulation’ across the entire Baltimore city from 2003-2019. To identify the geographic locations, or "hot spots", of specific city council districts with the highest citations, Districts 12 and 13 had the highest number of citations; District 12 had the highest of “dumping under 25lbs of waste on public property”, whereas District 13 had the highest in the categories of “high grass and weeds” and “trash accumulation”. 
After identifying ‘high grass and weeds’ and ‘trash accumulation’ as the most common citations in Baltimore city, we chose to focus on the “trash accumulation” category to answer our business question because it is the most relevant. After performing linear regression to analyze the trends of trash accumulation from 2003-2019, there was an increase in the citation frequency with an R^2 value of .6003, meaning 60.03% of our data was explained by the linear regression.
With this data, we reached our business answer: while Baltimore has issues with trash accumulation and disposal in certain “hot spots” throughout the city, we still need to acquire more environmental data (inaccessible to us at this time) from other major cities to measure the true severity on a city-wide basis. Additionally, we identified certain districts with the highest number of citations, but we must consider that different districts have varying populations, leading to different amounts of trash. In addition, there may be trash that is unaccounted for simply because citations were not given out. The overall impact is that trash accumulation is increasing in Baltimore City, and immediate action must be taken. 

# Future Suggestions

The call to action is that Baltimore needs to increase accessibility of proper trash disposal locations/services through policy change and social initiatives. Through policy changes that enable more frequent weekly trash pick-ups or add additional trash disposal locations in high risk trash neighborhoods, residents will be more likely to dispose trash properly and reduce the detrimental impacts of trash accumulation. In addition, Baltimore can increase awareness of proper trash disposal behaviors, and can work with the Bloomberg School of Public Health to initiate a city-wide public health campaigns around trash accessibility. These awareness campaigns will target residents' behaviors and enable them to dispose trash properly.
The people of Baltimore will be have more pride in their city knowing that it will no longer be called a “trashy” or “disgusting...mess”, as Trump had previously suggested. Residents will see their health improve with less harmful trash in their surroundings. By removing Baltimore’s “trashy” label, this city may see an increase in tourism and outside commerce which can lead to increased revenue and economic opportunities. 

# Data Analysis

![Frequency of the revelant citation categories](https://i.imgur.com/pjtalbf.png)
By using COUNTIF and COUNT functions, we were able to identify the most frequent environemntal citations that pertained to our business question. Overall, 'high grass and weeds' and 'trash accumulation' had the most number of citations, at 25,467 and 19,753 citations, respectively.

![Number of citations per city council district](https://i.imgur.com/iypLoDz.png)
Using the pivot table, we took a more in depth analysis of geographic hot spots with the most number of citations. Based on the analysis, Districts 12 and 13 received the highest number of overall citations from 2003-2019 at around 9000 per district. By cross referencing this to a map, we found that both districts are very close in proximity, making up the Dowtown and East Baltimore region. 

![Comparison of the relevant citation numbers in Districts 12 and 13](https://i.imgur.com/CXHgGEa.png)
Using the pivot table again to take a deeper dive into which citations were most common in our district "hot spots", District 12 (blue) had the most citations under 'dumping under 25lbs of waste on public property'. District 13 (orange) had the most citations under 'high grass and weeds' and 'trash accumulation'. As shown in the graph, trash and dumping are still very prevalent in these hot spot regions.

![Trash accumulation citations per year linear regression](https://i.imgur.com/hneMhA2.png)
Using a simple linear regression, we found a trend line that best fit our data points. With an R^2 value of .6003, 60.03% of our data can be explained by this linear trend. The slope of 299 implies that every year, there is an expected increase of around 300 additional citations. 

![Trash accumulation citations per year exponential regression](https://i.imgur.com/CsKMsyE.png)
Lastly, we found that an exponential linear regression was a better fit for the data points, resulting in an R^2 value of .9284, meaning 92.8% of our data can be explained by this line. 

