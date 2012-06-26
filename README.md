
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


License
-------

Copyright 2012, Rowan Manning  
Dual licensed under the [MIT][mit] or [GPL Version 2][gpl2]
licenses.


[gpl2]: http://opensource.org/licenses/gpl-2.0.php
[mit]: http://opensource.org/licenses/mit-license.php
