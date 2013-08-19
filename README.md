ClubFinance-SQL
===============

structured queries and simple tables to help analyze club finances and day-care finances

ENGLISH

A collection of Hyper SQL queries (stored in OpenOffice Base), views and tables created for the treasurer of
a day-care center  supported by  a club of parents.
It has a small number of small tables which are manually filled and then does various queries on a large external *.csv (tab stop separated) file containing transactions. Right now getting this file from the bank into HyperSql is a manual process involving a web browser, notepad++,  cat, tac, gawk -f gawt00.txt temp01.csv > .

Useful Queries:
Children did they pay
Umsatz Match Kibiz
UmsatzKostenstelle
UmsatzRestAsQuery
QUOTE_RELATION_FOLLOW0_POSITION

The last query is used to extract the cost of a larger project. Looking up pay scale is done by a separate database which still needs to be cleaned up. I miss rename refactoring in my current working environment. Anyway, the planned naming convention is:
Identifier have spaces. Words which belong closer together have fewer spaces between them.
Phrases have upper and lower case.
Single words and acronyms are all caps.
I count C-like ( ordinal numbers start with 0, too).
For words from computer science American English is used, but for accounting often the German (De-De) words are used.

GERMAN

Eine Sammlung von HyperSQLdb1.8 Abfragen (abgespeichert in einer OpenOffice 4 Base Datei), Sichten und Tabellen für den Kassenwart einer
Kita getragen durch eine Elterninitiative (eingetragener Verein).