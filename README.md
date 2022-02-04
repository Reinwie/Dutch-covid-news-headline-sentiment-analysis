# Dutch-covid-news-headline-sentiment-analysis

Hi! This is the code I created for my master's thesis, a sentiment analysis of Dutch online Covid news headlines. 

Here's what the code does:
- Headline scraper.ipynb
  - Scrapes headlines and some metadata from the search results of NRC.nl, Telegraaf.nl, NOS.nl, Trouw.nl and Volkskrant.nl. 
  - Scrapes headlines from the search results of Nexis Uni (requires valid login credentials)
- Sentiment analysis.ipynb
  - Contains some code for cleaning up the NRC Emotion Lexicon (EmoLex) by Mohammad and Turney
  - Uses Pattern-nl and EmoLex to analyze the headlines scraped using the code in the previous file
- Duplicate finder
  - Finds unique headlines between data from Nexis Uni and the search engines on NRC.nl and Telegraaf.nl.

Be aware, some websites may not want their search results to be scraped. I'm not responsible for the way you use my code and the data it produces.
