download the code and try to run following command in cmd nad install dependency:
npm install request
npm install promise
npm install parser
npm install await
npm install yargs

After running avobe command try to execute the index.js using command:

//Given a date and a token, return the portfolio value of that token in USD on that date
//node .\index.js --date=4/3/2018 --token=BTC

//Given a date, return the portfolio value per token in USD on that date
//node .\index.js --date=4/3/2018

//Given a token, return the latest portfolio value for that token in USD
//node .\index.js --token=BTC

//Given no parameters, return the latest portfolio value per token in USD
//node .\index.js
