# slate-idb-store 

This Polymer 2 element provide access to browser's IndexedDb using [Jake Archibald's idb API](https://github.com/jakearchibald/idb) (indexedDb with promises).

## Why
With Polymer, when loading external script with `<script src=''></script>` in more than one component this external script will be loaded multiple time whereas `<link rel='import' src=''>` are de-duplicated.
That's why the best practice to use external lib in multiple components is throught a 'proxy' component like this one.

## Installation

Add the dependency to the `bower.json` of your application:

```
   "dependencies": {
     [...]
     "slate-idb-store": "slate-idb-store#1.0.0"
   }
``` 

And then recover them via `bower install`.

## Usage


## Demo !

[https://jefflefoll.github.io/slate-idb-store](https://jefflefoll.github.io/slate-idb-store)
 
```html
``` 

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D


## License

[Apache 2.0](http://www.apache.org/licenses/LICENSE-2.0)
