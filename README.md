# Crypto_Arbitrage

This application will identify and analyze potential arbitrage opportunities in the crypto markets. Specifically looking at trades occurring on the Coinbase and Bitstamp exchanges during the first quarter of 2018.

Null data has been dropped, values stored as strings (i.e. dollar amounts stored with USD currency indicator) have been converted to numeric float datatypes, and duplicated rows have been dropped from the dataframe.

The analysis to understand aribtrage opportunities was performed across the sample dates - one in January, one in February, and one in March of 2018. The analysis consists of determining the spread in bitcoin prices between the two exchanges at the exact same point in time. This is calculated and then conditionally filtered where the profit margin is greater than 1% (the cost of buy and sell trade commissions). Profit opportunities for each of the three days are calculated followed by a detailed analysis highlighting the potential arbitrage opportunities that existed across the Bitstamp and Coinbase exchanges in early 2018.

The following image shows the cumulative profits one could have gained on January 28th had they executed near instanteous buy/sell orders for one Bitcoin on the two exchanges.

![Image of a line graph showing January 28th, 2018 Bitcoin arbitrage opportunty throughout the day - totalling $350k](https://github.com/rjohnson617/Crypto_Arbitrage/blob/main/Resources/jan_28_profits.png?raw=true)

---

## Technologies

### Python, Pandas, Pathlib, JupyterLab, Matplotlib

The application is written in Python through a JupyterLab notebook and utilizes the Pandas, Pathlib, and maplotlib libraries to bring in Bitcoin data, scrub and analyze, and then visulaize for the final analysis

---

## Contributors

Code produced by Ryan Johnson

---

## License

[MIT]

Copyright (c) [2022] [Ryan Johnson]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.