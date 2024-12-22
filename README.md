# Iso Date Converter

A lightweight TypeScript library that converts ISO 8601 date strings to YYYY-MM-DD format. Perfect for when you need to extract just the date portion from a full ISO timestamp.

## Installation

```bash
npm install iso-date-converter
```

## Examples

```ts
import { dateConvert } from 'iso-date-converter'

const date = dateConvert('1970-01-01T00:00:00.000Z')
console.log(date) // '1970-01-01'
```

## License

Distributed under the MIT License. See [LICENSE](LICENSE) for more information.