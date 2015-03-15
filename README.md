# Tooltip plugin for Chartist.js

This plugin provides quick&easy tooltips for your chartist charts. Touch support is planned soon.

Please visit http://gionkunz.github.io/chartist-js/plugins.html for more information.

## Available options and their defaults

```javascript
//None at this point
```

## Sample usage in Chartist.js

`bower install chartist-plugin-tooltip --save`

```javascript
var chart = new Chartist.Line('.ct-chart', {
  labels: [1, 2, 3, 4, 5, 6, 7],
  series: [
    [1, 5, 3, 4, 6, 2, 3],
    [2, 4, 2, 5, 4, 3, 6]
  ]
}, {
  plugins: [
    Chartist.plugins.tooltip()
  ]
});
```
