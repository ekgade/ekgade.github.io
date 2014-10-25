---
published: true
---

## Week Four of eSceince Data Incubator: Wrestling Unicode.

Thus far, my project has been moving along very quickly and I couldn't be more pleased with the support the incubator has provided. Rather than staying "stuck" on lines of code for days, thanks to careful help from Andrew, Dan and Bill, I have been zooming through. Today though, we struggled. Andrew and I have been working on piping the results of my climate change scrape from the Hadoop cluster into a PostgreSQL database using Python. We encountered a whole list of errors, from random unrecognized Unicode characters to the wrong number of columns, but I think we have resolved them. This involved re-writing my pig scripts to remove all non-visible characters with the RegEx [^\\{Graph}] for the title, content, and description fields of each webpage, as well as some fancy work with Python to remove carriage returns and add extra backslashes so that PSQL and the Java underwriting the Hadoop cluster can talk to one another. Whew!