# bootstrap-ie8
Bootstrap projects sometimes does not work with IE8 well. You may need these good development tools to fix your projects under ie8. Also these may make your life easier for IE8 development.

### What included
[es5-shim.js](https://github.com/es-shims/es5-shim)

"ECMAScript 5 compatibility shims for legacy JavaScript engines."

You need this because some jQuery plugins may use some code cannot be supported by IE8 legacy engine.

[console-polyfill](https://github.com/paulmillr/console-polyfill)

"Browser console polyfill. Makes it safe to do console.log()-s etc always."

If you want to use console.log() for debug purpose.

[HTML5 shiv](https://github.com/afarkas/html5shiv)

"Enable use of HTML5 sectioning elements in legacy Internet Explorer."

[Respond.js](https://github.com/scottjehl/Respond)

"A fast & lightweight polyfill for min/max-width CSS3 Media Queries (for IE 6-8, and more)"

If you need Bootstrap works properly under IE8

### bower
If you use [bower](http://bower.io/), you can just take bower.json and run
bower install

to get the least the dependencies.

### Example
Please check index.html.