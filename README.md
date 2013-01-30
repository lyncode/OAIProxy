## OAI Proxy 1.0 (Beta)

### What is OAI Proxy?

OAI Proxy is a standalone service that allows one to harvest multiple OAI-PMH data providers, offering an OAI interface that exposes those harvested records.

- Easy to use and install
- Fast, it indexes all the information
- Uses [XOAI](http://github.com/lyncode/xoai) which means powerful features (Virtual Sets, Virtual Contexts, Transformers, Filters)


### Manual (UNIX)

- Download the ZIP file, unpack it.
- (Optional) Edit configurations at ``[UNPACKED_OAIPROXY_DIR]/config/proxy.cfg``
- Open the terminal and execute:

``$ cd [UNPACKED_OAIPROXY_DIR]``

``$ sudo java -jar oai-proxy.jar``

### OAI Proxy in Action

NOTE: By default OAI Proxy will use port 80.

- Open the browser at http://localhost
- The OAI interface will be available at http://localhost/oai/request

- - - 

### Credits

OAIProxy was developed and is currently maintained by [Lyncode](http://www.lyncode.com). 

All resources used on this site are released under their respective licenses by the authors credited in this page.
The OAIProxy components are distributed using the [Apache License, Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

![Developed by Lybcode](http://www.lyncode.com/images/lyncode/logo.png)
