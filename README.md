ng-focus
========

An AngularJS directive to place focus on the element. It is applied to when the expression it binds to evaluates to true.

## Implementation steps

### Step 1: Install ng-focus

Install using Bower:

```
bower install ng-focus
```

Include ng-focus.js in your app.

### Step 2: Load the ng-focus module

```js
angular.module('myApp', ['ng-focus']);
```

### Step 3: Add the focus directive to a DOM element

```html
<!-- false: focus disabled -->
<input focus=false>
<!-- true: focus enabled -->
<input focus=true>
```

## Licence

MIT