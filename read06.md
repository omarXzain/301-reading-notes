# Node js
---------
Node.js is an open source, cross-platform runtime environment for developing server-side and networking applications. Node.js applications are written in JavaScript, and can be run within the Node.js runtime on OS X, Microsoft Windows, and Linux.

![](https://1.bp.blogspot.com/-iR_Cv_hvLaM/XwCY7_k7pMI/AAAAAAAAheM/zB69RFOkAEwauXXbP8GyKAiVwbQErqj_gCLcBGAsYHQ/w1200-h630-p-k-no-nu/run-nodejs.jpg)

.js files use Node’s built-in console module to display a message in a terminal window. Example: node hello.js

- Node.js Has Excellent Support for Modern JavaScript. Node has excellent support for ECMAScript 2015 (ES6) and beyond. As you’re only targeting one runtime (a specific version of the V8 engine), this means that you can write your JavaScript using the latest and most modern syntax. It also means that you don’t generally have to worry about compatibility issues — as you would if you were writing JavaScript that would run in different browsers.
- Node comes bundled with a package manager called npm. To check which version you have installed on your system, type npm -v.


## Node.js use cases:
-For anything from bundling your JavaScript files and dependencies into static assets, to running tests, or automatic code linting and style checking.
Lets Us Run JavaScript on the Server.

- As a scripting language to automate repetitive or error prone tasks on your PC.
Write your own command line tool, such as this Yeoman-Style generator to scaffold out new projects.
Node.js is single-threaded and event-driven, which means that everything that happens in Node is in reaction to an event.

- For example,
 when a new request comes in (one kind of event) the server will start processing it. If it then encounters a blocking I/O operation, instead of waiting for this to complete, it will register a callback before continuing to process the next event. When the I/O operation has finished (another kind of event), the server will execute the callback and continue working on the original request. Under the hood, Node uses the libuv library to implement this asynchronous (that is, non-blocking) behavior.
 
## Node.js execution model:
- Node apps pass async tasks to the event loop, along with a callback.
The event loop efficiently manages a thread pool and executes taks efficiently.
Executes each task as callback executes.

## What Node.js is suited to?
- applications that require some form of real-time interaction or collaboration — for example, chat sites, or apps such as CodeShare.
APIs where you’re handling lots of requests that are I/O driven (such as those needing to perform operations on a database).
Sites involving data streaming, as Node makes it possible to process files while they’re still being uploaded.

## Node.js advantages:
### Speed and scalability.
- You can do everything in the same language.
- It speaks JSON. JSON is probably the most important data exchange format on the Web.
JavaScript is ubiquitous.

--------------------------------------------------------------------

[Table Of Content](https://github.com/omarXzain/301-reading-notes)
