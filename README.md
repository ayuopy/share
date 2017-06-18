## Share messages across devices connected to a local network through a web page

### Usage

`$ ./share [OPTION]`

You can then visit the specified location to begin a new session. Bare in
mind that share.html points to a WebSocket connection at localhost:8080 (see
also below). You can change this in share.html (line 45) and by using the `-f`
flag.

### Options

```
-f      specify a HTML file to serve (default: share.html)
-s      set a host and port to listen on (default: localhost:8080)
-h      print help text
```

Note that the by default the web page will only be accessible to the
host. To serve it across the local network, specify the host's local IP
address with the `-s` flag (you can find the address by using `hostname -I`).

### Todo

* Regex search urls within messages
* Responsive design elements
* Add file upload feature

### Screenshots

![desktop](https://github.com/ayuopy/share/images/desktop.jpg)

![mobile](https://github.com/ayuopy/share/images/mobile.jpg)