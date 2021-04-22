# URL Shortener 
## requirements
- Azure Cosmos DB with Mongo API storage
- NodeJS version ^8.1.2 
- npm version ^5.5.1
- any type of browser
## step to configure this code and run it locally
1. run this command `npm init --y ` inside your working directory for the first time and it will create `package.json` file
2. install the dependencies used for this project using this command `npm install --save body-parser@1.14.1 express@4.13.3 mongoose@4.2.9`
3. go to file `config.js` and change value for `uri` and `host` with yours from Azure Cosmos DB
  > in order to get the uri and host value, 
  >1. open your Cosmos DB storage account
  >2. Go to Settings category and select Connection String
  >3. copy value in Host and Primary Connection String
  >4. replace the value field with the corresponding field inside the `config.js`

4. open your terminal and run this project with this command `node app.js`
5. click the link provided in the terminal and shorten your looonggg url!
## This is the web interface if you succeed run this project
![end result](views/web%20url%20shortener.png)