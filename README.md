#### Unsupervised Learning Case Study

Webscraping Bigfoot sighting description and conducting topic modelling using tfidf and non-negative matrix factorization (NMF)

### Bigfoot Sightings

A data set of bigfoot sighting reports was collected from the [Geographic Database of Bigfoot / Sasquatch Sightings & Reports](http://www.bfro.net/gdb/); you can see an example report [here](http://www.bfro.net/GDB/show_report.asp?id=13038). The data, downloadable as a zipped `json` file [here](https://s3.amazonaws.com/ufodatafordarren/bigfoot_data.json.zip), contains the URL, raw HTML for that URL, and the time it was scraped for each report in the database along with the remnants of a database id.

### The Problem

Find something interesting in the data! That's not very specific, so here are some thoughts to get you going:
* What state has the most bigfoot sightings? Can you visualize this/compare them?

A huge part of the challenge for this case study will be getting the data into a usable form, so don't fret about finding something mind-blowingly insightful in the data. Simply verifying a suspicion you have with a model or summarizing a quality about the data that is difficult to see in the raw data is good data science.
