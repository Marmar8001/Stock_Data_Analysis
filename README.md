# Stock_Data_Analysis

For this mini project, I will focus on equities data from the Frankfurt Stock Exhange (FSE), which is available for free. I'll try and analyze the stock prices of a company called Carl Zeiss Meditec, which manufactures tools for eye examinations, as well as medical lasers for laser eye surgery: https://www.zeiss.com/meditec/int/home.html. The company is listed under the stock ticker AFX_X.


While there is a dedicated Python package for connecting to the Quandl API, I would prefer that I use the requests package, which can be easily downloaded using pip or conda. You can find the documentation for the package here: http://docs.python-requests.org/en/master/

Finally, apart from the requests package, I did not use any third party Python packages, such as pandas, and instead focus on what's available in the Python like lists and dictionaries.

These are your tasks for this mini project:

* Collect data from the Franfurt Stock Exchange, for the ticker AFX_X, for the whole year 2017 (keep in mind that the date format is YYYY-MM-DD).
* Convert the returned JSON object into a Python dictionary.
Calculate what the highest and lowest opening prices were for the stock in this period.
What was the largest change in any one day (based on High and Low price)?
What was the largest change between any two days (based on Closing Price)?
What was the average daily trading volume during this year?
(Optional) What was the median trading volume during this year. (Note: you may need to implement your own function for calculating the median.)
