# Assignment-7-Data-Curation-and-Analysis

The goal of my project is to construct, analyze, and publish a dataset on data.world. All analysis performed in a single Jupyter notebook and all data, documentation, and code published in a single GitHubLinks to an external repository.

This assignment demonstrates that I can follow best practices for open scientific research in designing and implementing my project, and make my project fully reproducible by others: from data collection to data analysis.

Links to any relevant API documentation: https://www.mediawiki.org/wiki/API:Main_page

The license of your data and any source data: https://en.wikipedia.org/wiki/Wikipedia:Text_of_the_Creative_Commons_Attribution-ShareAlike_3.0_Unported_License

References:
"Time Zone Database". IANA. 2017-02-28. Retrieved 2019-08-05. "Time Zone & Clock Changes in Troll Station, Antarctica". www.timeanddate.com. Retrieved 2019-08-05.

A data type and description for each attribute in your data: 
'Country code(s)' - String that depicts all country codes in the TZ database. 
'TZ database name' - String of countries and continents. '
Type' - String of either Link (An alternative name (alias) which links to a canonical zone) or Canonical (The primary, preferred zone name) time zone. 
'UTC offset±hh:mm': - String of hour difference from 00:00 (the Standard time difference) 
'UTC offset±hh:mm.1' - String of hour difference from 00:00 (the Daylight Savings time difference) 
'Time zoneabbreviation' - String of the abbreviation of a time zone. (the Standard time difference) 
'Time zoneabbreviation.1' - String of the abbreviation of a time zone. (the Daylight Savings time difference) 
'Sourcefile' - String of the continent.

Any known issues or potential issues, such as sources of bias in collection: A potential issue with the data would be inaccurate data collection since the data was from 2019 and since then there are many US states that are attempting to not have a daylights saving time and many of those states are in the CST which is the most common in the database.
