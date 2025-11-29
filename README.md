# Welcome to Filghts Service

# Project setup
-clone the project on your local 
-execute `npm install` on the same path as of your root directory of the downloaded project
-create a new `.env` file in the root directory and add the following enviornmane variable
    -`PIRT=3000`
-Inside the `src/config` folder create a new file `config.json` and then add the following piece of json

```
{
  "development": {
    "username": <>YOUR_DB_USERNAME,
    "password": <YOUR_DB_PASSWORD>,
    "database": "Flights_Search_DB_DEV",
    "host": "127.0.0.1",
    "dialect": "mysql"
  },

}

```
