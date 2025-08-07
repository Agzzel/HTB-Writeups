<h1>Code Writeup</h1>

<h3>Introduction</h3>
Code is an Easy-rated box on HackTheBox, in which a code injection vulnerability is used to gain low-privileged access to the server. 
A path traversal vulnerability is then exploited to obtain the root flag.

The purpose of this document is to show my approach to obtaining unauthorised root privileges on the server and how to remediate the discovered security issues.

<h3>Enumeration</h3>
Initial Nmap scan revealed SSH on port 22 and Gunicorn on 5000.
