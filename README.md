# NodeJSBootCamp-ProxyServer_0
Prework- Introduction to NodeJS | CodePath 

My application is complete and I almost spent 3 hours for setting up the environment and completing the proxu server project.

Completed Task List:

Successful Echo Requests
Successful Proxy Requests
Included CLI
log requests to STDOUT
Here is the walkthorugh gif attached. I have built the index.js step by step according to video. I have displayed the end result task.

Starting the server:
 nodemon --exec babel-node -- index.js

Request Sent to Proxy Server:
curl -v http://127.0.0.1:8001 -H 'x-asdf: foo' -d 'asdf'

Response from Server:
<p><\n>l-snvx2cmg8w-m:proxy-server bjoshi$ curl -v http://127.0.0.1:8001 -H 'x-asdf: foo' -d 'asdf'
<p><\n>* Rebuilt URL to: http://127.0.0.1:8001/
<p><\n>* Hostname was NOT found in DNS cache
<p><\n>*   Trying 127.0.0.1...
* Connected to 127.0.0.1 (127.0.0.1) port 8001 (#0)
> POST / HTTP/1.1
> User-Agent: curl/7.37.1
> Host: 127.0.0.1:8001
> Accept: */*
> x-asdf: foo
> Content-Length: 4
> Content-Type: application/x-www-form-urlencoded
> 
* upload completely sent off: 4 out of 4 bytes
< HTTP/1.1 200 OK
< user-agent: curl/7.37.1
< host: 127.0.0.1:8001
< accept: */*
< x-asdf: foo
< content-length: 4
< content-type: application/x-www-form-urlencoded
< connection: close
< date: Thu, 20 Aug 2015 18:01:05 GMT
< 
* Closing connection 0

Walkthrough.gif

![walkthrough](https://cloud.githubusercontent.com/assets/5514807/9391072/b71136ea-4729-11e5-8396-2671f494a083.gif)
