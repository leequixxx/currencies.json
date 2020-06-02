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
  //     name: 'US Dollar',
  //     name_plural: 'US dollars',
  //     code: 'USD',
  //     symbol: '$',
  //     symbol_native: '$',
  //     decimal_digits: 2,
  //     rounding: 0,
  //   },
  //   {
  //     name: 'Russian Ruble',
  //     name_plural: 'Russian rubles',
  //     code: 'RUB',
  //     symbol: 'RUB',
  //     symbol_native: '₽.',
  //     decimal_digits: 2,
  //     rounding: 0,
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
  //     name: 'US Dollar',
  //     name_plural: 'US dollars',
  //     code: 'USD',
  //     symbol: '$',
  //     symbol_native: '$',
  //     decimal_digits: 2,
  //     rounding: 0,
  //   },
  //   {
  //     name: 'Russian Ruble',
  //     name_plural: 'Russian rubles',
  //     code: 'RUB',
  //     symbol: 'RUB',
  //     symbol_native: '₽.',
  //     decimal_digits: 2,
  //     rounding: 0,
  //   },
  //   ...
  // ]
```