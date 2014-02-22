angular-online-status
=====================

An angular directive module that sets a rootscope variable of ``online`` to either true or false depending on your current network status.

Demo
----

To see a demo of this site in action, go to [the github page](http://infomofo.github.io/angular-online-status/). You can toggle your computer's network status to see how the page changes.

Instructions
------------

### [Optional] Install the chrome module using bower

Install using bower install

    bower install infomofo/angular-online-status

Add the following script import

```html
    <script src="bower_components/angular-online-status/angular-online-status.js"></script>
```

### Import the module

```javascript
angular.module('myapp',['online-status']);
```

### How it works

This listens to your navigator.online variable and sets a rootscope variable accordingly so it can be accessed and referenced by angular expressions.
