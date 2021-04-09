# wordlists
=======================================
A collection of wordlists ive mushed together 
Nothing really special here alot is taken from common wordlists repos with some extra bit.


##### /webapp

**find-goodies_30k** - This is a mush of looking for default content, vulns and look for juicy endpoints - I have tried to organise this in a logical way but still get a bit of a mess. Trying to keep it at a 30k limit. Useful for a once over to identify any low hanging fruit. best used with tool like FFUF as the list doesnt have / at start annd includes extentions est so keep that in mind. this does have some junky strings in so filtering output will help alot



##### /passwords

**easy-passwords_15k** - Mainly a merge of all top password lists the usual suspect. Trying to keep it arond 15k so it can be quickly blasted to see if you get any hits. good for cracking hashes or bruteforcing ports that dont rate limit ya

###### /sql-injection

**sqli-everything** - This is all the SQL wordlists in one. aimed to try an detect first then into other method. Best used with Burp to fuzz a parameter. If you notice it sticking or slowing down it may be sleeping so check the output 
