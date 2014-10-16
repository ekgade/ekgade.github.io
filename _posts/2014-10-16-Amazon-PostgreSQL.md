---
published: false
---

## Database Creation

Today three main tasks were accomplished: 
  1) I broke my script into three parts that will correspond to PostgreSQL tables. The first is one that has all the unique observations of each capture mentioning global warming related words. The second pulls out all observations (even those where the content of the page was the same) of each capture mentioning global warming related words, but saves only the date of the capture, the URL and the checkedsum (so no more duplicate content). The third counts the words in all the documents across the whole cluster and saves a total count of each capture by URL and date. This is designed as a control variable and for tabulating term frequencies. 
  2) I created a new Amazon instance on the CAPPP cluster that will host the PostgreSQL database to hold the tables made from the above scripts.
  3) I installed postgres locally on my machine (via [homebrew](http://brew.sh/)) and connected to the new database (trickier than it sounds!). I created some sample tables to hold the results of the above scripts. 
Now I will run the scripts across the cluster over the next few days and concatenate results. Tuesday, I will attempt to upload the results into the database

