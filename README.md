# sails-generate-new-coffee

A CoffeeScript generator for Sails.js.


## Usage

#### On the command line

```sh
sails new projectName --coffee
```

#### In a node script

```javascript
var generate = require('sails-generate');
var scope = {};
generate(require('sails-generate-new-coffee'), scope, function (err) {
	if (err) throw err;

	// Log output available in `scope` for your enjoyment:
	console.log(scope);
});
```


## Contributing to this generator

See `CONTRIBUTING.md`.

## License

See `LICENSE.md`.

