
# DataRep-Lab2


C:\Users\G00327095\Desktop\Data Reprenstation and Querying>curl -v https://odetocode.com/odetocode.
* Expire in 0 ms for 6 (transfer 0x1afcf5a45d0)
* Expire in 1 ms for 1 (transfer 0x1afcf5a45d0)
* Expire in 1 ms for 1 (transfer 0x1afcf5a45d0)
* Expire in 2 ms for 1 (transfer 0x1afcf5a45d0)
* Expire in 3 ms for 1 (transfer 0x1afcf5a45d0)
* Expire in 5 ms for 1 (transfer 0x1afcf5a45d0)
* Expire in 6 ms for 1 (transfer 0x1afcf5a45d0)
*   Trying 168.62.48.183...
* TCP_NODELAY set
* Expire in 200 ms for 4 (transfer 0x1afcf5a45d0)
* Connected to odetocode.com (168.62.48.183) port 443 (#0)
* schannel: SSL/TLS connection with odetocode.com port 443 (step 1/3)
* schannel: checking server certificate revocation
* schannel: sending initial handshake data: sending 178 bytes...
* schannel: sent initial handshake data: sent 178 bytes
* schannel: SSL/TLS connection with odetocode.com port 443 (step 2/3)
* schannel: failed to receive handshake, need more data
* schannel: SSL/TLS connection with odetocode.com port 443 (step 2/3)
* schannel: encrypted data got 4096
* schannel: encrypted data buffer: offset 4096 length 4096
* schannel: received incomplete message, need more data
* schannel: SSL/TLS connection with odetocode.com port 443 (step 2/3)
* schannel: encrypted data got 337
* schannel: encrypted data buffer: offset 4433 length 5120
* schannel: sending next handshake data: sending 126 bytes...
* schannel: SSL/TLS connection with odetocode.com port 443 (step 2/3)
* schannel: encrypted data got 51
* schannel: encrypted data buffer: offset 51 length 5120
* schannel: SSL/TLS handshake complete
* schannel: SSL/TLS connection with odetocode.com port 443 (step 3/3)
* schannel: stored credential handle in session cache
> GET /odetocode. HTTP/1.1
> Host: odetocode.com
> User-Agent: curl/7.64.0
> Accept: */*
>
* schannel: client wants to read 102400 bytes
* schannel: encdata_buffer resized 103424
* schannel: encrypted data buffer: offset 0 length 103424
* schannel: encrypted data got 409
* schannel: encrypted data buffer: offset 409 length 103424
* schannel: decrypted data length: 380
* schannel: decrypted data added: 380
* schannel: decrypted data cached: offset 380 length 102400
* schannel: encrypted data buffer: offset 0 length 103424
* schannel: decrypted data buffer: offset 380 length 102400
* schannel: schannel_recv cleanup
* schannel: decrypted data returned 380
* schannel: decrypted data buffer: offset 0 length 102400
< HTTP/1.1 302 Found
< Content-Length: 157
< Content-Type: text/html; charset=utf-8
< Location: /Error/Missing?aspxerrorpath=/odetocode.
< Server: Microsoft-IIS/10.0
< X-Powered-By: ASP.NET
< Date: Thu, 19 Sep 2019 12:25:03 GMT
<
<html><head><title>Object moved</title></head><body>
<h2>Object moved to <a href="/Error/Missing?aspxerrorpath=/odetocode.">here</a>.</h2>
</body></html>
* Connection #0 to host odetocode.com left intact
