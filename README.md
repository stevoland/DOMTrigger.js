# DOMTrigger.js

Simulate HTMLEvent and MouseEvents cross-browser

## Supported events

### HTMLEvent

* load
* unload
* abort
* error
* select
* change
* submit
* reset
* focus
* blur
* resize
* scroll

### MouseEvent

* click
* dblclick
* mousedown
* mouseup
* mouseover
* mousemove
* mouseout

## Installation

You can use with an AMD loader or vanilla javascript.

### Dowload
You can directly download the
[Development Version](https://raw.github.com/stevoland/DOMTrigger.js/master/dist/DOMTrigger.js)
or the
[Production Version](https://raw.github.com/stevoland/DOMTrigger.js/master/dist/DOMTrigger.min.js)
from the root folder

### BOWER
```shell
$ bower install DOMTrigger.js
```

### JAM
```shell
$ jam install DOMTrigger.js
```

## Integration

### AMD
```javascript
// AMD
require(['path/to/DOMTrigger.js'], function (DOMTrigger) {
  // DOMTrigger(el, 'click');
});
```

### CommonJS
```javascript
// CommonJS
var DOMTrigger = require('DOMTrigger');
```

### Vanilla JS
```html
<!-- Vanilla javascript -->
<script src="path/to/DOMTrigger.js"></script>
<script>
	console.log(DOMTrigger(el, 'click'));
</script>
```

