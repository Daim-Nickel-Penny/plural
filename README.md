# PLURALIZED

This a NODE.Js module which returns the plural form of the input word.

## For Installation

    npm i pluralized

## Usage

For using the **npm** files.

### JavaScript

```javascript
var pluralise = require("pluralized");
var boys = pluralise.getPlural("Roof");
```

```sh
Output shown will be 'Roofs'
```

### TypeScript

```typescript
import { getPlural } from "mypluralize";
console.log(getPlural("Shelf"));
```

```sh
Output shown will be 'Shelves'
```

### Asynchronous module definition

```javascript
define(function (require, exports, module) {
  var pluralise = require("mypluralize");
});
```
