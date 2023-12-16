**A technique by which a website is downgraded from https to http**. Exposes you to **eavesdropping and data manipulation**

# How it works
To execute an SSL strip attack, there must be three entities – victim’s system, secure web server, and attacker’s system. 
In order to “strip” the TLS/SSL, an attacker intervenes in the redirection from HTTP to HTTPS and intercepts a request from the user to the server.


Best Defense → Enable HTTPS on ALL pages of your website. Implement a HTTP Strict Transport Security (HSTS) policy, so the browser requires HTTPS.

