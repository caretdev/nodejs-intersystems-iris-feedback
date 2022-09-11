# intersystems-iris

NodeJS Support for InterSystems IRIS. At the moment only SQL queries supported.

## Installing intersystems-iris

Installing intersystems-iris requires a node 14

You can install the project with npm. In the project directory, run:

```sh
npm install intersystems-iris
```

This fully installs the project, including installing any dependencies.

## Exploring intersystems-iris

After building intersystems-iris, you can explore its exports at the Node REPL:

```sh
$ npm install intersystems-iris
$ node
> const iris = require('intersytems-iris')
> const db = new iris('localhost', 1972, 'USER', '_SYSTEM', 'SYS')
> const queryResult = db.sql('SELECT * FROM Sample.Person')
```
