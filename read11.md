# About EJS
-----------
- Where is EJS used? EJS is used in node.js when working with the Express framework as a templating engine to help render JavaScript code on the client-side.

- EJS simply stands for Embedded JavaScript templates, and we can use it both server-side or client-side.

- Jade comes as the view engine for Express by default but Jade syntax can be overly complex for many use cases. EJS is one alternative does that job well and is very easy to set up. Let’s take a look at how we can create a simple application and use EJS to include repeatable parts of our site (partials) and pass data to our views.

- package.json will hold our Node application information and the dependencies we need (express and EJS). server.js will hold our Express server setup, configuration.

- <% 'Scriptlet' tag, for control-flow, no output

- <%= Outputs the value into the template (HTML escaped)

- <%- Outputs the unescaped value into the template

![](https://miro.medium.com/max/720/1*DG4VA127mu4Fx2TrRIzskw.jpeg)

## Tags
- <% 'Scriptlet' tag, for control-flow, no output
- <%_ ‘Whitespace Slurping’ Scriptlet tag, strips all whitespace before it
- <%= Outputs the value into the template (HTML escaped)
- <%- Outputs the unescaped value into the template
- <%# Comment tag, no execution, no output
- <%% Outputs a literal '<%'
- %> Plain ending tag
- %> Trim-mode ('newline slurp') tag, trims following newline
- %> ‘Whitespace Slurping’ ending tag, removes all whitespace after it

- You can use simple JS statements with EJS, such as:
---------------------------------------------
## How To Use API:

- Here's how to determine which of those options to use:
- If the request requires authorization (such as a request for an individual's private data), then the application must provide an OAuth 2.0 token with the request. -The - application may also provide the API key, but it doesn't have to.
If the request doesn't require authorization (such as a request for public data), then the application must provide either the API key or an OAuth 2.0 token, or both—whatever option is most convenient for you.
Authorizing requests with OAuth 2.0:

---------------------------------------------


[Table Of Content](https://github.com/omarXzain/301-reading-notes)
