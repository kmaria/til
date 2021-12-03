### What is an IDOR vulnerability?

IDOR stands for Insecure Direct Object Reference and is a type of access control vulnerability. An access control vulnerability is when an attacker can gain access to information or actions not intended for them. An IDOR vulnerability can occur when a web server receives user-supplied input to retrieve objects (files, data, documents), and too much trust has been placed on that input data, and the web application does not validate whether the user should, in fact, have access to the requested object.

### IDOR in the wild

Seeing a product, user, or service identifier in the URL or otherwise is a must to test. IDOR vulnerabilities can reveal sensitive information, as well as potentially giving you access to usually restricted site functionality.


[Top 25 IDOR Bug Bounty Reports](https://corneacristian.medium.com/top-25-idor-bug-bounty-reports-ba8cd59ad331) 

[OWASP - Testing for IDOR](https://owasp.org/www-project-web-security-testing-guide/latest/4-Web_Application_Security_Testing/05-Authorization_Testing/04-Testing_for_Insecure_Direct_Object_References)
