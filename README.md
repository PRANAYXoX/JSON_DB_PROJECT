# JSON_DB_PROJECT_On DATABASE CONNECTIVITY 
## Description
This project demonstrates how front end web application communicates with JSONPOWERDB. This project includes:-
1. CSS
2. HTML
3. JAVASCRIPT
4. JsonPowerDb specific connectivity codes.

## BENEFITS OF USING JsonPowerDB:-
- JsonPowerDB is a Database Server with Developer friendly REST API services. It's a High Performance, Light Weight, Ajax Enabled, Serverless, Simple to Use, Real-time     Database.

- Easy and fast to develop database applications without using any server side programming / scripting or without installing any kind of database.

- Whether it's a Dynamic Website or a Mobile App or some Data Analytics Portal, the development is real fun and fast. Nothing better than trying it yourself. What all     you need is a basic understanding of HTML, CSS, Bootstrap, and Javascript.
![](/Screenshot(870).png)

## JsonPowerDb Release History:-
### 0.2.5 / 2017-08-10
 * Added: Any Json row if inserted by default it will store in JsonPowerDB.
 * Added: User have facility to remove database.
 * Added: User can add new index or column in JsonPowerDB.
 * Added: User can remove single column in JsonPowerDB.
 * Fixed: If Column is not added(indexed) in PowerIndex then Error Message returned to the Client.
### 0.2.7 / 2017-09-19
 * Added: Developer dashboard more easy to use, by which developer can insert, remove, update records easily.
 * Added: NoSQL, using this feature developer can write their own query script in native (java) language and execute that script on JsonPowerDB server.
 * Added: NoSQL is designed using QueryService interface which contains some ready to use high performance, easy to use query support methods.
 * Added: NoSQL also has support for passing parameters to the QueryService interface’s execute methods.
 * Added: User can add new index and remove existing index into/from JsonPowerDB.
 * Fixed: Restricted indexing on Boolean columns.
 * Fixed: Method which give accurate file size by deducting deleted record count.
### 0.3.2 / 2020-10-08
* Added : Added Plugin API Framework in JsonPowerDB.
* Added : Added a new class APISyntaxValidator to check syntax of request json.
* Added : Added a new APIs for column operation and implement it using pluggable framework:
             Copy Column - It will copy column in database.
             Rename Column - It will rename column in database.
             RemoveColumn - It will remove column in database.
             Change Column type - It will change type of column in database.
* Improved : In Geospatial distance API to pick create time column (sorted in ascending) as time range 
             (by default it should pick the record creation time from the JPDB system file internal 
             recorded time) defined in request fromTime to toTime.
* Fixed : Fixed important bugs.  
### 0.3.2 / 2021-04-10
* Added : New type "REMOVE" in Set API for delete operations, in compliance with RDBMS constraints.
* Added : New response headers that display time taken by the JPDB server to serve request.
* Added : ForeignKeys functionality in SET and SET_ALL API to provide complete support for the soft implementation of RDBMS.
* Added : Started Reporting of All Unhandled Exceptions via email.
* Added : A new version of jpdb-commons.js 0.0.4 added with SET & SET_ALL methods and help for all commands
* Improved : Parsing time for request now reduced.
* Improved : Response message for syntax error in case of empty body in request.
* Improved : Known exception handling.
* Improved : Help Documentation.
* Improved : jUnit Test Cases.
* Various bug fixes.

