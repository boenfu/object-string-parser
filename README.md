# object-string-parser

> ⚠️⚠️⚠️ actually the source code is only one sentence, and not secure, so don't use it.

#### Install

```bash
npm install object-string-parser
```

#### Usage

```javascript
import { parse } from "object-string-parser";

// 1.
const obj = parse("{foo: 200}").foo; // 200 😄

// 2.
JSON.stringify(parse("{bar: 50}"), undefined, 2);
// convert `{bar: 50}` to `{"bar": 50}`
```
