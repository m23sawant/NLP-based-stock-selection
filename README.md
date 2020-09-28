# NLP-based-stock-selection
NLP Based Stock Selection Model based on the paper [Lazy Prices](https://www.nber.org/papers/w25084). 

Using the complete history of regular quarterly and annual filings by U.S. corporations from 1995-2014, the authors show that when firms make an active change in their reporting practices, this conveys an important signal about future firm operations. Changes to the language and construction of financial reports also have strong implications for firms’ future returns: a portfolio that shorts “changers” and buys “non-changers” earns up to 188 basis points in monthly alphas (over 22% per year) in the future. Changes in language referring to the executive (CEO and CFO) team, regarding litigation, or in the risk factor section of the documents are especially informative for future returns. They show that changes to the 10-Ks predict future earnings, profitability, future news announcements, and even future firm-level bankruptcies; meanwhile firms that do not make changes experience positive abnormal returns. 


In this project, I have used corporate 10K filings and to apply my knowledge in NLP, from cleaning data and text processing, to feature extraction and modeling. I've used use bag-of-words and TF-IDF to generate company-specific sentiments. With these sentiments, I come up with trading strategies, and measure the performance of the strategies.

