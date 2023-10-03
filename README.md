## Install

```
$ npm install find-country-state-city
```

## Usage
### Country
```
const findCountryStateCity = require('find-country-state-city');

// If Get All Country that Call below method
findCountryStateCity.getCountry();

// If Get Specific Country that Call below method
findCountryStateCity.getCountry('india');

output return a country array
    "name": "India",
    "code": "IN",
    "id": 103,
    "phone": 91,
    "symbol": "₹",
    "capital": "New Delhi",
    "currency": "INR",
    "continent": "Asia",
    "continent_code": "AS",
    "alpha_3": "IND"
```

### State
```
const findCountryStateCity = require('find-country-state-city');

// If Get All State that Call below method
findCountryStateCity.getState();

// If Get Specific Country State that Call below method
findCountryStateCity.getState("IN"); // Country Code

output return a state array
    name: 'Rajasthan',
    isoCode: 'RJ',
    countryCode: 'IN',
    latitude: '27.02380360',
    longitude: '74.21793260'
```