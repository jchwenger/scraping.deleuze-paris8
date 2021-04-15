# Scraping Deleuze

Extracting all course texts from [univ-paris8.fr/deleuze/](http://www2.univ-paris8.fr/deleuze/).

Using Python 3, [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) and [ftfy](https://ftfy.readthedocs.io/en/latest/).

```bash
$ python scrape.py
```

It will produce the folder `deleuze-txt`, containing all the scraped courses as
plain text files.

