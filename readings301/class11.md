# EJS #

## What is EJS? ##
- EJS stand for Embedded JavaScript templates is simple and effective template engine for JavaScript. EJS is the simple template which allows developers to create the HTML page with plain JavaScript. Ejs provide fast compilation and rendering and include both server and browser support.
- The general idea is to send your content to the browser delivered as js, in whatever syntax your chosen js templating engine dictates, once loaded (probably on DOMContentLoaded?) at which point the js template engine will take over and generate the HTML client side.
- EJS make your server less a complicated server side and end up pushing rendering to the client.


## EJS Options ##

- cache Compiled functions are cached, requires filename

- filename Used by cache to key caches, and for includes

- context Function execution context

- compileDebug When false no debug instrumentation is compiled

- client Returns standalone compiled function

- delimiter Character to use with angle brackets for open/close

- debug Output generated function body

- localsName Name to use for the object storing local variables when not using with Defaults to locals

- rmWhitespace Remove all safe-to-remove whitespace, including leading and trailing whitespace. It also enables a safer version of -%> line slurping for all scriptlet tags (it does not strip new lines of tags in the middle of a line).

- escape The escaping function used with <%= construct. It is used in rendering and is .toString()ed in the generation of client functions. (By default escapes XML).

- outputFunctionName Set to a string (e.g., 'echo' or 'print') for a function to print output inside scriptlet tags.

- async When true, EJS will use an async function for rendering. (Depends on async/await support in the JS runtime.



