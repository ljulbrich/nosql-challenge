# nosql-challenge

### Files
`NoSQL_setup_starter.ipynb`
* This file should be run first to load the database
* This code will require the use of mongosh shell terminal as well as your prefered shell terminal
* Run the code in the first markdown section in the appropriate shell terminals to load the database

`NoSQL_analysis_starter.ipynb`
* This loads data from the mongo database into pandas dataframes for easy manipulation

`\Images\database_setup_and_import\`
* This image shows what a successful database setup and import should look like
* The left terminal is mongosh. The right terminal is git bash.
![successful setup and import image](https://github.com/ljulbrich/nosql-challenge/blob/main/Images/database_setup_and_import.PNG)

`\Resources\establishments.json\`
* This json file is a dataset which is used throught this project

### Sources
`https://stackoverflow.com/questions/61456784/pymongo-cannot-encode-object-of-type-decimal-decimal`
* Used to import Decimal128 to convert strings to decimals
* Didn't end up using this. Instead converted the types to doubles

`https://www.mongodb.com/docs/manual/reference/bson-types/`
* Used to check the datatypes

`https://stackoverflow.com/questions/48365283/how-to-find-values-between-a-range-in-mongodb`
* Used in the 3rd analysis question to find the coordinate range
