# Kraken API
A client for the Kraken API based on Node.js

## Installation:
Use the following command to add this package as a dependency to your project:
```
npm install git+https://github.com/Asgaros/kraken-api.git
```

## Example:
```javascript
const api_key = 'xxx';
const api_private_key = 'xxx';
const KrakenAPI = require('kraken-api');
const kraken = new KrakenAPI(api_key, api_private_key);

(async () => {
	console.log(await kraken.request('Balance'));
})();
```
