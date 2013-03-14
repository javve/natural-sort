![web component logo](http://i49.tinypic.com/e7nj9v.png)

# naturalSort

Natural sort algorithm with unicode support.

The algorithm is written by [Jim Palmer](http://www.linkedin.com/in/jimbob)
and found at [http://www.overset.com/2008/09/01/javascript-natural-sort-algorithm/](http://www.overset.com/2008/09/01/javascript-natural-sort-algorithm/).

I, [javve](http://github.com/javve), only put it into a Component.

## Installation

    $ component install javve/natural-sort

## Example

```js
var naturalSort = require('natural-sort');

var values = ['B', 'a', 'D', 'c'];

values.sort(naturalSort); // ['B', 'D', 'a', 'c']

naturalSort.insensitive = true;

values.sort(naturalSort); // ['a', 'B', 'c', 'D']

naturalSort.desc = true;

values.sort(naturalSort); // ['D', 'c', 'B', 'a']

```

Find more examples at [http://www.overset.com/2008/09/01/javascript-natural-sort-algorithm/](http://www.overset.com/2008/09/01/javascript-natural-sort-algorithm/)
or look at the tests in `/test`. It's quite impressive. Handles dates, etc.

## License

MIT
