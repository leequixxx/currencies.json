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
  //     namePlural: 'US dollars',
  //     code: 'USD',
  //     symbol: '$',
  //     symbolNative: '$',
  //     decimalDigits: 2,
  //     rounding: 0,
  //   },
  //   {
  //     name: 'Russian Ruble',
  //     namePlural: 'Russian rubles',
  //     code: 'RUB',
  //     symbol: 'RUB',
  //     symbolNative: '₽.',
  //     decimalDigits: 2,
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
  //     namePlural: 'US dollars',
  //     code: 'USD',
  //     symbol: '$',
  //     symbolNative: '$',
  //     decimalDigits: 2,
  //     rounding: 0,
  //   },
  //   {
  //     name: 'Russian Ruble',
  //     namePlural: 'Russian rubles',
  //     code: 'RUB',
  //     symbol: 'RUB',
  //     symbolNative: '₽.',
  //     decimalDigits: 2,
  //     rounding: 0,
  //   },
  //   ...
  // ]
```