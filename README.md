DevSheets
====

**Goal:** take the idea of _"spreadsheet as general-purpose prototyping tool"_ and apply it to markdown files.

Example
----

- declaring and using variables

~~~
# Pizza Night

` ` `
formatDollars = require('format-dollars')

numPizzas = 3
numPeople = 7
pizzaCost = 12.00
` ` `

> Everyone needs to chip in `formatDollars(Math.ceil(numPizzas * pizzaCost) / numPeople))`.
~~~

will be rendered as:

```
# Pizza Night

Everyone needs to chip in `$5.15`
```

License
----

MIT
