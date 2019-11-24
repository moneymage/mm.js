# mm.js
Money Mage JavaScript library for Personal Finance Calculators and Charts

## Dependencies

Full list of dependencies are:

* moment.js/2.20.1
* Chart.js/2.7.1
* clipboard.js/1.5.3
* d3/5.12.0

You may reduce this list depending on what functionality you are using.

```
<script src="https://cdnjs.cloudflare.com/ajax/libs/moment.js/2.20.1/moment.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/2.7.1/Chart.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/clipboard.js/1.5.3/clipboard.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/d3/5.12.0/d3.min.js"></script>
<script src="{{ site.url }}/mm.min.js"></script> <!-- minified mm.js -->
```

## Minify

mm.js is successfully minified by Transpiling to ES5 and minifying with uglifier

```
require 'uglifier'
require 'babel/transpiler'

script_data = "..."
es5 = Babel::Transpiler.transform script_data
output = Uglifier.new().compile(es5["code"])
```

## Documentation

Full documentation and examples can be found at https://www.moneymage.net/calculators/embed/

## About mm.js

## License

mm.js is licensed under a derivative MIT license. Any usage must provide a backlink to https://www.moneymage.net/calculators/. See [LICENSE.md](LICENSE.md) for more details.
