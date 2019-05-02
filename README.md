# tdjsa-tickers
Following "Test Driving JavaScript Applications" test driving the chapter 5 node.js application

## Test cases
- `read` invokes `processTickers` if the file is valid
- `read` invokes an error handler if the file is invalid
- `processTickers` calls `getPrice` for each ticker symbol
- `getPrice` calls the web service
- For valid response, `getPrice` updates the prices collection
- For failed response, `getPrice` updates the `errors` collection
- `getPrice` calls `printReport` in the end
- `printReport` prints the results in sorted order
