# Test1


INTRO
======

This app get interest rates from MAS using API.

It works according to the following steps:

1. Prompt user to enter dates using enterDate() method. it will verify using checkDate() method.
If the date is entered wrongly the user will be asked to re-enter the date.

2. The dates will input into setQuery() method to create the API query.

3. getQuery() will call sendRequest() using with the query.

4. sendRequest() will call the MAS webservice and extract the data, the result will be trimmed to extract the JSON array, this will be put into an array of Record object.

5. the printRates() will then extract the data to print out.

6. trend() method will determine the trend, it will be called together with printRates()

INSTALLTION
===========

The project was create using Ecilipse using a Macbook and it zipped. The project file should be imported into an Ecilipse without issue.

RUNNING THE APP
===============
The app has been tested run on Eclipse, app will prompt for the date from and date to for the interest rates.

KNOWN ISSUE(S)
===============
trend() method not able to produce accurate result.
unable to export to runnable jar file (mac issue?).

