# stock-analysis

# Overview
Our client Steve is a recent graduate of a finance program and is looking to us to build a stock analysis program in VBA to help him analyse a group of green-energy companies stock prices.  Using VBA, we will build a program to automate this for him.

## Results
Using the tools we have built, we have created analyses for two years, 2017 and 2018.  At first glance, we can see 2017 was a much better year for green stocks than 2018 was:

![This is an image](https://github.com/Brents-Github/stock-analysis/blob/main/Resources/2017%20SS.png)
![This is an image](https://github.com/Brents-Github/stock-analysis/blob/main/Resources/2018%20SS.png)

As we can see, all stocks except for "TERP" had positive returns, with one stock "DQ" having a return of almost 200%!  However, when we look at the 2018 results, only two stocks had a positive return.  It would be worthwhile to look further into what happened in 2018.  Were there regulatory changes?  Perhaps commodities like fossil fuels were relatively cheap that year?  Based on these results, Steve should recommend purchasing "ENPH" and "RUN", as they both had positive results in both 2017 and 2018.

## Summary
1.  When coding, often our first attempt at creating the code may not be the most efficient.  Once our code is working, we should step back and take a look at what we have done, and see if there is a more efficient way to write our code, and improve the performance of our output by using less memory to perform the same tasks.  It can also help with the composition and improve the readability of your code for future users. Some disadvantages to refactoring code would be the length of time it takes to do, and (like what happened to me) you could end up breaking the code and spending even more time trying to sort out where you went wrong.

2.  The code we refactored will now be able to handle much more data, and through the use of arrays, be easily modified to accept more than 12 output arrays.  The analysis should also process quicker than before.
