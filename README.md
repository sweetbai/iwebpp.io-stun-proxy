iwebpp.io-stun-proxy
====================

iWebPP.io local STUN proxy

### Features

* proxy web service over STUN session
* secure p2p proxy tunnel
* high udp data transfer performance

### Install
* npm install iwebpp.io-stun-proxy, or git clone https://github.com/InstantWebP2P/iwebpp.io-stun-proxy.git && cd iwebpp.io-stun-proxy && npm install
* iwebpp.io-stun-proxy depend on node-httpp, please npm install httpp-binary.if the binary didn't work, just build it from source:
  https://github.com/InstantWebP2P/node-httpp

### Usage/API
* for demo, refer to demo/webproxy.js. to start it, just node demo/webproxy.js
* for utility, refer to bin/stun-proxy. to start it, just node bin/stun-proxy --key usrkey(MUST) --port 51688
* after start local proxy server, just embed 'vlocal.' as sub-domain in original vURL, then open it in web browser, 
  like original vURL is https://p95a6d9bd2d1f1c87p.7c80afab98c2bf81be92ea66707a3427.vurl.iwebpp.com:51688/,
  modified vURL is https://p95a6d9bd2d1f1c87p.7c80afab98c2bf81be92ea66707a3427.vurl.vlocal.iwebpp.com:51688/

<br/>
### License

(The MIT License)

Copyright (c) 2012-2013 Tom Zhou(iwebpp@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
