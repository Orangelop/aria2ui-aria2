# aria2-aria2ui

[![bilibili](https://img.shields.io/badge/Bilibili-Orangelop-red)](https://space.bilibili.com/54818676)
![github-follow](https://img.shields.io/github/followers/Orangelop?label=Followers&style=social)
![github-watch](https://img.shields.io/github/watchers/Orangelop/aria2ui-aria2?style=social)
![github-fork](https://img.shields.io/github/forks/Orangelop/aria2ui-aria2?label=Forks&style=social)
![github-stars](https://img.shields.io/github/stars/Orangelop/aria2ui-aria2?style=social)
[![license](https://img.shields.io/github/license/Orangelop/aria2ui-aria2)](EMPTY)
![language-top](https://img.shields.io/github/languages/top/Orangelop/aria2ui-aria2)
![languange-count](https://img.shields.io/github/languages/count/Orangelop/aria2ui-aria2)
[![chat-gitter](https://img.shields.io/gitter/room/Orangelop/aria2ui-aria2)](https://gitter.im/aria2uiandaria2/community#)
![open-pull-repuests](https://img.shields.io/github/issues-pr-raw/Orangelop/aria2ui-aria2)
![open-issues](https://img.shields.io/github/issues-raw/Orangelop/aria2ui-aria2)

Download Latest Releases

[![lr](https://img.shields.io/static/v1?label=latest-releases&message=0.1.1-alpha&color=brightgreen?style=flat-square&logo=appveyor)](https://github.com/Orangelop/aria2ui-aria2/releases)

The size of the repository

![repo-size](https://img.shields.io/github/repo-size/Orangelop/aria2ui-aria2)

The size of the code

![code-size](https://img.shields.io/github/languages/code-size/Orangelop/aria2ui-aria2)

## Status

aria2ui official releases site status

![site-status](https://img.shields.io/website?down_color=red&down_message=oops%21&up_color=lightgreen&up_message=online&url=https%3A%2F%2Forangelop.github.io%2Faria2ui%2Faria2ui.html)  

aria2(official build) build status

[![Build status](https://img.shields.io/appveyor/build/Orangelop/aria2?logo=appveyor)](https://ci.appveyor.com/project/Orangelop/aria2)

*\*Now we use official build. But we will change into unofficial builds to break the thread limit in future releases.*  

Notice:We will no longer update README.txt, please use README.md instead.  

## Version  

Aria2: 1.35.0(Official Build)  
Aria2ui: 0.1.1-alpha(Bld Date:2020-07-13)

## Introduction

This Repository  
Aria2: aria2 is a lightweight multi-protocol & multi-source, cross platform download utility operated in command-line. It supports HTTP/HTTPS, FTP, SFTP, BitTorrent and Metalink.

[Repository Link](https://github.com/aria2/aria2)

Aria2ui: A new website GUI with aria2 supporting all the new features of aria2

[Repository Link(Will be added soon)](EMPTY)

## Features(aria2ui & aria2)

### Aria2ui Features  

1. Using web GUI to download files.
2. You can login aria2 using password.
3. Watching while downloading*.
4. The max number of threads can up to 16**.  
and many other features...  

### Aria2 Features  

* Command-line interface
* Download files through HTTP(S)/FTP/SFTP/BitTorrent
* Segmented downloading
* Metalink version 4 (RFC 5854) support(HTTP/FTP/SFTP/BitTorrent)
* Metalink version 3.0 support(HTTP/FTP/SFTP/BitTorrent)
* Metalink/HTTP (RFC 6249) support
* HTTP/1.1 implementation
* HTTP Proxy support
* HTTP BASIC authentication support
* HTTP Proxy authentication support
* Well-known environment variables for proxy: ``http_proxy``,
  ``https_proxy``, ``ftp_proxy``, ``all_proxy`` and ``no_proxy``
* HTTP gzip, deflate content encoding support
* Verify peer using given trusted CA certificate in HTTPS
* Client certificate authentication in HTTPS
* Chunked transfer encoding support
* Load Cookies from file using the Firefox3 format, Chromium/Google Chrome
  and the Mozilla/Firefox
  (1.x/2.x)/Netscape format.
* Save Cookies in the Mozilla/Firefox (1.x/2.x)/Netscape format.
* Custom HTTP Header support
* Persistent Connections support
* FTP/SFTP through HTTP Proxy
* Download/Upload speed throttling
* BitTorrent extensions: Fast extension, DHT, PEX, MSE/PSE,
  Multi-Tracker, UDP tracker
* BitTorrent `WEB-Seeding <http://getright.com/seedtorrent.html>`_.
  aria2 requests chunks more than piece size to reduce the request
  overhead. It also supports pipelined requests with piece size.
* BitTorrent Local Peer Discovery
* Rename/change the directory structure of BitTorrent downloads
  completely
* JSON-RPC (over HTTP and WebSocket)/XML-RPC interface
* Run as a daemon process
* Selective download in multi-file torrent/Metalink
* Chunk checksum validation in Metalink
* Can disable segmented downloading in Metalink
* Netrc support
* Configuration file support
* Download URIs found in a text file or stdin and the destination
  directory and output file name can be specified optionally
* Parameterized URI support
* IPv6 support with Happy Eyeballs
* Disk cache to reduce disk activity

*\*This is the future plan*  
*\*\*In the future, threads can up to 128*  

## Usage

### Step 1  

Download and extract the file.

### Step 2

#### Way 1

Click the .vbs file and aria2 will run without a command prompt.  

#### Way 2

Create a shortcut and point to 'aria2c.exe --conf-path=aria2.conf'(make sure the 'aria2.conf' file is in the same folder with 'aria2c.exe'), or you can point it to 'aria2c.exe --conf-path=(the location of the config path)', then click it, aria2 will run with a command prompt.

### Step 3

Open the website in 'aria2-with-gui-0.1.1-alpha\webui-aria2\docs\index.html'

### Step 4

Follow the steps below to enter the RPC password.  
English Mode:
GUI > Settings > Connection Settings > Aria2 RPC host and port > Enter the secret token (optional)  
Default password is: `123456`  
Or you can delete 'rpc-secret=123456' in 'aria2.conf'  

### Step 5

Just enjoy it!
Tips: After reading the files with '!' in front of their names, you can delete them.

## More Usage

The more config commands will be in or not depending by yourself.
CHN:[Click Here](http://aria2c.com/usage.html)  
(The config command in this website is a little and had no longer updated, so view the English website as you can.)  
ENG:[Click Here](https://aria2.github.io/manual/en/html/aria2c.html)

## Problems  

If you have some problems when using aria2ui or unofficial aria2 build, please comment as an open issue.  

## Directory-Structure

You can also read it after extract the release folder, it's called '!filetree-(the version of aria2ui-aria2).txt'
