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


### License

Copyright 2012 Lyncode

![Developed by Lybcode](http://www.lyncode.com/images/lyncode/logoCor.png)

Licensed under the Apache License, Version 2.0 (the "License") you may not use this file except in compliance with the License.
You may obtain a copy of the License at 
	
[http://www.apache.org/licenses/LICENSE-2.0](http://www.apache.org/licenses/LICENSE-2.0)

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.


