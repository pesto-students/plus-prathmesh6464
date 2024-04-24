#### What are the different types of web servers, and how do they differ in terms of functionality and performance

# Server

- Sever is the machine or computer, which provides services of something like website, database, DNS etc.

# types of Web Servers:

1. EMail Server
2. Database Server
3. Cloud Server
4. Web Server
5. DNS Server
6. File Server
7. DHCP Sever
8. Web Proxy Server
9. FTP Server
10. Physical Server
11. Print Server
12. NTP Server
13. Radius Server
14. Syslog Server
15. Application Server

---

1.  Mail Server :

- EMail server is used for providing service of sending and receiving mail

2.  Database Server :

- Database server means High powered computers that store and manage data, by help of Database Server we can store, retrieve and manipulate Data.

3.  Cloud Server:

- This is a virtual server space within a cloud computing environment. It acts like a traditional physical server but exists on the internet and is managed by a cloud service provider. You can install various software programs on a cloud server, including database management software, web servers, or custom applications.

4.  Web Server :

- Web Server is used to provide web site's service to user, it provide service of front end part.

5.  DNS Server :

- DNS Server use to provide corresponding ip address of requested url.
- eg. of DMS Server - Google public DNS, Quad 9, Alternate DNS, Cloudflare, clean browsing etc.

6.  File Server :

- File Server use to store file, download and view file service.
  eg. google drive

7.  DHCP Sever :

- DHCP (Dynamic Host Configuration Protocol) is used for connecting client with host server.
- DHCP server automatically assign IP address, DNS Server to computer.

8.  Web Proxy Server :

- Web proxy server reterieves data on the internet on behalf of the user.
- Web proxy server will acts as middleman between user and server.
- user send request for web page then that request goes to the web proxy server, web proxy server hides original ip address of user and send request to server with proxy ip address, server sends back response to proxy server which is having proxy ip address then after receiving response from server proxy server sends response to original ip address user, like this proxy server provide security to user's ip address on internet.

  !["Web proxy Server Working"](./images/proxy%20server.png "Web proxy Server Working")

  - proxy server have cache database, proxy server store website on cache data, if next time also your requested same website from server then proxy server provides webpage from cache database, by doing this proxy server saves time and internet data of user and decrease traffic of server.

- data send from proxy server to server is not encrypted, so it's not secure.

9.  FTP Server :

- File transfer protocol (FTP) server is used for storing file, when user sends request for downloading file to ftp server, it receives the request and send response to the user.
- user can use ftp client for draging files from ftp server to user's client file or sending files to ftp server from user's file client.
- data which transfer from ftp server to user or user to ftp server is not encrypted hence it is not secure so new layer added of SFTP (secure file transfer protocol) for sending and receiving encrypted data.

10. Physical Server :

- A physical server, also known as a ‘bare-metal server’.
- it is a standalone computer server that is designated to a single user.
- It includes memory, processor, network connection, hard drive, and an operating system (OS) for running programs and applications.
- The resources and components of a physical server are not shared between multiple users.
- Each physical server operates independently and is responsible for running its own set of applications and services.

11. Print Server :

- print server acts as middle man between user and printer.
- if your company have 4 printer and 10 users and suppose 10 users priting the page then that user's request will go to print server then print server provide this 10 print request to printers.

12. NTP Server :

- NTP (Networking Time Protocol) is use for client and server's time sychronization.
- NTP Sever is resposible to provide correct date and time to system.

13. Radius Server :

- Radius server used for authentication, authorization and accouting.

14. Syslog Server :

- all computers amd switch logs is stored in syslog server.
- all computers connects to switch and we connect syslog to switch so we get all logs of switch plus computers.
- syslog server is monitored by cyber security persons.
- what ever user's are doing on computer that will be obeserve using syslog server.

15. Application Server :

- application server acts as the middleman between a client, like a web browser, and back-end resources like databases. It's the software that executes the behind-the-scenes logic of a web application.
- Imagine a restaurant. The client (customer) places an order with the waiter (web browser). The waiter takes the order to the kitchen (application server), which prepares the food (processes the request). The kitchen may need to get ingredients from the pantry (database) to fulfill the order. Finally, the waiter delivers the prepared food (response) back to the customer.
- web servers and application servers play essential roles in web applications. Web servers deliver the foundation, while application servers handle the complex processing and logic behind the scenes. They often work together to provide a seamless user experience for dynamic web applications.
- Web Server is Front End part and Application Server is Back End part.
