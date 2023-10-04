# country-state-mapping

## usage

```js
const sevice = require("country-state-mapping");
/**** using the iso code */
const x = sevice.getStateList("DZ");
console.log(x);
```

If want the entire data

```js
const sevice = require("country-state-mapping");
console.log(sevice.db);
```
