# fileserver

These scripts are used for building an FTP style fileserver on your own hardware.  

download-server.py - Flask python server for serving dynamic .tar downloads  
fixperms.sh - Easy bash permission-solving script for bad imports  
hash.py - Script that generates checksums for each folder  
html_gen.py - The script used to generate HTML index files for each folder  

Use at your own risk, this should be perfectly secure for trusted LAN environments but Flask is not perfect if you're going more in a consumer-grade route.
