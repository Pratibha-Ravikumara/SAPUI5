
# Sample oData Service

This is a sample oData service with CRUD operation. You can setup a simple oData service to test your UI5 Application locally.

This is a part of training material used in youtube channel : https://www.youtube.com/c/codingwithsijas

Learn UI5: https://youtube.com/playlist?list=PL54pcs7d52yfSdwl9h37kGY7vre4L1aUS





## Installation

Install capire sdk globally

```bash
    npm i -g @sap/cds-dk
```
Test it by 
```bash
    cds
```

Clone this repository and navigate to the folder

```bash
    npm install
```
To create a local persistancy in your system run

```bash
    cds deploy --to sqlite:my.db
```
The above line will create a db using sqlite3. The default data will be loaded from ./db/data folder. Modify the csv for your initial data.

To run your oData service
```bash
    npm start
```

open the service at : http://localhost:4004/ 
