cross-domain
============

POC data-persistent across different domains
----------------------------------------------

1. add the following to your local host file:
	127.0.0.1 domain1.com
	127.0.0.1 domain2.com
	127.0.0.1 placeholder.com
2. add virtual directory for "localhost/cross-origin" and place all four files (from POC folder) in this directory.