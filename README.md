#  What Happens When You Click www.google.com?

This document explains the technical steps involved when a user clicks on a URL like `www.google.com` in a web browser. It breaks down the process into understandable layers, showing the behind-the-scenes flow of how web pages are delivered to your screen.

###  Client-Server Architecture
A web browser (client) sends a request to a server, which responds with the necessary resources (like HTML, images, etc.). Every website is hosted on a server with a unique IP address.

###  DNS (Domain Name System)
DNS translates the human-readable address (`www.google.com`) into a machine-readable IP address (like `108.177.122.139`). The browser first checks its cache before querying DNS servers.

###  TCP/IP Model
The data is transmitted over the internet using the TCP/IP model which has four layers:
- **Application Layer** – Handles protocols like HTTP, HTTPS.
- **Transport Layer** – Breaks data into packets using TCP/UDP.
- **Internet Layer** – Assigns IP addresses to packets.
- **Data Link Layer** – Delivers packets via WiFi or Ethernet.

A **3-way handshake** (SYN, SYN-ACK, ACK) is used to establish a secure connection between client and server.

###  HTTPS Request & Response
- **Request**: The browser sends a secure HTTP request using SSL encryption.
- **Response**: The server replies with a status code, headers, and the requested web page content.

### Rendering
The browser then processes (renders) the response — converting HTML, CSS, and JavaScript into a visual, interactive web page.


