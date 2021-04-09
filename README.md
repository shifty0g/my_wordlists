wordlists
=======================================

A collection of wordlists ive mushed together
Nothing really special here alot is taken from common wordlists repos with some extra bit.


##### webapp/discovery/find-goodies_30k.txt

This is a mush of looking for default content, vulns and look for juicy endpoints - I have tried to organise this in a logical way but still get a bit of a mess. Trying to keep it at a 30k limit. Useful for a once over to identify any low hanging fruit. best used with tool like FFUF as the list doesnt have / at start annd includes extentions est so keep that in mind. this does have some junky strings in so filtering output will help alot

##### webapp/sql-injection/sqli-everything.txt

This is all the SQL wordlists in one. aimed to try an detect first then into other method. Best used with Burp to fuzz a parameter. If you notice it sticking or slowing down it may be sleeping so check the output 

##### webapp/probe.txt

This is a good one. its aimed at probing applications for common things. you will see its split into sections and has a flow to it allowing you to see how the app responsds. use with Burp

##### passwords/easy-passwords_15k.txt
Mainly a merge of all top password lists the usual suspect. Trying to keep it arond 15k so it can be quickly blasted to see if you get any hits. good for cracking hashes or bruteforcing ports that dont rate limit ya

#### usernames/users-default.txt

Tis is just my modified default usernames list - useful to quickly check
