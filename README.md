# Task 1 - Vulnerability Assessment Report

This project presents a basic vulnerability assessment of a live website (http://demo.testfire.net) using passive security testing techniques.

## Tools Used

* Browser Developer Tools
* OWASP ZAP (Passive Scanning)
* Nmap

## Methodology

* Inspected HTTP headers and cookies using DevTools
* Performed passive vulnerability scanning using OWASP ZAP
* Conducted port scanning using Nmap

## Key Findings

* Missing security headers (Content Security Policy, X-Frame-Options)
* Cookie security issues (Secure and SameSite attributes missing)
* Missing X-Content-Type-Options header
* Server version information disclosure
* Open ports identified (SSH, HTTP)

## Conclusion

The assessment identified several common security misconfigurations. Implementing the recommended fixes will improve the website’s security posture and reduce potential risks.

## Note

Nmap scanning was performed on a safe testing domain (scanme.nmap.org) due to restrictions on the main website.
