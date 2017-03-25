# down2transmission

Add a button in some private tracker site to support adding torrent to Transmission. 

Current support CCF and TTG.

If you want more pt sites supported, send me an invite :P

Screen shots:

[[https://github.com/coderant/repository/blob/master/img/main_page.jpg|alt=main_page]]
[[https://github.com/coderant/repository/blob/master/img/detail_page.jpg|alt=detail_page]]
[[https://github.com/coderant/repository/blob/master/img/added.jpg|alt=added]]


Edit below in script before use.

```
// http://192.168.1.1 for local access, input ddns for external access.
// NO trailing slash(/).
var transmission_url = "http://your.url.here";

// value of "rpc-port" in settings.json .
var transmission_port = "9091";

// value of "rpc-url"  in settings.json .
var transmission_rpc_bind_address = "/transmission/";

// Authentication;
var username = "your_username";
var pw = "your_password";
```
