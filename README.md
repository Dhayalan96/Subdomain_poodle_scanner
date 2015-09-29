# Subdomain_poodle_scanner
Scans the subdomains of the given Domiain for Poodle Vulnerability
  This script dnsdumpster.com to get the DNS records

pre requisites

 * Python 3
 * An SSL library that supports SSLv3
 * Beautifulsoup4

<h1>Basic Usage </h1>

  python3 Subdomain_poodle_scanner.py <domain>
  
  where domain is the domain name ALONE ! 
  
  Example in case of https://facebook.com use **domain as facebook.com**
  
###Output
An output of https (443): **No Answer** indicates the server is not listening on port 443 or is very slow .
An output of https (443): **Rejected** indicates that the server does not accept connections with the SSLv3 protocol.
An output of https (443): __**WARNING**__ CONNECTION ACCEPTED indicates that the server does accept https connections 
      with SSLv3. 

You can always ping me at dhayalanpro@gmail.com
