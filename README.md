# busarrivals.org

The goal of this project is to provide a unified UI between Sound Transit's [OneBusAway](https://onebusaway.org), and Community Transit's [BusFinder](http://mybusfinder.org).  

Both provide REST APIs for their data; the main complexity comes in (1) normalizing the different data formats, and (2) mapping stop numbers between agencies, possibly using latitude/longitude and/or address.

Given the generic nature of the domain name this maps to, this may be genericized to showing estimated bus arrival times using GTFS feeds from multiple cities. 
