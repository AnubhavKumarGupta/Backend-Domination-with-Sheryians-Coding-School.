<p align="center">
  <img src="https://img.shields.io/github/stars/AbhishekShrivastav73/Backend-Domination-with-Sheryians-Coding-School.?style=flat-square" alt="GitHub stars">
  <img src="https://img.shields.io/github/forks/AbhishekShrivastav73/Backend-Domination-with-Sheryians-Coding-School.?style=flat-square" alt="GitHub forks">
  <img src="https://img.shields.io/github/issues/AbhishekShrivastav73/Backend-Domination-with-Sheryians-Coding-School.?style=flat-square" alt="GitHub issues">
</p>

# Backend-Domination-With-Sheryians-Coding-Schools
Getting Start with Back-End Journey with Sheryians Coding Schools (Back-End Domination : Create Efficient Back-End.).

# Javascript WarmUp
In this Section, we'll introduce you to the fascinating world of JavaScript, the language that powers much of the web. You'll learn the basics of JavaScript syntax, data types, and how to write your first lines of code. Get ready to dive into the exciting world of web development with JavaScript as your guide!

### Basics : 
Break down of the core concepts of JavaScript in simple terms. You'll learn everything from variables and data types to loops and functions. By the end of this module, you'll have a solid understanding of the basics of JavaScript, setting you up for success as you dive deeper into web development. Let's unleash the power of JavaScript together!

### Asynchronous Javascript : 
In this lesson, we'll introduce you to the concept of asynchronous programming in JavaScript. We'll explore why it's important and how it can make your programs more efficient. Get ready to learn about asynchronous functions, callbacks, promises, and async/await syntax. By understanding asynchronous JavaScript, you'll be able to create dynamic and responsive web applications. Let's dive in and start mastering asynchronous programming!

# How Internet Works.

## Basics 

In this lesson, we'll take a deep dive into the fascinating world of the internet. We'll explore how data travels across the globe, from your device to servers and back again. You'll learn about protocols like TCP/IP, DNS, and HTTP, which form the backbone of the internet. By the end of this lesson, you'll have a clear understanding of the infrastructure that powers the internet and how information is transmitted between devices. Let's unravel the mysteries of the internet together!

### How Internet Works ? 
The internet connects devices worldwide through a network of cables and servers. When you request a webpage, your device sends data to your <mark>Internet Service Provider (ISP) </mark>, which then routes it to the server hosting the page. The server sends the data back, and your device displays the webpage. This happens quickly, enabling global communication.
### Understanding IP Address ?
An IP address is a unique number assigned to each device on the internet. It works like a home address, telling other devices where to send data, such as websites or emails. Each device needs an IP address to communicate and share information online.(IP is provided by the ISP)

### What is MAC Address ? 
A MAC address is a unique identifier assigned to a device's network hardware, like a Wi-Fi card or Ethernet adapter. Think of it as a serial number for your device's internet connection hardware. When devices communicate within a local network, the MAC address helps ensure that the information goes to the correct device. Unlike IP addresses, which can change, MAC addresses are usually fixed and assigned by the manufacturer.

#### IP addresses are used to route the data across networks globally, while MAC addresses are used to ensure the data reaches the correct device within a local network. This combination allows data to travel from your laptop to your friend's computer accurately.

### Understanding VPN 
A VPN, or Virtual Private Network, creates a secure connection between your device and the internet. It works by routing your internet traffic through a private server, hiding your real IP address and encrypting your data. This makes your online activities more private and secure, protecting you from hackers and allowing you to access content that might be restricted in your location. Essentially, a VPN acts like a secure tunnel for your internet traffic.

### Servers 
A server is a powerful computer that provides services and resources to other computers, called clients, over a network. Servers store and manage data, run applications, and handle requests from clients. For example, when you visit a website, your computer sends a request to the server hosting that site. The server processes the request and sends the webpage back to your computer. Servers can manage many tasks simultaneously and are essential for running websites, email, online games, and many other services on the internet.

## A server is a computer system connected to the internet, programmed to process, store, and provide data to other computers.

## More Information 

In this lesson, we'll simplify what reverse proxies are and how they work. Think of a reverse proxy as a shield that stands between the internet and your web servers, protecting them from direct access. We'll explore how reverse proxies enhance security, improve performance, and streamline network traffic. By the end of this lesson, you'll have a clear understanding of how reverse proxies can benefit your online infrastructure. Let's dive in and uncover the secrets of reverse proxies together!

### Proxy
A proxy server acts as an intermediary between your device and the internet. When you use a proxy, your internet requests go to the proxy server first, which then forwards them to the target website. The website's response goes back to the proxy, which sends it to you. This process hides your IP address, making your online activity more private and allowing you to access blocked or restricted content. Proxies can also improve security and manage network traffic.

### Reverse Proxy 
A reverse proxy sits between the internet and a server, acting as a middleman for incoming requests. When someone tries to access a website, the reverse proxy receives the request first, then forwards it to the appropriate server. It then sends the server's response back to the user. This helps balance the load among multiple servers, improves security by hiding the server's identity, and can cache content to speed up access for users. Essentially, a reverse proxy manages and protects server resources while providing efficient user access.

### Internet Protocols 
Internet protocols are rules and standards that allow devices to communicate over the internet. They ensure data is sent and received correctly between devices. Common protocols include HTTP for accessing websites, FTP for transferring files, and TCP/IP, which ensures data is properly routed and reaches its destination. These protocols work together to enable seamless and reliable communication across the global internet.

### ISP (Internet Service Provider)
An ISP, or Internet Service Provider, is a company that provides you with access to the internet. When you connect to the internet from home or on your mobile device, your ISP routes your data to and from websites and online services. They manage your internet connection, handle network traffic, and offer various services like email and web hosting. Without an ISP, you wouldn't be able to connect to the internet.

### TCP/IP
TCP/IP stands for Transmission Control Protocol/Internet Protocol, and it is the foundation of internet communication. TCP ensures that data is sent and received accurately by breaking it into packets and reassembling it at the destination. IP handles addressing and routing these packets to the correct destination. Together, TCP/IP makes sure that data travels efficiently and reliably between devices across networks, enabling everything from web browsing to email to online streaming.

### UDP -(User Datagram Protocol)
UDP, or User Datagram Protocol, is a communication method used on the internet. Unlike TCP, UDP sends data without establishing a connection or checking for errors. This makes it faster but less reliable, as data packets can be lost or arrive out of order. UDP is ideal for applications where speed is crucial and some data loss is acceptable, like live video streaming, online gaming, and voice calls.

### HTTP (Hypertext Transfer Protocol)
HTTP, or Hypertext Transfer Protocol, is the foundation of data communication on the web. It defines how messages are formatted and transmitted, and how web servers and browsers should respond to various commands. When you type a website address into your browser, HTTP is the protocol used to request the web page from the server, and it also defines how the server sends the web page back to your browser.

## Everthing about Node JS
Node.js is a runtime environment that allows you to run JavaScript on the server side, outside of a web browser. It's used to build fast and scalable server-side applications, thanks to its non-blocking, event-driven architecture. This makes it ideal for real-time applications like chat apps and online gaming.

### Non-blocking I/O
Non-blocking I/O is a way of handling input and output operations without making the program wait. Instead of stopping to wait for data to be read or written, the program can continue doing other tasks. When the data is ready, the program gets a notification and processes it. This approach helps make programs faster and more efficient, especially when dealing with many tasks at once.

### Libuv in NodeJs
##### Non-blocking or async nature of the Node js is just because of the Libuv
Libuv is a key component in Node.js that handles the event loop and manages asynchronous operations. It provides the foundation for non-blocking I/O by abstracting the underlying operating system's asynchronous features, such as file system operations, networking, and timers. When Node.js performs an asynchronous task, like reading a file, Libuv takes care of running the task in the background and notifies Node.js when the task is complete. This allows Node.js to keep processing other tasks without waiting, making it efficient and fast for handling multiple operations simultaneously.

### Node JS Single Threaded Architecture 
Node.js is single-threaded, which means it uses a single thread to handle all tasks. However, it can handle many tasks at once because of its event-driven, non-blocking nature. Here's an easy-to-understand explanation with an example:

Imagine you are a waiter in a busy restaurant, and you are the only one taking orders (the single thread). Instead of waiting by each table until the food is ready, you quickly take an order from one table, pass it to the kitchen (non-blocking), and move on to the next table to take another order. While you’re taking more orders, the kitchen (event loop) is preparing the food. When the food is ready, the kitchen notifies you, and you deliver it to the table (callback function).

In this way, even though you are just one person (single-threaded), you efficiently handle many tables (tasks) at the same time. Node.js works similarly by using the event loop to manage multiple operations without waiting for each one to finish before starting the next.

# NPM 
NPM, or Node Package Manager, is a tool that comes with Node.js. It helps you easily install, share, and manage packages (reusable pieces of code) that other developers have written. With NPM, you can quickly add new features to your project without writing everything from scratch. It also helps you manage project dependencies and keep your code organized.

## File Handling in Node JS

File handling in Node.js involves reading from, writing to, and managing files on your system. Node.js provides the `fs` (file system) module to perform these operations. Here’s a brief overview:

1. **Reading Files**: You can read files using methods like `fs.readFile` for asynchronous reading and `fs.readFileSync` for synchronous reading.
   ```javascript
   const fs = require('fs');
   fs.readFile('example.txt', 'utf8', (err, data) => {
       if (err) throw err;
       console.log(data);
   });
   ```

2. **Writing Files**: You can write to files using methods like `fs.writeFile` for asynchronous writing and `fs.writeFileSync` for synchronous writing.
   ```javascript
   fs.writeFile('example.txt', 'Hello, World!', (err) => {
       if (err) throw err;
       console.log('File has been written');
   });
   ```

3. **Appending Files**: You can add content to an existing file using `fs.appendFile` for asynchronous appending.
   ```javascript
   fs.appendFile('example.txt', ' More content', (err) => {
       if (err) throw err;
       console.log('Content added');
   });
   ```

4. **Deleting Files**: You can delete files using `fs.unlink`.
   ```javascript
   fs.unlink('example.txt', (err) => {
       if (err) throw err;
       console.log('File deleted');
   });
   ```

5. **Other Operations**: The `fs` module also allows you to rename files, read directories, and perform many other file-related operations.

By using these methods, Node.js allows you to handle files efficiently in both synchronous and asynchronous ways.

<hr/>

Handling folders (directories) in Node.js involves operations like creating, reading, renaming, and deleting directories. The `fs` (file system) module in Node.js provides methods for these operations:

1. **Creating Directories**: You can create directories using `fs.mkdir`.
   ```javascript
   const fs = require('fs');
   fs.mkdir('newFolder', (err) => {
       if (err) throw err;
       console.log('Directory created');
   });
   ```

2. **Reading Directories**: You can read the contents of a directory using `fs.readdir`.
   ```javascript
   fs.readdir('.', (err, files) => {
       if (err) throw err;
       console.log('Files in the current directory:', files);
   });
   ```

3. **Renaming Directories**: You can rename directories using `fs.rename`.
   ```javascript
   fs.rename('newFolder', 'renamedFolder', (err) => {
       if (err) throw err;
       console.log('Directory renamed');
   });
   ```

4. **Deleting Directories**: You can delete directories using `fs.rmdir`.
   ```javascript
   fs.rmdir('renamedFolder', (err) => {
       if (err) throw err;
       console.log('Directory deleted');
   });
   ```

These methods allow you to manage directories in your file system, enabling you to organize and manipulate folder structures as needed within your Node.js applications.
