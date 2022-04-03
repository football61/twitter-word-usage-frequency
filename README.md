# twitter-word-usage-frequency
Scrapes tweets from members of congress and calculates words usage frequencies from SAT, Profanity, and Elementary School word lists

handles.csv contains handles, first names, last names, stdis(state and district), and party.

The script reads handles.csv for twitter handles to scrape.
Scraped tweets are put into the congress_22 folder.
The tweets are processed and word usage frequencies are calculated based on their presence in each of the word lists: SAT, Profanity, and Elementary School.


The script can be modified for any list of twitter handles.
