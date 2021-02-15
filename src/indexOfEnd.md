# indexOfEnd

Returns the last index of the substring given of the string given,
Behaves the same as `String.prototype.indexOf()` for other details.

If the substring is of length 1, it returns the same as `String.prototype.indexOf()` and therefore you should use that.

## Usage

```typescript
import { indexOfEnd } from "https://deno.land/x/grutils@0.0.5/mod.ts";

console.log(indexOfEnd("hello there!", "ere")) // prints 11
```
