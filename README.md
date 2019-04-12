# Proxy-Server
A multithreaded proxy server in python, implemented using threading and sockets. Supoorts HTTP websites only.

### Functionalities Covered
- Multiple Clients can be routed through this server.
- Websites are cached in case of frequent requests (more than 3 times) within a period of 5 minutes.
- Blocking using a CIDR list (present in proxy/blacklist.txt)

### Tested on
- [Baidu](www.baidu.com)
- [ICZN](www.iczn.org)

### To Run
- Fix the port on your host to 20100 (server assumes to be on the port 20100 and reroutes requests through it).
```console
user@linux:~/Proxy-Server$ python server.py
```
