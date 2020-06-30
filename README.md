# Clapboard

Clapboard: A simple utility to enhance the log information sent out in the application. The logger is initialized as

const Logger = require ('clapboard');
const Log = new Logger ();

and used as

```js
Log.info ('this is an info');
Log.warn ('this is a warning');
Log.error ('this is an error');
```

the output is as follows:

```shell
index.js 16:5 | 01/02/2020 11:42:04.429 | this is an info
index.js 17:5 | 01/02/2020 11:42:04.457 | this is a warning
index.js 18:5 | 01/02/2020 11:42:04.460 | this is an error
```
