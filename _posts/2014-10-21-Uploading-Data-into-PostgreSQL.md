---
published: false
---

## PostgeSQL Uploads

Today I worked on uploading the data from my scripts that scrape all mentions of climate change into the Amazon instance that I created last week. With Andrew's help, I solved two key problems: first, we discovered how to find the Unicode field delimiter we created and tell PostgreSQL to identify fields by that instead of tabs or commas. Second, we added a find/replace option into my initial script so that there are no '\n' mentions in any of the content fields. We also downloaded a PostgreSQL GUI to help make the dataset more accessible for other users. We have uploaded the results of one WARC file into the dataset and all the fields still exist. Now we are writing a python script to automate the transfer of all nearly 900 results files from the cluster into the new PostgreSQL database.

Tag: incubator