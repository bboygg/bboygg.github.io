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

#### 1.3Resource
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









