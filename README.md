# virulahd-lgmt.github.io
Math-215-Portfolio
# Project Ideas

## Stock market volatility through interest rate & inflation changes

This project would have me exploring the volatilty of different sectors of the market when affected by interest rate and inflation.
I would download a API that tracks the market along with datasets from FRED.
The goal would be to find the sectors of the market which are most vurnable to changes in the US economy.

## Finding what makes the a song popular

In this project I would look at the genre of house music and find the most popular songs, from there I would use the spotify dataset from class to find the variables that these songs possess.

## Trend in movies over time

In this project I would see which genre of movie is the most popular at different times, and how the trend has changed.
I would use an API to track popular movie genres and then overlay that with a time line.

# Reflection

This was my first time building a website it was very straight forward, the video was very helpful. This was a very cool project and I will be building another one to connect it to my linkedin. I would say the ionterface is confusing without the video and it would have taken my much longer to do with out it. I really like both of my ideas from class but it took me a while to find the last one. I wanted to do something that isnt related to the other two, but still somehting I would find fun and engaging. The resource can in the form of my friend that brought up a movie we had just watched and it sparked the idea in my head. It took me roughly 40 minutes to do this project, but I feel like I learned a valuable and applicable skill.

## Week 10 Update

As of now the first idea relating to the stock market seems the most interesting to me, and more than likely the path I will follow. I have been talking with Nathan Nemali on working on this together, but as of now nothing is solidified. I looked into a yahoo finance api to use for this project and it is a viable option i didnt see anything wrong with it, another option is the api I used for this weeks mini project. The API is from alpha vantage and I really enjoyed working with it. The only draw back is that the data is subject to be up to 15 minutes behind real market data. The three big questions I have are which stocks are most affected by interest rate and inflation rate changes, which sector is the least volatile and which stocks have seen the greatest YTD change since the current presiden took office.


<iframe
  src="Alaska_destinations_delays.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

## Week 11 Update


I found three datasets that I could possibly use I got two of them from the federal reserve of St Louis and the other from Yahoo finance.I want to use these in order to analyze market volitilty based on both of these variables. The two that come from FRED are inflation and interest rate data from the USA, it was very easy to find this as I have worked with FRED throughout my entire college career. The data is very easy to sort and is very trust worthy. The Yahoo dataset took me more time to figure out, I couldn't find a download page for any of the stocks or sectors. After a while I did a web search to figure it out. From this I found out I can download a yahoo library to python which allows me to pull real time data and historic datasets. An important consideration is that the datasets can be in different frequencies, so standarizing them before beginning the project is very important or the results will not be coherent. One major strength is that all three datasets are very trustworthy and accurate, and most important unbiased which will make my results more accurate. Currently I am learning how to use the yfinance library in python and trying to find a time of high volatility for inflation and interest rate to see how markets react at the extremes. I think the biggest challange will be dealing with different ways to write the date or values, and possible dealing with missing values to be able to standarize the data.

## Week 12 Update

<iframe
  src="Sector_Correlation_Matrix.html"
  width="100%"
  height="600"
  frameborder="0">
</iframe>

The graph above is a correlation heat map of S&P 500 sectors and inflation and interest rate. This helps with my understanding of which sectors are the most volitile in relation to interest rate and inflation. From here I'll be able to take a deeper dive into these sectors and find why they are more sentative to the volitility of the rates. I also spent sometime finding the the historic times that rates changed, then I found the same time realting to the market to find price changes.
