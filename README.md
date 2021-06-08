# JsonPowerDB  

# Release History 1.0.0

## "This project is all about basics of JsonPowerDB (JPDB) and how to use JPDB for PUT and GET operations." 

## "This project is in developing phase so you can use that project as template for you and add more required functionality over this."

### About JsonPowerDB:

- JsonPowerDB is a Real-time, High Performance, Lightweight and Simple to Use, Rest API based Multi-mode DBMS. JsonPowerDB has ready to use API for Json document DB, RDBMS, Key-value DB, GeoSpatial DB and Time Series DB functionality. JPDB supports and advocates for true serverless and pluggable API development.

### Benefits of using JsonPowerDB

- Simplest way to retrieve data in a JSON format.
- Schema-free, Simple to use, Nimble and In-Memory database.
- It is built on top of one of the fastest and real-time data indexing engine - PowerIndeX.
- It is low level (raw) form of data and is also human readable.
- It helps developers in faster coding, in-turn reduces development cost.

For more information you can refer following document 
  [Documentation Link](http://login2explore.com/jpdb/docs.html)

### Examples of use:

 1. For **PUT** operation , we have to send following JSON to link **http://api.login2explore.com:5577/api/iml**

           {
              "token": "<generated token>",
              "cmd": "PUT",
              "dbName": "SAMPLE",
              "rel": "emp-rel",
              "jsonStr": {
                  "empId": 1,
                  "empEmail": "shub@gmail.com",
                  "empName": "shub",
                "mobile_no": 98764324564
              }
           }
2. For **GET_ALL** operation , we have to send following JSON to link **http://api.login2explore.com:5577/api/irl**

           {
              "token": "<generated token>",
              "cmd": "GET_ALL",
              "dbName": "SAMPLE",
              "rel": "emp-rel"
           }
 For more information you can refer following document 
  [Documentation Link](http://login2explore.com/jpdb/docs.html) 
  
  
 
