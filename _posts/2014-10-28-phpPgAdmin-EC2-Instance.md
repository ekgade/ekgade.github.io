---
published: true
---

## Finally Up and Running!

We finally have our database up and running. I created (with Bill's help!) an EC2 instance to host PhpPgAdmin to be the frontend of our database and enable people with the login info to write SQL queries against the database without having to ssh in. The database is hosted [here.](http://ec2-54-191-15-66.us-west-2.compute.amazonaws.com/phppgadmin/). It contains all the .gov documents that had at least one mention of any climate change related terms.
Potential queries we would like to run on this dataset: Which was the first site to mention any type of climate change related word? Which was the first to mention each specific term? Which sites have used these terms the most? How did the use of these terms spread through the .gov domain?