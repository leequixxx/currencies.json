# currencies.json

Full list of currencies

## Examples
```javascript
  // example.js

  const currencies = require('currencies.json');

  console.log(currencies);
  // Output:
  //
  // [
  //   ...
  //   {
  //     code: "USD",
  //     decimal_digits: 2,
  //     name: "US Dollar",
  //     name_plural: "US dollars",
  //     rounding: 0,
  //     symbol: "$",
  //     symbol_native: "$",
  //   },
  //   {
  //     symbol: 'RUB',
  //     name: 'Russian Ruble',
  //     symbol_native: '₽.',
  //     decimal_digits: 2,
  //     rounding: 0,
  //     code: 'RUB',
  //     name_plural: 'Russian rubles',
  //   },
  //   ...
  // ]
```

```typescript
  // example.ts

  import { currencies } from 'currencies.json';

  console.log(currencies);
  // Output:
  //
  // [
  //   ...
  //   {
  //     code: "USD",
  //     decimal_digits: 2,
  //     name: "US Dollar",
  //     name_plural: "US dollars",
  //     rounding: 0,
  //     symbol: "$",
  //     symbol_native: "$",
  //   },
  //   {
  //     symbol: 'RUB',
  //     name: 'Russian Ruble',
  //     symbol_native: '₽.',
  //     decimal_digits: 2,
  //     rounding: 0,
  //     code: 'RUB',
  //     name_plural: 'Russian rubles',
  //   },
  //   ...
  // ]
```