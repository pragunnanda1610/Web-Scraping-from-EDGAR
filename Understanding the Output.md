UNDERSTANDING THE OUTPUT:

The output has been simplified to a great extent and listed with proper headings in order to avoid any confusions.

Sample Output:
```
1.	Enter SIC numbers separated by space: 2810 2800 2860
2.	SIC numbers:  ['2800', '2810', '2860']
3.	Enter the type of filing: `10-k`
4.	['10-k']  filing
5.	Starting period (YYYYMMDD): `20150101`
6.	Ending period (YYYYMMDD): `20160101`
7.	SIC Code- 2800
8.	List of Companies from SIC Code 2800 below-
9.	https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&myowner=exclude&SIC=2800&count=100
10.	Request Successful
--------------------------------------------------------------------------------------
11.	PRAXAIR INC CIK#: 0000884905 (see all company filings)
12.	Below is the link to all your selected Filings
13.	https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000884905&owner=include&count=100&type=10-k&dateb=20160101&datea=20150101
14.	Below are links to your specified form type
15.	https://www.sec.gov/cgi-bin/viewer?action=view&cik=884905&accession_number=0000884905-15-000027&xbrl_type=v
16.	PRAXAIR INC CIK 0000884905  0.xls
17.	https://www.sec.gov/Archives/edgar/data/884905/000088490515000027/Financial_Report.xlsx
--------------------------------------------------------------------------------------
18.	https://www.sec.gov/cgi-bin/viewer?action=view&cik=884905&accession_number=0000884905-15-000016&xbrl_type=v
19.	PRAXAIR INC CIK 0000884905  1.xls
20.	https://www.sec.gov/Archives/edgar/data/884905/000088490515000016/Financial_Report.xlsx
--------------------------------------------------------------------------------------
```
Here,
* Line 1-6 are the input data that the user enters. These are the search parameters as preferred by the user.
* Line 7 depicts the current SIC code in which the search is being made.
* Line 9 is the URL that redirects to the EDGAR page when the search is made for an SIC. You can view the list of all the companies here.
* Line 11 is the current company that the search returns, along with its CIK number. You will see the filings for this company below.
* Line 13 is the URL that redirects to the search results for 10-k(here) or 10-q filings in the specified time period.
  All the available filings as per the specified prameters will be listed here.   
* Line 15 URL redirects you to the filing page, where you can view all the "Interactive Data" for a specific 10-k(here) or 10-q filing.
* Line 16 is the name of the excel file that will be downloaded in your directory, along with it's hyperlink in the next line 17.
* Line 18 In case of multiple 10-k(here) or 10-q filings for a company in the specified time period, links for all the filing pages
  will be provided for Interactive Data in a similar way (ref. Line 15).   
* Line 19 The multiple filings of the a company in the given time period will be downloaded in an orderly way under the names   
  `<company name with CIK> 0.xls`, `<company name with CIK> 1.xls`, `<company name with CIK> 2.xls`, and so on until all filings for that particular company have been downloaded.   
