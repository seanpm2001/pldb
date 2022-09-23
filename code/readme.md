# PLDB: a Programming Language Database

## Over 100,000 facts on over 4,000 languages in 1 typed JSON file with 0 dependencies

This is the readme for the npm distribution of `pldb.json`.

Installing:

```console
npm install pldb
```

Using:

```js
const pldb = require("pldb")

console.log(
	Object.values(pldb)
		.filter(item => item.type === "pl" && item.appeared === 1972)
		.map(item => item.title)
)
```

## Also available on the web and as CSV:

https://pldb.com/pldb.json

OR:

https://pldb.com/pldb.csv