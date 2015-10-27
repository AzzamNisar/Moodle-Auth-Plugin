Problem Statement:
I’ve been stuck in a problem where I have to develop a local Plugin in Moodle 2.9 that just sends Username & Password to that plugin and in return, the plugin should return True or False (You can modify according to your need).
Description:
Authenticate.php will GET two parameters and perform all authentication processes and return accordingly (For now I’m Printing the valid “$user” object if the Username & Passwords matches from “username” & “password” fields in mdl_users table). Moodle 2.9 verify a password against a hash using a timing attack resistant approach (http://www.iacr.org/archive/ches2009/57470001/57470001.pdf)
Plugin Location: moodle/location/auth_webservice/authenticate.php
Plugin Call: http://localhost/moodle/local/auth_webservice/authenticate.php?username=azzam&password=vwXyz.123
Contact Details:
Email: azzamnisar1@gmail.com
Attachments:
auth_webservice.zip
