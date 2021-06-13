# Web-Scraping-from-EDGAR

Created an automated web scraping tool to extract real time key data (10-K and 10-Q filings) from SEC EDGAR, for various parameters as requested by the user.
Created the tool from scratch, in Python using the libraries Requests, Pandas, Beautiful Soup, Re, Urllib. The task of the user is to just input the required time period, the type of filings, and the SIC numbers for the Market Sector for which the filings are required, and within just these few clicks, the program would navigate, seach, parse from thousands of pages and start downloading from the EDGAR database. On completion it yields a sorted folder of all the available files for the specified parameters, along with the list of Companies for which the data is available. The data is presented in an organised and user friendly manner, which can be used for further analysis without needing much cleaning.
Final working model was successfully able to download around 8GB+ of data, comprising of 1500+ filings for 100+ companies in the Chemical Sector, across a period of 10 years, in just under 45 minutes. Otherwise if done manually, for a single person, this task would have taken several days and a lot of physical effort, thus improving the efficiency of the Analytics team and saving a huge amount of time for the company.

For details and a run through of the code and a guide to understandng the outputs, go through the [SCRAPING TOOL Documentation](SCRAPING TOOL Documentation).
