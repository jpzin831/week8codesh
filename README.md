# week8codesh
# Project 8 - Pentesting Live Targets

1. Username Enumeration: A careless developer mistake has created a username enumeration vulnerability. Determine which color has the vulnerability. You can use the existing username "jmonroe99" as a test. Next, figure out what mistake the developer made.

Green has the vulnerability, the error given when login is unsuccesful in not bold when a non-existant user tries to log in.
<img src="https://github.com/jpzin831/week8codesh/blob/master/username%20enumaration.gif" width="800">

2. Insecure Direct Object Reference: One of the three sites is missing code which would prevent some sensitive information from being made public. Determine which color has the vulnerability. Then, figure out what the other two sites did correctly to prevent the information leak.
Red has the missing code.
<img src="https://github.com/jpzin831/week8codesh/blob/master/insecure_object.gif" width="800">

3.Most of the data input received by these websites is being sanitized properly. However, one of the three sites has one place where the input is not being sanitized before being used in an SQL query. Determine which color has the vulnerability.
 Blue has the vulnerability.
 
 <img src="https://github.com/jpzin831/week8codesh/blob/master/3.gif" width="800">
 
 4.All three sites do a good job of protecting against a reflected XSS attack. However, one of the sites has a mistake which leaves the site vulnerable to a stored XSS attack. A reflected XSS attack would be easy to reveal, while a stored XSS does not provide instant feedback. You will need to log into the admin area and look through the CMS in order to "spring the trap" and find out if your attack succeeded. Determine which color has the vulnerability. Remember, others will be attacking these sites alongside you. Use your name in the XSS so that your results won't be confused with anyone else's 
 
 Green has the vulnerability.
 
  <img src="https://github.com/jpzin831/week8codesh/blob/master/4.5.gif" width="800">
