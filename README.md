jsDump
======

`jsDump.parse(object)` returns a string containing a human-readable representation of `object`

jsDump is like [Mozilla’s toSource()](https://developer.mozilla.org/en/Core_JavaScript_1.5_Reference/Objects/Function/toSource),
but cross-browser.

[jsDump](http://flesler.blogspot.com/2008/05/jsdump-pretty-dump-of-any-javascript.html)
was originally developed by Ariel Flesler.
This fork based on [version 1.0.0](http://code.google.com/p/flesler-projects/source/browse/trunk/javascript/JSDump/).


Analogs
-------

  - `inspect()` from [Node.js sys module](http://nodejs.org/api.html#_system_module)
  - `repr()` from Narwhal’s util module
  - `console._source_of()` from [Console.js](http://github.com/NV/console.js/)

NPM
---

can be installed with:
    npm install jsDump
and used in node with:
    var jsDump = require("jsDump");
    jsDump.parse(foo);

[Tests](http://nv.github.com/jsDump/tests/)
-----
In the browser:

  1. `git submodule update --init`
  2. open `tests/index.html`

Or from command line:

    $ narwhal tests/*_test.js


Contribution
------------
Use [jQuery coding style](http://docs.jquery.com/UI_Developer_Guide#Coding_Style).
Basically, use tabs instead of spaces.
