
# DataRep-Lab2

## Querying odetocode.com/odeteocode.jpg// ##
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


## Querying jsmarshall.com// ##
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

## Querying www.duckduckgo.com ##
 GET / HTTP/1.1
> Host: www.duckduckgo.com
> User-Agent: curl/7.64.0
> Accept: */*
>
< HTTP/1.1 301 Moved Permanently
< Server: nginx
< Date: Thu, 19 Sep 2019 12:48:16 GMT
< Content-Type: text/html
< Content-Length: 162
< Connection: keep-alive
< Location: https://duckduckgo.com/
< Strict-Transport-Security: max-age=31536000
< Expires: Fri, 18 Sep 2020 12:48:16 GMT
< Cache-Control: max-age=31536000
<
<html>
<head><title>301 Moved Permanently</title></head>
<body>
<center><h1>301 Moved Permanently</h1></center>
<hr><center>nginx</center>
</body>
</html>
* Connection #0 to host www.duckduckgo.com left intact


## Querying Science/computer-science On DuckDuckGo.com ##

curl -o science.txt https://duckduckgo.com/?q=science&t=h_&ia=web
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 12832    0 12832    0     0   208k      0 --:--:-- --:--:-- --:--:--  208k
't' is not recognized as an internal or external command,
operable program or batch file.
'ia' is not recognized as an internal or external command,
operable program or batch file.

curl -o computer-science.txt https://duckduckgo.com/?q=computer-science&t=h_&ia=web
  % Total    % Received % Xferd  Average Speed   Time    Time     Time  Current
                                 Dload  Upload   Total   Spent    Left  Speed
100 14626    0 14626    0     0   117k      0 --:--:-- --:--:-- --:--:--  117k
't' is not recognized as an internal or external command,
operable program or batch file.
'ia' is not recognized as an internal or external command,
operable program or batch file.
