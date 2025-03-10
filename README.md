# HACKBOX

HACKBOX is a web security testing lab made using Flask for budding security enthusiasts to learn about various web 
vulnerabilities. Inspired by DVWA, the Blogger have tried their best to regenerate various web vulnerabilities

The application is solely made for educational purpose and to learn web hacking in a legal environment. 

Read more about it [here](https://singh-simardeepsingh99.medium.com/tiwap-3a8b70043ce9)

## Disclaimer

We highly recommend installing the lab on a Virtual Machine instead of a live web server (Internal or External).

We do not take responsibility for the way in which anyone uses this application (TIWAP). 
The application has been made for educational purpose only and should not be used maliciously. 
If your web servers are compromised due to installation of this application, 
it is not our responsibility, it is the responsibility of the person/s who uploaded and installed it.


## Setup and Installation
To keep the installation and setup easy, we have configured everything for you. All you need is Docker on your system.

Once you are done with docker installation, run the following commands. 

> git clone https://github.com/Art1193/HACKBOX <br/>
> cd HACKBOX <br/>
> docker-compose up

<strong>Note: It works only on Linux as of now and windows compatibility is work under progress </strong>

Once the lab is started, you can log in using the default credentials.<br/>
Username: `admin` <br/>
Password: `admin`

## Tech Stack

Front-End: HTML, CSS and JavaScript <br/>
Back-End: Python - Flask <br/>
Databases: SQLite3 and MongoDB

## Vulnerabilities

Currently, we have 22 vulnerabilities in the lab. All listed below:

- SQL Injection
- Blind SQL Injection
- NoSQL Injection
- Command Injection
- Business Logic Flaw
- Sensitive Data Exposure
- XML External Entities
- Security Misconfiguration
- Reflected XSS
- Stored XSS
- DOM Based XSS
- HTML Injection
- Improper Certificate Validation
- Hardcoded Credentials
- Insecure File Upload
- Brute Force
- Directory Traversal
- Cross-Site Request Forgery (CSRF)
- Server-Side Request Forgery (SSRF)
- Server-Side Template Injection (SSTI)
- JWT Token
- Insecure Deserialization

Each vulnerability is having 3 difficulty levels, namely Low, Medium and Hard. 
These levels can be set from the settings page.


<strong>Happy Hacking! :)</strong>

