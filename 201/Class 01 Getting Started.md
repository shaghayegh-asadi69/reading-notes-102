# 201 Getting Started

[How the Web Works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works)

[Web Design and Process](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

[JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)

## Compose a short poem describing how HTTP sends data between computers

*(This was written by AI - Sorry)*  

In a digital realm, HTTP sings,  

Linking computers with data's wings.  

Client and server, they dance in sync,  

Requesting and responding, weaved in link.

  --

GET, POST, methods bring their charm,  

Fetching, creating, causing no harm.  

URLs and headers, they guide the way,  

To resources sought, where answers lay.  

--

Stateless it is, each cycle anew,  

No memories kept, each request in view.  

TCP/IP's embrace, a network's core,  

Packets divide, deliverance they pour.  
  
--

From server's realm, response takes flight,  

Status codes speak of success or plight.  

HTML, JSON, formats diverse,  

Response body holds resources' verse.  

--

Hyperlinks spark navigation's spark,  

A web of knowledge, shining in the dark.  

HTTP, a language of connection,  

Uniting computers with pure affection.  

--

In this poetic realm, HTTP thrives,  

Data flows freely, as our world derives.  

A symphony of bytes, an internet's delight,  

HTTP's rhythm, a digital light.

--

**Client-Server Model:** HTTP follows a client-server model, where one computer acts as the client, typically a web browser, and another computer acts as the server, which hosts the requested resources.

**Request-Response Cycle:** The communication between the client and server happens through a series of request-response cycles. The client sends an HTTP request to the server, and the server responds with an HTTP response.

**HTTP Methods:** HTTP defines various methods, such as GET, POST, PUT, DELETE, etc., which indicate the type of action the client wants to perform on a resource. The most common method is GET, used to retrieve a resource from the server.

**URL and Headers:** The HTTP request includes a Uniform Resource Locator (URL), which specifies the resource's location on the server. Additionally, the request can contain headers that provide additional information, such as the type of content the client can accept.

**Server Processing:** Upon receiving the request, the server processes it based on the requested resource and the specified method. It may perform actions like retrieving data from a database, executing server-side scripts, or generating a dynamic response.

**Response Codes:** After processing the request, the server sends an HTTP response back to the client. The response contains a status code indicating the outcome of the request, such as 200 OK for a successful response or 404 Not Found for a resource that could not be located.

**Response Body:** The HTTP response may also include a response body, which contains the requested resource or an error message. The response body can be in various formats, such as HTML, JSON, XML, etc., depending on the requested resource and the server's capabilities.

**Statelessness:** HTTP is stateless, meaning each request-response cycle is independent, and the server does not retain any information about past requests from the same client. To maintain state or session information, mechanisms like cookies or tokens are used.

**TCP/IP and Connection Management:** HTTP operates on top of the TCP/IP network protocol. TCP ensures reliable data delivery by dividing the data into packets, numbering them, and reassembling them at the destination. HTTP uses TCP connections, typically establishing a new connection for each request and closing it after the response.

**Hyperlinks and Navigation:** HTTP is the foundation of the World Wide Web, enabling the navigation between web pages through hyperlinks. Hyperlinks contain URLs that the browser uses to send new HTTP requests to fetch and display linked resources.

In summary, HTTP allows computers to communicate over the internet by sending requests from clients to servers and receiving responses containing the requested resources or error messages. It follows a request-response cycle, supports various methods, and operates on top of the TCP/IP protocol.

## Describe how HTML, CSS, and JS files are “parsed” in the browser  

**HTML Parsing:** When a browser encounters an HTML file, it parses it from top to bottom, constructing the Document Object Model (DOM). The browser interprets the HTML tags and creates a structured representation of the document, allowing it to understand the document's structure and content.

**CSS Parsing:** After the HTML parsing, the browser parses CSS files linked to the HTML document. It processes the CSS rules, selectors, and properties, and applies the styles to the corresponding elements in the DOM. This process is called the CSSOM (CSS Object Model) construction.

**JS Parsing:** When encountering a < script > tag or an external JavaScript file, the browser parses and executes the JavaScript code. The JavaScript engine reads the code line by line, performs syntax analysis, and creates an Abstract Syntax Tree (AST). It then executes the code, modifying the DOM and CSSOM as necessary.  

## How can you find images to add to a Website?  

**Stock Image Websites:** There are various stock image websites like Shutterstock, Unsplash, or Pixabay that offer a wide range of high-quality images for free or for purchase. You can search for specific themes or subjects to find suitable images.

**Creative Commons:** Websites like Flickr or Wikimedia Commons provide images with Creative Commons licenses. These licenses specify the usage rights, allowing you to find images that you can use and modify for your website.

**Self-Creation or Photography:** You can create your own images by using a camera or designing graphics using tools like Photoshop or Illustrator. This allows you to have unique and personalized visuals for your website.  

## How do you create a String vs a Number in JavaScript?  

String: To create a string in JavaScript, you enclose the desired text within single quotes ('') or double quotes (""). For example:  

let myString = "Hello, World!";  

Number: JavaScript recognizes numeric values without quotes as numbers. You can assign a number directly to a variable. For example:  

let myNumber = 42;  

## What is a Variable and why are they important in JavaScript?

Variables in JavaScript are used to store and manipulate data. They provide a way to reference values that can change during the program's execution.

Importance:

**Data Storage:** Variables allow you to store and retrieve data, such as strings, numbers, arrays, or objects, within a program.
**Data Manipulation:** You can perform operations, calculations, or transformations on the stored data using variables.
**Code Organization:** Variables help in organizing and managing code by providing named references to values, making the code more readable and maintainable.
**Dynamic Behavior:** JavaScript is a dynamically-typed language, and variables allow you to adapt to changing data types and values as the program runs.
**Scope and Context:** Variables have scope, defining their accessibility within different parts of the code. They also play a role in the context or environment in which the code is executed.  

In summary, variables are essential in JavaScript as they enable data storage, manipulation, code organization, and adaptability to changing values and types during program execution.
