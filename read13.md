# Sending form data
Once the form data has been validated on the client-side, it is okay to submit the form. And, since we covered validation in the previous article, we're ready to submit! This article looks at what happens when a user submits a form.

## Client/Server Architecture
- Client/server architecture is a computing model in which multiple components work in strictly defined roles to communicate. The server hosts, delivers and manages most of the resources and services to be consumed by the client. This type of shared resources architecture has one or more client computers connected to a central server over a network or internet connection.

![](https://www.tutorialspoint.com/data_communication_computer_network/images/client_server.jpg)

- GET means the browser will add the form contents to the end of the URL. This offers a number oadvantages for simple forms. It allows the browser to cache the results of the form submission, and it alsallows the user to bookmark the page once the form has been submitted. As such, GET is generally used fosimple forms where security is not a concern.

## The GET method
- The GET method is the method used by the browser to ask the server to send back a given resource: "Hey server, I want to get this resource." In this case, the browser sends an empty body. Because the body is empty, if a form is sent using this method the data sent to the server is appended to the URL.

## The POST method
- The POST method is a little different. It's the method the browser uses to talk to the server when asking for a response that takes into account the data provided in the body of the HTTP request: "Hey server, take a look at this data and send me back an appropriate result." If a form is sent using this method, the data is appended to the body of the HTTP request.

![](https://miro.medium.com/max/853/1*8-fT6K1o6nHiBRxKppcqOg.png)

## Viewing HTTP requests
- HTTP requests are never displayed to the user (if you want to see them, you need to use tools such as the Firefox Network Monitor or the Chrome Developer Tools). As an example, your form data will be shown as follows in the Chrome Network tab. After submitting the form:

- Open the developer tools.
1) Select "Network"
2) Select "All"
3) Select "foo.com" in the "Name" tab
4) Select "Headers"


## Security issues
- Each time you send data to a server, you need to consider security. HTML forms are by far the most common server attack vectors (places where attacks can occur). The problems never come from the HTML forms themselves — they come from how the server handles data.


------------------------------------------------------------------------------------


[Table Of Content](https://github.com/omarXzain/301-reading-notes)
