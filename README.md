OSE Secure plugin provides the most basic protection to a website. 
It supports Joomla! versions including Joomla!1.5, 2.5 and 3.x.

###Please download it here:
[Download OSE Secure Plugin](https://github.com/ShawnOSE/OSE-Secure-Plugin/archive/master.zip)

###Installation 
After the download, please extract the package on your local first. Then you can find the proper version to install on your website for Joomla! 1.5, or Joomla! 2.5.-3.x. Install it from Joomla! Extensions --> Install.

###Configuration
<img src="https://cdn.protect-website.co/centrora_web/images/Community/OSE%20Secure%20Plugin/2017-03-17_15-55-40.png" width="750">

1. After the installation, please enable the plugin "System - OSE Secure" and also enable the parameter "Basic Feature - Enable OSE Backend Secure Key" to activate the functions.

2. Set the Secure Key to protect the website back-end. 
The default secure key is **oseSecure**, so if you have not changed the key, please try to access the back-end at:
http://www.yourwebsite.com/administrator/?oseSecure
This should get you back to the administrator panel.
If you forget the key but forget the key, please rename the file:  /plugins/system/osesecure/osesecure.php to /plugins/system/osesecure/osesecure2.php through the FTP to have the access back.

3. The plugin also has the function previously to enable OSE anti-Hacker. If there is no OSE Anti-Hacker installed in the site, please DO NOT enable the parameter "Activate Anti-Hacker Protection"

4. Please enable the Rules of the protection.

5. You can add whitelist variables in this section. For example, you have the form on the site with the field name and function POST.name. If the form submission is falsely blocked, you can add the whitelist variable POST.name there.