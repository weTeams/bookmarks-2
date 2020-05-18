# bookmarks

### Description
Online bookmarks tool.
* NodeJS REST API (express, mongoose, mongodb). 

### Version 0.0.1 
__Early stage of construction__. This is __not ready__ for consumption, nor contribution.
* The basic API works
* The app is deployable
* Database connection is working
* Data can be retrieved

### Instructions
1. Create a .env file in the main directory. This provides access to the mongodb database and sets deployment port. The url below points to a locally deployed instance, named MyDatabase. This should be updated with your db connection string.
```javascript
DB_CONNECTION=mongodb://localhost:27017/MyDatabase
```
2. Install node and npm
3. $ npm install
4. $ node server.js
5. http://localhost:3000
