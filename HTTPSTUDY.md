# HTTP STUDY


## 1. HTTP: Basic of the WEB

1. HTTP 
2. URL resource
3. HTTP message
4. Connection Management - common misunderstanding etc.



## HTTP Getting started 

* HTTP: Hypertext Transfer Protocol
> Languages for Internet World.
<p>&nbsp;</p>

* HTTP: Melti Media Delivery 
> HTTP using reliable data transfer protocol.
<p>&nbsp;</p>

* Web client and server
    * Web contents exist in web server. Normally we call it as HTTP server, because communicate via HTTP Protocol.
    * Basic mechanism is client request the HTTP Object to Server (HTTP request) , and server send request Data via HTTP  to client (HTTP response).
> Web client is web browser like chrome, firefox etc.
<p>&nbsp;</p>

### 1.3Resource
> Web server do manage the web resource and provide it. Resource is all kinds of the file. (can be program as well.)
<p>&nbsp;</p>
###1.3.1Media Type


> Web server attach the MIME type to all the HTTP object data. MIME means "Multipurpose Internet Mail Extensions" <br />


* HTML: text/html
* plain ASCII: text/plain
* JPEG: image/jpeg
* GIF: image/gif
* Apple quick time video: video/quicktime
* MS ppt: application/vnd.ms-powerpoint

1.3.2 URI "uniform resourse identifier
> Each web server resource have their own name, so client can point out specific resource. the name of the resource is URI, and It's like postbox of Internet. URI hava two kinds of type URL and URN. <br />

Ex. http://www.joes-hardware.com/specials/saw-blade.gif<br />
* http:// > Use HTTP protocl
* www.joes-hardware.com > move to ~.com
* /specials/saw-blade.gif > get this resource <br />

1.3.3 URL "Uniform resource locator"
> URL devided by three part. 1. Protocol, 2. Address, 3. resource
> Most of URI is URL in todays. <br />

1.3.4 URN "Uniform resource name" <br />

### 1.4 Transaction
> HTTP transaction are consist of request message and response message.<br />
> Request: GET /specials/saw-blade.gif HTTP/1.0 Host: www.joes-hardware.com<br />
> Response: HTTP/1.0 200 OK Content-type: image/gif Content-length: 8572 >>> "includes result of transation"<br />

1.4.1 Method <br />
HTPP request message have each of method. and this method say to server that what server should do. 
* GET: send requested resource from server to client
* PUT: save the data which sent by client as specified resource.
* DELETE: Delete the resource from server
* POST: send the client data server gateway application.
* HEAD: In response, just send header part


1.4.2 Status Code

all the reponse message sending with status code together. Status code is three digit that inform to client  about  the request was successful or need further action.

* 200: All right! the reponse came out correctly.
* 302: Re reuest it. or ask different location to get resource.
* 404: Can't found resource.

> Normally, HTTP send the "reason phrase" together. like below
> 200 OK / 200 Document attached / 200 Success / 200 All's cool, dude

1.4.3 Web page can consist of many objects
> Web page is collection of resources.

### 1.5 Message

> HTTP message use simple text struct.
> consist of three part 

* Start-line
* Header-Message
* Body-Message


### TCP connection

> TCP is Transmission Control Protocol.


1.6.1 TCP/IP

HTTP is Application layer protocol. and they doesn't care network communication specifiactions. 
this work leave to TCP/IP 

TCP provide belows
* Send Data without error
* Send the Ordered Data
* Send the unfragemented Data
* HTTP>TCP>IP>Link interface for Network>Pysical Network Hardware


1.6.2 Connection, IP address, Port Number

> Before send message from client to Server, TAP/IP connection required.
> TCP connection is like call to another office's someone.

How to know IP address and Port Number? 

URL informed that. 

http://www.netscape.com is http://207.200.83.29:80 

### 1.7 Protocol Version

* 0.9: 1991
* 1.0: started to use widely 
* 1.0+: 1990 mid "Keep alive" + proxy
* 1.1: 1990 later
* 2.0: 2021 now we are using ! 


### 1.8 Web Components

* Proxy: Middleman between client and server
* Cache: Storage near client that store Frequently visited Web pages
* Gate Way: Web server connected with other application
* Turnel: Special Proxy which is only send HTTP commuication.
* Agent: "Semi-intelligent" web client that make  HTTP request automatically.


1.8.1 Proxy

> transmitt all the HTTP request from clien to server. using for Security, and filtering.


1.8.2 Cache

> HTTP proxy server store copies, and client can get it in short time. 


1.8.3  Gateway 
> 'HTTP client' <-HTTP-> 'HTTP/FTP Gateway' <-FTP-> 'FTP Server'

1.8.4 Turnnel 


### 1.9 The end of the start

### 1.10 reference

A lot..





