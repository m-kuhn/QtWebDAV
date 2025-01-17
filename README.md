# QtWebDAV

QtWebDAV Library version 2.0

is a library for Qt6 (and Qt5) and provides access to WebDAV servers.
WebDAV is an extension for HTTP, so that a Web server can
provide write access in addition to read access. The WebDAV
standard provides the essential functionalities to access
a Web server like a file server.

More information
http://en.wikipedia.org/wiki/WebDAV

WebDAV standard as RFC4918:
"HTTP Extensions for Web Distributed Authoring and
Versioning (WebDAV)" from June 2007
http://tools.ietf.org/html/rfc4918

This library has been derived from previous works
QWebdav plugin for MeeDav (LGPL v2.1)
http://projects.developer.nokia.com/meedav/
QWebdav - WebDAV lib for Qt4 (LGPL v2.1)
http://xf.iksaif.net/dev/qwebdav.html

Tested WebDAV server:
- Apache HTTP Server with mod_dav
Apache/2.2.14, http://httpd.apache.org/
- Microsoft Internet Information Service 7.5 (MS IIS 7.5)
as used by Windows 7 and Windows Server 2008 R2
- SabreDAV - WebDAV framework for PHP
SabreDAV 1.6.1-stable, http://code.google.com/p/sabredav/

QtWebDAV Library supports the following authentication methods:
(as provided by Qt4)

* Basic
  http://en.wikipedia.org/wiki/Basic_access_authentication
* NTLM version 1 (older Windows challenge-response authentication)
  http://en.wikipedia.org/wiki/NTLM
* Digest-MD5
  http://en.wikipedia.org/wiki/Digest_access_authentication

More information on authentication by Qt6

https://doc.qt.io/qt-6/qtnetworkauth-index.html

## Build

```shell
cmake -S . -B build -GNinja
cmake --build build
```

