# Web Scraping haritidis.gr

Web scraping the haritidis.gr website to create a dataset of 8.600 pieces of jewelry.

### haritidis.gr

<a href='https://www.haritidis.gr/'>haritidis.gr</a> is a website that features an extensive list of pieces of jewelry..<br>
For each piece of jewelry this website features some data about different aspects and attributes such as price, gemstones, material and others.

### Tools

To extract the data I used the Python programming language as well as some of its modules.
* For requests I used the <a href='https://requests.readthedocs.io/en/master/'>Requests</a> module.
* For the web scraping I used the <a href='https://www.crummy.com/software/BeautifulSoup/bs4/doc/'>Beautiful Soup</a> module
* For cleaning and transforming the data I used the <a href='https://pandas.pydata.org/'>Pandas</a> module.
* For translating the greek words to english, for international use, I used the <a href='https://pypi.org/project/googletrans/'>googletrans</a> module.
* To save the raw data I used a json file. To save the cleaner data I used a csv file.

### Data
Each piece of jewelery has a name, a price and a brand. The names are not unique, but each piece of jewelry listed has its own page in the website.<br>
Aside from the index, there is no clearly primary key to this dataset.

The dataset can be found here: https://www.kaggle.com/victormegir/jewelry-from-haritidisgr
