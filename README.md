# What is HTTP?
~~~
HTTP stands for Hyper Text Transfer Protocol

WWW is about communication between web clients and servers

Communication between client computers and web servers is done by sending HTTP Requests and receiving HTTP Responses.
. The most popular hypertext format is,  the Hypertext Markup Language  known as HTML.

 . The approximately 4.6 billion HTML pages, interconnected via hyperlinks, form the structure known as the World Wide Web, or Web for short.

 HTML files are transferred across the Internet using a communication protocol.
 ~~~
 # what is protocol
 ~~~
  1 A protocol is a system of rules that allow two or more devices on a computer network to transmit information.
  2 The protocol of the Web is called the Hypertext Transfer Protocol (HTTP)   is to transmit hypertext over a computer network.
 3  HTTP is quite flexible and is also used to transmit non-hypertext data as well.
  
~~~
# World Wide Web Communication
~~~
The World Wide Web is about communication between web clients and web servers.

Clients are often browsers (Chrome, Edge, Safari), but they can be any type of program or device.

Servers are most often computers in the cloud.

~~~

# HTTP Request / Response
~~~
Communication between clients and servers is done by requests and responses:

1 A client (a browser) sends an HTTP request to the web.
2 An web server receives the request.
3 The server runs an application to process the request.
4 The server returns an HTTP response (output) to the browser.
5 The client (the browser) receives the response.
~~~

# The HTTP Request Circle
~~~
A typical HTTP request / response circle:
1 The browser requests an HTML page. The server returns an HTML file.
2 The browser requests a style sheet. The server returns a CSS file.
3 The browser requests an JPG image. The server returns a JPG file.
4 The browser requests JavaScript code. The server returns a JS file
5 The browser requests data. The server returns data (in XML or JSON).
~~~
# XHR - XML Http Request
~~~
All browsers have a built-in XMLHttpRequest Object (XHR).

1  XHR is a JavaScript object that is used to transfer data between a web browser and a web server.
2 XHR is often used to request and recieve data for the purpose of modifying a web page.

The XHR Object is a Web Developers Dream, because you can
. Update a web page without reloading the page
. Request data from a server - after the page has loaded
. Receive data from a server - after the page has loaded
. Send data to a server - in the background.
~~~
# Why is HTTP useful?
~~~
1 HTTP provides a consistent, uniform interface that separates clients from servers.

2 This separation of clients can focus on presenting the user interface instead of managing resources.
3. servers can focus on managing resources instead of presenting the user interface. 
~~~

# What's an HTTP Request?
~~~
The client sends a plain-text message called an HTTP request to a server on behalf of the user.
~~~
# What's an HTTP response?
~~~
1 The server receives an HTTP request, attempts to process it, and sends a plain-text message called an HTTP response back to the client.
 Popular web servers Apache, Nginx, Node.js, and Python's built-in HTTPServer.

 Status codes are three-digit numbers that are grouped into the following categories.

 Status Code Group           Description
 	                       
  1XX	                   Request accepted, ready for the next one.
  2XX	                   Request accepted, the server's work is complete.
  3XX	                   Request accepted, but additional client work is needed.
  4XX	                   Request accepted, but there was an error on the client.
  5XX	                   Request accepted, but there was an error on the server.


 ~~~

# What's JSON?
~~~
1 JSON stands for JavaScript Object Notation

2 JSON is a lightweight format for storing and transporting data.

3 JSON is often used when data is sent from a server to a web page.

4 JSON is "self-describing" and easy to understand .

5 JSON is text, written with JavaScript object notation.

~~~
# Why use JSON?
~~~
1 Serialization is the process of translating a program's data to and from a string.

2 serialized to a string can be stored in a file, inserted into a database, or transmitted across a computer network.

~~~
# JSON.parse()
~~~
A common use of JSON is to exchange data to/from a web server.

When receiving data from a web server, the data is always a string.

Parse the data with JSON.parse(), and the data becomes a JavaScript object.
~~~
# JSON.stringify()
~~~
A common use of JSON is to exchange data to/from a web server.

When sending data to a web server, the data has to be a string.

Convert a JavaScript object into a string with JSON.stringify().

~~~

# Stringify a JavaScript Array
~~~
Example
[ "Nitu", "Nisha", "Neha", "Lila" ];
~~~

# JSON Objects
~~~
1 JSON objects are surrounded by curly braces {}.

2 JSON objects are written in key/value pairs.

3 Keys must be strings, and values must be a valid JSON data type (string, number, object, array, boolean or null).

4 Keys and values are separated by a colon.

5 Each key/value pair is separated by a comma.

Code Example
{ "name":"Nitu", "age":30, "city":null }

~~~
# JSON Arrays
~~~
Arrays in JSON are almost the same as arrays in JavaScript.

In JSON, array values must be of type string, number, object, array, boolean or null.

CODE EXample
[ "Ford", "BMW", "Fiat" ]

~~~

# What's a web API?
~~~
1 API mean application programming interface.
2 API, is a  set of protocols for interacting with a computer program.
3 A web API is a contract between a client and a server.
4 According to the contract, a web API allows a client to send specific HTTP requests to a server and the server will send specific HTTP responses back.
~~~















 










  
