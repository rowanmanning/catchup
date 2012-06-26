
Catchup
=======

Catchup is a small set of CSS3 and CSS 2.1 compatibility mixins
for LESS. Use catch-up to polyfill features for older browsers
and prevent code duplication by abstracting away vendor
prefixes.


Using Catchup
-------------

Catchup can be `@import`ed like any of your own LESS files. The
library isn't useful by itself, there are no selectors exposed,
you can just include `css21.less` and/or `css3.less` in your
code to start using the mixins:

    @import 'lib/css21';
    @import 'lib/css3';


Testing Catchup
---------------

Catchup is tested with HTML files in browser at the moment. In
order to test, you'll need to compile the Catchup test LESS
files into CSS. You'll need to install [Node.js][node],
[npm][npm] and the LESS command line utility:

    npm install -g less

Then you can run the following from within the project directory
to compile the test CSS:

    lessc test/catchup.less > test/catchup.css

Now you can open `test/catchup.html` in browser to make sure
everything works.


License
-------

Copyright 2012, Rowan Manning  
Dual licensed under the [MIT][mit] or [GPL Version 2][gpl2]
licenses.


[node]: http://nodejs.org/
[npm]: http://npmjs.org/
[gpl2]: http://opensource.org/licenses/gpl-2.0.php
[mit]: http://opensource.org/licenses/mit-license.php
