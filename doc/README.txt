chttpd
======

chttpd is a simple web server that I'm currently working on. This is the 
initial release of this web server, and its in working condition

Website: http://pentium44.github.io/projects/chttpd.html
License: GPLv2

Compiling chttpd:
	~navigate to the chttpd directory
	~run: make
	~start the httpd

Changelog:
	v1.3.1:
	Fixed a major URI path bug.

	v1.3.0:
	Added CGI support.
	CGI can be enabled / disabled within config
	
	v1.2.6:
	Added configuration parser
	
	v1.2.5:
	Added Content-Length to header
	Added new mimetypes
	Fixed old archive mimetypes

	v1.2.4:
	Fixed another bug in the directory listings, now working smooth
	cleaned the code, added comments
	
	v1.2.3:
	Fixed directory listings bug
	Added sys lable to error, and directory pages
	Cleaned up logging system

	v1.2.2:
	Added directory listings (Thanks Lisa!)
	Added index.html support

	v1.2:
	Added some small features
	Development at a standstill

	v1.1:
	Initial release, works fine
