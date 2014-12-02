---
published: false
---


##“Views” in PostgreSQL plus Codebook for PoliInfomatics

I created 40 “views” – which I’ve learned are basically saved commands – for people at the conference to run on the dataset to see a sample of what sorts of results might be possible. I also created some tables “joining” the dataset of unique captures to the dataset of total captures (basically just a 1 if there was a duplicate of that capture taken on a later date). This would allow people to see every time a cite was captured, even if the content didn’t change. As well, I created a smaller version of the dataset – 3.5GB – so that if people want to test out a command on the smaller version, to see if it works, they can. Then they would not have to wait for commands to run on the bigger version of the database. I also wrote a “codebook” and access instructions for the PostgreSQL database, the views and tables, etc. which is [here](https://github.com/ekgade/Emilys-pigscripts/wiki/Example-Queries). I also posted a 8.5MB dataset of the counts of climate change terms, their ULR group (whitehouse.gov, senate.gov, etc.) and the month and year. This provides a subset of pre-created ‘data’ that people could experiment with to get a sense of the type of data that would be possible to scrape from the .gov cluster.
