# country-state-mapping

## Usage

![Badge for GitHub repo top language](https://img.shields.io/github/languages/top/connietran-dev/readme-generator?style=flat&logo=appveyor) ![Badge for GitHub last commit](https://img.shields.io/github/last-commit/suvradip/country-state-mapping)

```js
const sevice = require("country-state-mapping");
/**** using the iso code */
const x = sevice.getStateList("DZ");
console.log(x);
```

> If want the entire data

```js
const sevice = require("country-state-mapping");
console.log(sevice.db);
```

## License

MIT
