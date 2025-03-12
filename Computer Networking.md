TODO: Add description

* Introduction
	* Network Programming and C
	* OSI Layer Model
	* TCP/IP Model
	* Internet Protocols
	* IPv4 and IPv6
	* Domain Name System
	* Routing
	* Network Address Translation
	* Client-Server Model
	* Listing IP Addresses in C
* Socket Programming
	* Sockets Overview
	* Network Header Files
	* Connection and Connectionless
	* TCP and UDP Protocols
	* Socket Functions
	* Building a Web Server
* TCP Connections
	* Configuring with `getaddrinfo()`
	* Initiating with `connect()`
	* Detecting Terminal Input
	* Multiplexing with `fork()`
	* Multiplexing with `select()`
	* Detecting Peer Disconnects
	* Implementing a microservice
	* TCP Stream Protocol
	* Blocking on `send()`
* UDP Connections
	* Differences between TCP and UDP
	* Using `sendto()` and `recvfrom()`
	* UDP Sockets and `connect()`
	* Implementing a UDP Server
	* Using `select()` with UDP Socket
* Hostnames & DNS
	* Breaking down DNS
	* DNS Record Types
	* Using `getaddrinfo()` and `getnameinfo()`
	* DNS Query Data Structures
	* DNS UDP Protocol
	* DNS TCP Fallback
	* Writing a DNS Query Program
* Web Client
	* HTTP Message Format
	* HTTP Request Types
	* Common HTTP Headers
	* HTTP Response Code
	* HTTP Message Parsing
	* Implementing an HTTP Client
	* Encoding Form Data (POST)
	* HTTP File Uploads
* Web Server
	* Accepting and Buffering Connections
	* Parsing an HTTP Request Line
	* Formatting an HTTP Response
	* Serving Files
	* Security Practices
* SMTP Protocol
	* How SMTP Servers Work
	* Determining a Mail Server
	* Using SMTP
	* Email Encoding
	* Spam Blocking Pitfalls
* HTTPS & OpenSSL
	* Information about HTTPS
	* Types of Encryption Ciphers
	* Authenticating Servers
	* Basic OpenSSL Usage
	* Creating a HTTPS Client
* Secure Web Server
	* HTTPS Overview and Certificates
	* HTTPS Server Setup with OpenSSL
	* Accepting HTTPS Connections
	* Common Pitfalls
	* OpenSSL Alternatives
	* Direct TLS Termination
* SSH with `libssh`
	* SSH Protocol Overview
	* The `libssh` Library
	* Establishing a Connection
	* SSH Authentication Methods
	* Executing a Remote Command
	* File Transfer
* Network Security
	* Checking Host Reachability
	* Displaying a Connection Route
	* Showing Open Ports
	* Listing Open Connections
	* Packet Sniffing
	* Firewalls and Packet Filtering
* Secure Socket Programming
	* Error Handling and Error Descriptions
	* TCP Handshakes and Orderly Release
	* Timeout on `connect()`
	* Preventing TCP Deadlocks
	* TCP Flow Control
	* Avoiding Address-In-Use Errors
	* Preventing `SIGPIPE` Crashes
	* Multiplexing Limitations of `select()`
* Web Programming and IoT
	* Defining IoT
	* Connectivity Types
	* Bandwidth Considerations
	* Controller Types
	* Ethics of IoT
	* Security of IoT