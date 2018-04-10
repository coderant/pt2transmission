# down2transmission

## Introduction
Add a button in torrent sites to support adding torrent to Transmission directly.

## Images
<img src="https://raw.githubusercontent.com/coderant/down2transmission/master/resource/img/main_page.jpg" width="300">
<img src="https://raw.githubusercontent.com/coderant/down2transmission/master/resource/img/added.jpg" width="300">
<img src="https://raw.githubusercontent.com/coderant/down2transmission/master/resource/img/duplicate.jpg" width="300">

## Supported sites:
```
ccfbits
- http://ccfbits.org/browse.php
- http://ccfbits.org/details.php

totheglory
- https://totheglory.im/browse.php
- https://totheglory.im/t/

piratebay
- https://thepiratebay.org/search/

iptorrent
- https://iptorrents.com/t?q=
```

Open an issue or pull request if you want more sites supported.

If it's an private site(I don't have access), you better send me an invite. ;P

## Usage
Edit below in script before use.

```javascript
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

// Can be found in direct download rss.
var ipt_torrent_pass = "your_ipt_torrent_pass";
```

## Environment
Tested with Tampermonkey on Chrome, macOS.
