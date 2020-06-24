# Olympics Data Visualization Summary
A Data Visualization through the use of Jupyter Notebook, Pandas, Python, Matplotlib and Seaborn and Tableau.

Reference for the Dataset: https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results/kernels?sortBy=hotness&group=everyone&pageSize=20&datasetId=31029&tagIds=13201

## Olympics Country and Sports
I visualized here in my notebook on how many athletes per country participated in the Olympics from 1896 to 2016. Here is an example.
![](/Pictures/athletes_countries.JPG)

Take note: The average participants of each country is 1179 (I used the .mean() of python to get the average)

I then clustered each country with the average participants in the Olympics and here is the result:

**Cluster 1**
![](/Pictures/cluster1.JPG)


**Cluster 2**
![](/Pictures/cluster2.JPG)

After I clustered each country I made the top 10 countries who has many athletes participated and the least athletes participated.

**Countries with the most athletes**
![](/Pictures/top10.JPG)

**Countries with the least athletes**
![](/Pictures/least10.JPG)

I then summarized all the Sports events of the Olympics from 1896-2016 both Winter and Summer Events.
![](/Pictures/sports.JPG)

I then Categorized the most played sports in the Olympics and the least played sports.

**Top 10 Sports**

![](/Pictures/top10sports.JPG)


**Least 10 Sports**

![](/Pictures/lesat10sports.JPG)

## Olympic Medal per country and top 10 athletes
In this notebook I dropped all the athletes who dont have any medal in the dataset and analyzed it each, by knowing the top 10 athletes who has won many medals, the number of medals of each country and gender comparison.

By the way I saved the new dataset into a new CSV file called Olympics only those who have medals.

I started of categorizing the data with the most medals won by each country and the breakdown of it.

**Total Medals won by each countries [PERCENTAGE]**
![](/Pictures/countrymedalpercentage.JPG)

**Total Medals won by each countries**
![](/Pictures/totalmedalcountries.JPG)

**Total Medals won by each countries breakdown**
![](/Pictures/medalcountries.JPG)

Next is the Top 10 Athletes who won the most medals and its breakdown.

**Top 10 Athletes**
![](/Pictures/top10athletesmedal.JPG)

**Top 10 Athletes Medal Breakdown**
![](/Pictures/athletebreakdown.JPG)

Lastly the Gender Comparison Through The Years.
![](/Pictures/gendercomparison.JPG)

## Medal With Age
In this notebook I only did the analysis of the ages of the athletes who won with a medal.
![](/Pictures/age.JPG)

As you can see the average age of an athlete in the olympics is 26 years old, and if you hover the dataframe the youngest age who entered in the olympics is a gymnast athlete with an age of 10 years old, while the oldest is a 73 years old athlete who participated in the Arts Competition.
