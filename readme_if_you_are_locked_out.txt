If you are locked out from the administrator panel as you forgot the secure key to the administrator panel. Please do the following:

1. The default secure key is oseSecure, so if you have not changed the key, please try to access the backend here: 

http://www.yourwebsite.com/administrator/?oseSecure

this should get you back to the administrator panel.

2. However, if you have changed the key but forget the key, please do the following:

a) Login your ftp, and access this folder in your Joomla installation folder: /plugins/system/osesecure/
b) Rename the file  /plugins/system/osesecure/osesecure.php to /plugins/system/osesecure/osesecure2.php
c) Now, please access the administrator backend, and go to plugin manager, mark down the secure key you have configured in the plugin manager. 
d) Rename the file  /plugins/system/osesecure/osesecure2.php back to /plugins/system/osesecure/osesecure.php
e) Acccess your website through this link:

http://www.yourwebsite.com/administrator/?YOURSECUREKEY


