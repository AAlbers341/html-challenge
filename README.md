# html-challenge

# Mars News HTML Scrape
Utilizing Splinter to scrape https://static.bc-edx.com/data/web/mars_news/index.html. Extracted article Titles and Preview into a dictionary

## Sources
All code utilized was referenced through course material i.e. examples and exercises

# Mars Temperature Analysis
Utilizing Splinter to scrape the 'Mars Temperature Data' table to conduct EDA with Pandas. 

## Primilmary EDA
How many months exist on Mars?
12 
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
1867
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
month
1    -77.160920
2    -79.932584
3    -83.307292
4    -82.747423
5    -79.308725
6    -75.299320
7    -72.281690
8    -68.382979
9    -69.171642
10   -71.982143
11   -71.985507
12   -74.451807
Name: min_temp, dtype: float64

Plot the results as a bar chart.
![image](https://github.com/AAlbers341/html-challenge/assets/149892097/0c98328f-b89a-407d-8a25-8360c3809b31)


Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
month
1     862.488506
2     889.455056
3     877.322917
4     806.329897
5     748.557047
6     745.054422
7     795.105634
8     873.829787
9     913.305970
10    887.312500
11    857.014493
12    842.156627
Name: pressure, dtype: float64

Plot the results as a bar chart.
![image](https://github.com/AAlbers341/html-challenge/assets/149892097/76f4b18c-8821-4e58-89ef-6d0b6bc97e9b)



About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.
![image](https://github.com/AAlbers341/html-challenge/assets/149892097/ebdc2e40-504f-4a1c-9bab-9b03d31c11c7)
