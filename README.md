# Welcome to the OWASP Top 10 2007! 

This edition, totally re-written from the previous 2004 version, lists the most serious web application vulnerabilities, discusses how to protect against them, and provides links to more information. 

OWASP Top 10 2007 List :

[A1 - Cross Site Scripting (XSS)](https://www.owasp.org/index.php/Top_10_2007-Cross_Site_Scripting)

XSS flaws occur whenever an application takes user supplied data and sends it to a web browser without first validating or encoding that content. XSS allows attackers to execute script in the victim's browser which can hijack user sessions, deface web sites, possibly introduce worms, etc. 

[A2 - Injection Flaws](https://www.owasp.org/index.php/Top_10_2007-Injection_Flaws)

Injection flaws, particularly SQL injection, are common in web applications. Injection occurs when user-supplied data is sent to an interpreter as part of a command or query. The attacker's hostile data tricks the interpreter into executing unintended commands or changing data. 

[A3 - Malicious File Execution](https://www.owasp.org/index.php/Top_10_2007-Malicious_File_Execution)

Code vulnerable to remote file inclusion (RFI) allows attackers to include hostile code and data, resulting in devastating attacks, such as total server compromise. Malicious file execution attacks affect PHP, XML and any framework which accepts filenames or files from users. 

[A4 - Insecure Direct Object Reference](https://www.owasp.org/index.php/Top_10_2007-Malicious_File_Execution)

A direct object reference occurs when a developer exposes a reference to an internal implementation object, such as a file, directory, database record, or key, as a URL or form parameter. Attackers can manipulate those references to access other objects without authorization.

[A5 - Cross Site Request Forgery (CSRF)](https://www.owasp.org/index.php/Top_10_2007-Cross_Site_Request_Forgery)

A CSRF attack forces a logged-on victim's browser to send a pre-authenticated request to a vulnerable web application, which then forces the victim's browser to perform a hostile action to the benefit of the attacker. CSRF can be as powerful as the web application that it attacks. 

[A6 - Information Leakage and Improper Error Handling](https://www.owasp.org/index.php/Top_10_2007-Information_Leakage_and_Improper_Error_Handling)

Applications can unintentionally leak information about their configuration, internal workings, or violate privacy through a variety of application problems. Attackers use this weakness to steal sensitive data, or conduct more serious attacks. 

[A7 - Broken Authentication and Session Management](https://www.owasp.org/index.php/Top_10_2007-A7)

Account credentials and session tokens are often not properly protected. Attackers compromise passwords, keys, or authentication tokens to assume other users' identities. 

[A8 - Insecure Cryptographic Storage](https://www.owasp.org/index.php/Top_10_2007-Insecure_Cryptographic_Storage)

Web applications rarely use cryptographic functions properly to protect data and credentials. Attackers use weakly protected data to conduct identity theft and other crimes, such as credit card fraud. 

[A9 - Insecure Communications](https://www.owasp.org/index.php/Top_10_2007-Insecure_Communications)

Applications frequently fail to encrypt network traffic when it is necessary to protect sensitive communications.

[A10 - Failure to Restrict URL Access](https://www.owasp.org/index.php/Top_10_2007-Failure_to_Restrict_URL_Access)

Frequently, an application only protects sensitive functionality by preventing the display of links or URLs to unauthorized users. Attackers can use this weakness to access and perform unauthorized operations by accessing those URLs directly. 
