**This library allows you to quickly and easily use the Elastic Email Web API v2 via JavaScript.**

# Quick start #

## Getting account info in Node ##
```js	
const ee = require('elasticemail-webapiclient');

var eeClient = ee(
  {
    ApiKey: "YOUR-API-KEY"
  }
);

eeClient.Account.Load(function (data) {

  console.log(data);
});
```
## Getting account info in HTML ##
```js
//jQuery required!
var clientEE = EEAPI(
  {
    ApiKey: "YOUR-API-KEY"
  }
);

clientEE.Account.Load(function (data) {

  console.log(data);
})
```

## API ##
API documentation you can find on [Elastic Email website](https://api.elasticemail.com/public/help).

# About #
elasticemail-webapiclient is guided and supported by the ElasticEmail Dev Team.

elasticemail-webapiclient is maintained and funded by Elastic Email Inc. The names and logos for elasticemail-webapiclient are trademarks of Elastic Email Inc.

![logo](https://elasticemail.com/files/ee_200x200.png )