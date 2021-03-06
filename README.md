rigWatch
========

Self-hosted, PHP-based frontend interface for cgminer, MPOS pools, and other APIs, all in one responsive UI.

Requirements:
--
- PHP v5.2+
- Apache or IIS
 - or use XAMPP (http://www.apachefriends.org/en/xampp.html)
- cgminer (for monitoring rigs)
- MPOS Mining Pool account (many pools support this)

Installation:
--

1. Install (if required) a web server such as Apache or Microsoft IIS. 
  1.  If you're running Windows, and have neither IIS nor PHP installed, there is a simple tool from Microsoft called [Web Platform Installer](http://www.microsoft.com/web/downloads/platform.aspx) that can do this painlessly. 

2. Setup a new site and point the home/root directory to this project. 

You'll want to ensure you're running cgminer with API-Access enabled, here's an example excerpt from the .conf:

    ...
    "api-allow" : "W:127.0.0.1,192.168.1.0/24",
    "api-listen" : true,
    "api-mcast-port" : "4028",
    "api-port" : "4028",
    ...

...and you should be good to go. 

Hope you enjoy what we're trying to do here, and thanks to all of the other similar OSS projects like this for help and inspiration.

Our own measly rigs would appreciate any catalyst donations to **[TODO] WALLET ADDRESS [/TODO] - Thanks in advance!**

Reference: https://www.cryptsy.com/pages/api
