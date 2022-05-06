## Please read the report.html file for full report and code.

# API and web scraper data correlation testing in Python (Jupyter notebooks)
A Python analysis of changes in the price of Bitcoin cryptocurrency and indices depicting the UK state of economy over the period of ten financial years (2010-2019).

## Context
The creation of cryptocurrencies has changed how the world operates entirely. As a method of payment, a tool for investment or a mean for international transactions, cryptocurrencies now serve a fair number of purposes. Despite a few unsuccessful or at least not much popular attempts to create a cryptocurrency, Bitcoin is the first cryptocurrency to draw serious attention by market traders (Reif, 2021). Becoming a major tool for investment and trade online, Bitcoin has shown the strength to dictate many financial decisions from companies and from individuals alike (Graham, 2017). With larger and larger sums invested in cryptocurrencies by companies, it is to be expected that, with time, economies will be likely to influence how much cryptocurrencies cost on the global exchange. In an academic paper (Al.Qudah & Aloulou, 2020), researchers have studied how Bitcoin would serve as a tool for financial hedging in GCC countries. Data of inflation rate, foreign trade and GDP of those countries has been analysed alongside how Bitcoin has performed in the past. Being the 5th largest economy in the world for 2020 (Silver, 2021), it presents an interesting topic of research to test whether similar tendencies exist between Bitcoin and the country’s macroeconomic indicators. Following the concept of Al-Qudah and Aloulou (2020), this study will attempt in a similar fashion to analyse macroeconomic indicators of the UK economy parallel historical data on Bitcoin.

## Methodology
The methodology used in this paper consists of using the programming language Python in an environment suitable for making API calls, run code and print results in separate sections. This study will carry out empirical analysis (“What is empirical analysis?”, 2022) on available data online by calculating correlations between data series and make deductions based on data visualisation results. It will also execute hypothesis testing by estimating a number of values which provide insight on whether relationships between data series are significant or not. The values for hypothesis testing are Pearson's r, Spearman's rho and Kendall's tau (Stojiljkovic, n.d.).

### Tools
#### The software used in this paper to retrieve and analyse the data to test the hypotheses will be:

Python – programming language.

Jupyter notebooks – The Jupyter Notebook is the original web application for creating and sharing computational documents. It offers a simple, streamlined, document-centric experience.

Pip - pip is the package installer for Python. You can use pip to install packages from the Python Package Index and other indexes.

Anaconda - Individual Edition is an open source, flexible solution that provides the utilities to build, distribute, install, update, and manage software in a cross-platform manner. Conda makes it easy to manage multiple data environments that can be maintained and run separately without interference from each other.

#### Python Libraries The Python libraries used for the analysis of the data in this paper are the following:

Pandas - https://pandas.pydata.org/ Open-source data analysis and manipulation tool.

NumPy - https://numpy.org/ Scientific calculations library.

Urllib3 - https://urllib3.readthedocs.io/en/stable/ A powerful, user-friendly HTTP client.

Matplotlib - https://matplotlib.org/ Visualization library.

Json - https://docs.python.org/3/library/json.html Exposes an API familiar to users of the standard library marshal and pickle modules.

Requests - https://pypi.org/project/requests/ HTTP Library.

Beautiful Soup – https://www.crummy.com/software/BeautifulSoup/bs4/doc/ Library for pulling data out of HTML and XML files

seaborn - https://seaborn.pydata.org/ Statistical data visualization

scipy.stats - https://docs.scipy.org/doc/scipy/reference/stats.html Statistical functions

os - https://docs.python.org/3/library/os.html Provides a way of using operating system functionality.
