# Strategic Competitor Awareness from Indeed.com job postings

## Goal

To identify a competitor or an industry's strategic direction of growth by analysing recruitment trends with respect to a firm of interest by scrapping data from Indeed.com.

## Implementation
1. Web scrape job listings data from Indeed.com,  refer `proj_scrape.py` for firms of Interest
2. Firms of interest here is the forbes 500 US firms and some other frims of interest, refer: `firms-forbes.csv` & `firms-NonForbes.csv`
3. Data scrapped for over 500 US firms, raw data available in `Data/Scrapped Data`
3. Scrapped data is processed by `analytica.py`, to tokenize the job listings using Natuaral Language Library: NLTK. 
4. Processed data can be visualised through Tableau dasboard
