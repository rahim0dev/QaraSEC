
# QaraSEC - DETAILED CYBER SECURITY TOOL

QaraSEC is an advanced cybersecurity scanning tool designed for penetration testers and security professionals. This powerful toolkit provides a wide range of vulnerability assessment capabilities to help identify security weaknesses in web applications and network systems.



![Logo](https://i.ibb.co/qFcrCCcY/qarasec.jpg)

    
# Features
### Web Application Security Testing:

- XSS Scanner: Detects Cross-Site Scripting vulnerabilities in web applications

- SQL Injection Scanner: Identifies SQL injection points in web forms and APIs

- CSRF Scanner: Checks for Cross-Site Request Forgery vulnerabilities

- XXE Scanner: Tests for XML External Entity processing vulnerabilities

- Clickjacking Tester: Verifies X-Frame-Options and CSP headers

- Open Redirect Scanner: Finds unsafe URL redirection implementations

- CRLF Injection Scanner: Detects HTTP header injection vulnerabilities

- SSRF Scanner: Identifies Server-Side Request Forgery risks

  
### Network and Infrastructure Scanning:

- Port Scanner: Checks for open ports on target systems

- NTP Scanner: Tests for NTP amplification vulnerabilities

- WAF Detector: Identifies Web Application Firewalls in use

- WHOIS/DNS/SSL Scanner: Gathers domain registration and SSL certificate information

### Discovery Tools:

- Admin Panel Finder: Locates administrative interfaces

- Subdomain Finder: Discovers subdomains of target domains

- Hidden File Scanner: Finds hidden files and directories

- Directory Traversal Tester: Checks for path traversal vulnerabilities

### Authentication Testing:

- Brute Force Tool: Performs credential brute force attacks

- Command Injection Scanner: Tests for OS command injection flaws

# General use of the software 

## Tool Main Menu
![Screenshot 1](https://i.postimg.cc/L4Qjn6Yx/Screenshot-1.png)

## XSS Scanner
![Screenshot 2](https://i.postimg.cc/GmGD7FMf/Screenshot-2.png)
- Used to detect Cross-Site Scripting (XSS) vulnerabilities, including both reflected and stored XSS. You can use default payloads or add custom ones. It supports scanning a single URL or multiple URLs in bulk. The results show which payloads were successful and which were not.

## SQL Injection
![Screenshot 3](https://i.postimg.cc/L6rf3CVf/Screenshot-3.png)
- Detects SQL injection vulnerabilities using various techniques (UNION-based, Boolean-based, Time-based). You can scan a single URL or multiple URLs. The results indicate which parameters are vulnerable and which payloads worked.


## Port Scanner
![Screenshot 4](https://i.postimg.cc/k5Cbk2zg/Screenshot-4.png)
- Scans for open ports on a target system. You can scan all ports (1-65535), common ports, or a custom range. Results show open, closed, and filtered ports, along with scan duration.
![Screenshot 4.1.1](https://i.postimg.cc/X7ZdFS94/Screenshot-4-1-1.png)

## Admin Panel Finder
![Screenshot 5](https://i.postimg.cc/s2JhyVC9/Screenshot-5.png)
- Finds admin panels on websites by testing common paths. You can use a default wordlist or a custom one. Results show discovered admin panels and inaccessible paths.


## Subdomain Finder
![Screenshot 6](https://i.postimg.cc/d3hk8rk4/Screenshot-6.png)
- Discovers subdomains of a target domain. It tests common subdomains or uses a custom wordlist. Results display active and inactive subdomains.


## WAF Scanner
![Screenshot 7](https://i.postimg.cc/nzcQh6H8/Screenshot-7.png)
- Detects Web Application Firewalls (WAFs) by testing different HTTP methods (GET, POST, PUT, DELETE). Results identify the WAF in use and which methods are blocked.


## WHOIS/DNS/SSL
![Screenshot 8](https://i.postimg.cc/NMJ29pMK/Screenshot-8.png)
- Retrieves WHOIS data, DNS records, and SSL certificate details for a domain. Shows registration date, expiration date, name servers, and SSL certificate information.


## Directory Traversal
![Screenshot 9](https://i.postimg.cc/L5Gqv5jR/Screenshot-9.png)
- Tests for path traversal vulnerabilities using various payloads. Results show which payloads were successful.


## XXE Scanner
![Screenshot 10](https://i.postimg.cc/054J9WF3/Screenshot-10.png)
- Identifies XML External Entity (XXE) vulnerabilities by testing custom XML payloads. Results indicate whether the server is vulnerable to XXE attacks.


## CSRF Scanner
![Screenshot 11](https://i.postimg.cc/Hs78n0CL/Screenshot-11.png)
- Checks for Cross-Site Request Forgery (CSRF) vulnerabilities by analyzing forms for CSRF tokens. Results show which forms are vulnerable.


## NTP Scanner
![Screenshot 12](https://i.postimg.cc/fRnt93wf/Screenshot-12.png)
- Scans NTP servers for amplification vulnerabilities, particularly the monlist command. Results indicate whether the server is vulnerable.




## Hidden Files
![Screenshot 13](https://i.postimg.cc/MGzn9hfc/Screenshot-13.png)
- Finds hidden files and directories on a web server using a wordlist. Supports simple or recursive scanning. Results list discovered hidden files.
![Screenshot 14](https://i.postimg.cc/6pr7L9qJ/Screenshot-14.png)


## Brute Force
![Screenshot 15](https://i.postimg.cc/s2Kvqw5T/Screenshot-15.png)
- Performs brute force attacks on web applications using username and password lists. Custom POST parameters and invalid response messages can be configured. Results show valid credentials.


## Open Redirect
![Screenshot 16](https://i.postimg.cc/XJJpbd84/Screenshot-16.png)
- Tests for open redirect vulnerabilities by injecting different payloads. Results show which parameters are vulnerable and redirect destinations.


## CORS Scanner
![Screenshot 17](https://i.postimg.cc/cHb64C9Y/Screenshot-17.png)
- Checks for Cross-Origin Resource Sharing (CORS) misconfigurations, such as wildcard (*) or reflected origins. Results indicate whether CORS policies are secure.


## SSRF Scanner
![Screenshot 18](https://i.postimg.cc/qq6qtrSF/Screenshot-18.png)
- Detects Server-Side Request Forgery (SSRF) vulnerabilities by testing payloads (e.g., localhost, metadata APIs). Results show potential SSRF vulnerabilities.


## Clickjacking
![Screenshot 19](https://i.postimg.cc/14xtwTZ3/Screenshot-19.png)
- Tests for clickjacking vulnerabilities by checking X-Frame-Options and frame-ancestors in CSP headers. Results indicate whether the page is protected.


# Developer Message :)
![Screenshot 20](https://i.postimg.cc/MZnm0Q8C/Screenshot-20.png)
# Technical Specifications

Platform: Cross-platform (Windows, Linux, macOS)

Interface: User-friendly GUI built with Tkinter

Language: Python 3

Dependencies: Requests, BeautifulSoup, dnspython, python-whois, pillow

- At the end of the program's production phase, when we switched from CLI to GUI, we solved some of the problems we experienced with artificial intelligence. With the contribution of Artificial Intelligence, we have created a completely problem-free project. Artificial intelligence was used only in the GUI part.

# Ethical Usage Guidelines

### QaraSEC is designed for legitimate security testing purposes only. 

- Obtain proper authorization before scanning any systems

- Comply with all applicable laws and regulations

- Use the tool responsibly and ethically

- Not use the tool for malicious purposes

The developer assumes no liability for misuse of this software.



## Q: How do I access the open source code of this Tool?
- Reaching me via my e-mail address will be enough for this. You can find my e-mail address in the Profile section. In order to obtain the Open Source code, I will ask for a portfolio that proves that you are a Developer.

