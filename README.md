#### Unsupervised Learning Case Study

Webscraping Bigfoot sighting description and conducting topic modelling using tfidf and non-negative matrix factorization (NMF)

### Bigfoot Sightings

A data set of bigfoot sighting reports was collected from the [Geographic Database of Bigfoot / Sasquatch Sightings & Reports](http://www.bfro.net/gdb/); you can see an example report [here](http://www.bfro.net/GDB/show_report.asp?id=13038). The data, downloadable as a zipped `json` file [here](https://s3.amazonaws.com/ufodatafordarren/bigfoot_data.json.zip), contains the URL, raw HTML for that URL, and the time it was scraped for each report in the database along with the remnants of a database id.

### The Data
here are 4800+ sighting reports from 1960 to 2010 stored in this site. The raw dataset are html pages in a single json file. The reports information are parsed using BeautifulSoup library in python.


### The Problem

* What state has the most bigfoot sightings? Can you visualize this/compare them?

Analyzed unstructured data to determine and visualize location and timings of big foot sightings. Parsed raw HTML of bigfoot sighting reports using NLP techniques (TF-IDF) and performed topic modeling with Non-Negative Matrix Factorization to determine latent topics characterizing reports.
