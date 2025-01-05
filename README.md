# Top 10 OWASP Scanner
GitHub Python Bash

## Description 
The Top 10 OWASP Scanner is a powerful Bash script designed to automate the process of discovering vulnerabilities in web applications by leveraging Google Dorks related to the OWASP Top 10 vulnerabilities. This tool is ideal for bug hunters, penetration testers, and security researchers who want to quickly identify potential security issues in a target domain.

## Features
OWASP Top 10 Focus: Targets vulnerabilities listed in the OWASP Top 10, including:

Injection

Broken Authentication

Sensitive Data Exposure

XML External Entities (XXE)

Broken Access Control

Security Misconfiguration

Cross-Site Scripting (XSS)

Insecure Deserialization

Using Components with Known Vulnerabilities

Insufficient Logging & Monitoring

Google Dork Integration: Uses the degoogle tool to perform Google Dork searches.

Customizable Dorks: Easily modify or extend the list of dorks to suit your needs.

Clean Output: Provides well-formatted and easy-to-read results.

Supports Multiple Domains: Scan multiple domains by running the script with different inputs.
## Installation
### Prerequisites
Python 3.7+: Required for the degoogle tool.

Bash 5.0+: Required to run the script.

Steps
Clone the repository:

bash
Copy
git clone https://github.com/your-username/top10-owasp-scanner.git
cd top10-owasp-scanner
Install the degoogle tool:

bash
Copy
pip install degoogle
Make the script executable:

bash
Copy
chmod +x top10_owasp_scanner.sh
Usage
## Basic Usage
Run the script with a target domain:

bash
Copy
./top10_owasp_scanner.sh example.com
Example Output
Copy
==============================================
[+] Testing dork: inurl:search.php?q=
----------------------------------------------
No results found.
==============================================

==============================================
[+] Testing dork: inurl:query.php?id=
----------------------------------------------
No results found.
==============================================

==============================================
[+] Testing dork: intitle:"index of" "admin"
----------------------------------------------
No results found.
==============================================
