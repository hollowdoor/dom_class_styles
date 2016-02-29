dom-class-styles
================

Install
-------

`npm install --save dom-class-styles`

Example
-------

```javascript
var classStyles = require('dom-class-styles');
var styles = classStyles('class-name');
console.log(styles.border);
```

About
-----

Get the styles of a class from a style sheet in the current HTML document. If there is more than one CSS document in the page the furthest one down in the HTML will be used.
