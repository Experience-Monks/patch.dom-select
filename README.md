## dom-select

## :warning: DEPRECATED :warning:

This module exists to fix some [kik/Azer](http://blog.npmjs.org/post/141577284765/kik-left-pad-and-npm) issues. New projects should not depend on this.

---

DOM Selector Library [With Fallback Support](http://npmjs.org/qwery)

```js
var select = require('select-dom')

select('.foo a[href=bar]')
// => [Element]

select.all('.foo a[href=bar]')
// => [[Element], [Element], [Element]]
```