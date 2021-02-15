# Direction

An enum contaning the 4 cardinal directions.

Enums are 0-indexed, therefore the values(if assigned to a variable or something along those lines) are as such:
<!--
|Direction  |Value      |
|-----------|-----------|
|North|0                |
|South|1|
|West|2|
|East|3| -->

## Usage

```typescript
import { Direction } from "https://deno.land/x/grutils@0.0.5/mod.ts";

let north = Direction.North;

console.log(north); // prints 0
```

## Notes

 - If you import this from it's file, it is not default exported due to how exports interact with enums.