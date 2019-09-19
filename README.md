
# DataRep-Lab2

## Querying odetocode.com/odeteocode.jpg ##
C:\Users\G00327095\Desktop\Data Reprenstation and Querying>curl -v https://odetocode.com/odetocode.
> GET /odetocode.jpg HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*

< HTTP/1.1 200 OK
< Content-Length: 11751
< Content-Type: image/jpeg
< Last-Modified: Mon, 10 Dec 2012 02:44:57 GMT
< Accept-Ranges: bytes
< ETag: "64c77b5780d6cd1:0"
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Thu, 19 Sep 2019 12:31:52 GMT


## Querying jsmarshall.com ##
C:\Users\G00327095\Desktop\Data Reprenstation and Querying>curl -v http://www.jmarshall.com/easy/http/

GET /easy/http/ HTTP/1.1
> Host: www.jmarshall.com
> User-Agent: curl/7.64.0
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Date: Thu, 19 Sep 2019 12:39:49 GMT
< Server: Apache
< Location: https://www.jmarshall.com/easy/http/
< Content-Length: 244
< Content-Type: text/html; charset=iso-8859-1
<
<!DOCTYPE HTML PUBLIC "-//IETF//DTD HTML 2.0//EN">
<html><head>
<title>301 Moved Permanently</title>
</head><body>
<h1>Moved Permanently</h1>
<p>The document has moved <a href="https://www.jmarshall.com/easy/http/">here</a>.</p>
</body></html>
* Connection #0 to host www.jmarshall.com left intact
