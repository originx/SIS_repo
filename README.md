#xploitSearch v 1.0
Nmap script for detecting exploits on remote hosts 
========
Get data from scanned ports and services with OS fingerprint (if exists)
and query exploitsearch.net to get possible number of exploits on specific service.
Use -oX filename.xml or similar for structured file output.

###DISCLAIMER: 
Number of shown exploits doesn't reflect possible number of security holes that exists on your server. 
exploitsearch.net crawls possible security databases and depending on the quality of the query returns different results.

###Contributors:
* Mario Oršolić - (https://github.com/originx)

###TO DO:
-Improve OS fingerprint query if possible, results are sometimes unpredictable if there is not enough information
-Set http headers for more polite querys.
-Clean up code <- prehaps there are some finished libraries for eg. url escape chars.

Mentored under:
##FOI OSS
-Faculty of Organization and Informatics
-Open Systems and Security Lab
-http://security.foi.hr/wiki/index.php/Glavna_stranica
-Class: Sigurnost informacijskih sustava
-Tonimir Kišasondi - (https://github.com/tkisason)

------------------------------------------------------------------------
