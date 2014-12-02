---
published: false
---

##Index Issues and PostgreSQL Speed

The Amazon Instance with the PostgreSQL and GUI front end via PhpPgAmdim is very slow for running any sorts of basic PostgreSQL commands. Andrew and I did some research to find out ways to speed it up. It looks like creating an index should help, so I started running that today. I used the turns out indexing all 252GB takes quite a while and didn’t really speed up the processing time required to run a PSQL command. As a result, I uploaded a much smaller version of the total dataset, about 3.5GB as a test dataset. It is much easier to run commands over this version, and the hope is that people could test their PostgreSQL commands over this smaller version, and then if they wanted full results, run them over the larger dataset (and have to wait a while). I still believe the user interface will be more accessible to political scientists than hadoop, but I’m not sure whether this actually solves the problem because it might slow enough that even the user interface doesn’t make it accessible. 

