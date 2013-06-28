cross-domain
============

POC data-persistent across different domains
----------------------------------------------

1. add the following to your local host file: \n
	127.0.0.1 domain1.com\n
	127.0.0.1 domain2.com\n
	127.0.0.1 placeholder.com\n
2. add virtual directory for "localhost/cross-origin" and place all four files (from POC folder) in this directory.
\n