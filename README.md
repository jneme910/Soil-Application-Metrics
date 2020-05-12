# Explanation of Web Soil Survey Metrics Spreadsheet

## This is a brief overview for Web Soil Survey Metrics. 
Filter options are as follows:
STATE – Filter by two-letter state abbreviation or “xnational” for National 
query_frequency – Can be filtered on CY for Calendar Year, FY for Fiscal Year, or M for Month. 

*	Choosing CY will cause query_month to all be “1” which is the first month of the calendar year (January).  The aggregations have already been done for you and are displayed in COUNT
*	Choosing FY will cause query_month to all be “10” which is the first month of the fiscal year (October)  The aggregations have already been done for you and are displayed in COUNT
*	Choosing M will cause query_month to be 1 thru 12, except January of 2014 which we do not have data for. 
*	When choosing CY or FY the aggregations are already done for you. You do not have to add up all the Months for the year.  For example:  Filter by query_frequency = CY, query_year=2015, STATE=xnational, query_title=Ratings and you will see that in CY2015 for National the Hydrologic Soil Group rating was ran 101,238 times. 
*	When choosing FY be aware that if you filter by query_frequency = FY, query_year=2015 you will see query_month set to “10” and the results are actually FY2016 results because October 2015 is the beginning of FY2016. 

Additional WSS charts and metrics for other web pages and/or applications will eventually be added to the shared folder. 

Things to come:  
*	Least used ratings
*	Lease used reports
*	Soil Data Access charts
*	Lab Data Mart charts
* Web Soil Survey Centroid

