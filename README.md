# NOTICE
*11/6/2017 - It is no longer recommended to use this script, now that Navicat ships an updated ntunnel_mysql.php script with Navicat for MySQL 12+.  To get the newer script, follow [these instructions](https://help.navicat.com/hc/en-us/articles/218283457-Where-can-i-get-the-HTTP-tunnel-script-file-).*

---

# ntunnel_mysqli

This is an updated tunnel script for connecting to MySQL and MariaDB databases with Navicat for MySQL via mysqli.  The ntunnel_mysql.php script that comes with current versions of Navicat (as of 10/18/2016) will not work with PHP7, as procedural mysql functions have been deprecated.

## About Tunneling
HTTP Tunneling is a method for connecting to a server that uses the same protocol (http://) and the same port (port 80) as a webserver does. It is used while your ISPs do not allow direct connections, but allows establishing HTTP connections.

## Uploading the Tunneling Script

To set up an HTTP tunnel, first upload the ntunnel_mysqli.php script to your web server.

## Setting up HTTP Tunnel

The following instruction guides you through the process of configuring a HTTP connection.

1. Select the HTTP tab and enable **Use HTTP Tunnel**.
2. Enter URL of the tunneling script, e.g. *http://www.navicat.com/ntunnel_mysqli.php* .
3. If your server installed a Web Application Firewall, you can check the **Encode outgoing query with base64** option.
4. If the tunneling script is hosted in a password protected server or you have to access internet over a proxy server, you can provide the required authentication details in **Authentication** or **Proxy** tab.
5. Navicat host name at the General settings page should be set relatively to the HTTP server which provided by your database hosting company.
