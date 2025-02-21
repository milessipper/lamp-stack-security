# lamp-stack-security
Configured a LAMP stack on Ubuntu with security enhancements, SQLMap testing, and ModSecurity.

LAMP Stack Security Project
Author: Miles Sipper 
Date: February 20, 2025

Overview:
This project involves setting up a LAMP (Linux, Apache, MySQL, PHP) stack on my Ubuntu system and implementing security enhancements. I used SQLMap to allow for penetration testing, configured ModSecurity as a Web Application Firewall (WAF), and applied several other best practices as security configurations. This was my first major project and is rather rudimentary. It was a great way for me to gain hands-on skills relating to web security, security hardening, and even a little bit of penetration testing. Through this project, I learned how to identify and mitigate vulnerabilities, configure security tools, and enhance the overall resilience of a web application. My skills are rather elementary, and I plan on frequently revisiting this project and improving it as my skills improve.

Security Features Implemented
 SQL Injection Testing – Used SQLMap to test vulnerabilities in a sample web app.
ModSecurity WAF – Configured ModSecurity to filter and block malicious HTTP requests.
 Least Privilege Database Access – Restricted MySQL user permissions.
Firewall Rules – Allowed only necessary traffic (e.g., HTTP/HTTPS).
Secure Apache Configuration – Disabled directory listing, prevented file uploads execution, etc
