## currency-decimal-places

In order to convert easily money amounts in whole integer to their original amounts. The list is based off of [wikipedia](https://en.wikipedia.org/wiki/ISO_4217)

#### Usage

```javascript
import {getDecimalPlacesForCurrency} from "@nexapp/currency-decimal-places"


const currency = "CAD" // ISO 4217 currency code (3 letters)
const decimalPlaces = getDecimalPlacesForCurrency(currency)
// decimalPlaces is 2, you can use money libraries like Dinero to convert a cent amount to the desired decimal format

```