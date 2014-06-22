---
title       : Shiny Stocks US 
subtitle    : A sample app to demo the power of Shiny
author      : Ken Kopparapu
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
---

## Shiny Stocks US


This application shows the details of the listed US stocks using Shiny web application frame work and R

This is a simple application that loads information about all listed stocks on NYSE, NASDAQ, AMEX.

You can view all the stocks by Exchange and industry 

or 

if you know the ticker, you can get the details of the stock by entering the ticker

The underlying is downloaded from nasdaq website. For example the stocks listed on AMEX are downloaded using the following url 

http://www.nasdaq.com/screening/companies-by-industry.aspx?exchange=AMEX&render=download"

Any stocks with a market cap of 0 are removed from the dataset.

--- .class #id 

## Shiny stocks trivia



[1] "Number of stock listings by Exchange"
<!-- html table generated in R 3.1.0 by xtable 1.7-3 package -->
<!-- Sun Jun 22 16:46:35 2014 -->
<TABLE border=1>
<TR> <TH>  </TH> <TH> Exch </TH> <TH> Count </TH>  </TR>
  <TR> <TD align="right"> 1 </TD> <TD> AMEX </TD> <TD align="right"> 375 </TD> </TR>
  <TR> <TD align="right"> 2 </TD> <TD> NASDAQ </TD> <TD align="right"> 2743 </TD> </TR>
  <TR> <TD align="right"> 3 </TD> <TD> NYSE </TD> <TD align="right"> 2564 </TD> </TR>
   </TABLE>

<br>
<br>



```
## [1] "These listed stocks are divided in to  13 sectors"
```


--- .class #id 

## Number of industries 




```
## [1] "Did you know the US listed stocks are broken in to  137 industries ?"
```
<br>
<br>
Shiny Stocks makes it easy to see all the stocks for each industry by exchange.
<br>
<br>
This is very useful when you are researching about a stock and others in the group


--- .class #id 

## Shiny Stocks - next steps 

<br>
<br>

This applications will be enhanced to show the historical prices, dividend information, technical indicators, news
 
