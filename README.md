Deploy-Server-Config
====================

Configurations related to the server:
Server runs xampp using itself as a DNS and a static IP address.
To allow connectivity from other machines, have them edit their etc/host files to resolve that 
static IP address to whatever you want your website name to be. 
You also have to allow incoming connections on the xampp side by editing
the following files:
-httpd.conf in both the original and extra folders
-xampp.conf

Tested on 3/27/2015 and this setup should work on both wireless and ethernet
running IPV4 and IPV6. 

-Frank N. Landry
