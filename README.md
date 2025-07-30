# CODTECH-TASK3


PENETRATION TESTING TOOLKIT

Project Overview:
The Penetration Testing Toolkit is a Python-based modular scanner designed to help identify common security vulnerabilities in web applications. This educational toolkit is ideal for beginners and intermediate learners in ethical hacking, cybersecurity, and information security domains.

INSTRUCTIONS
Objective:
Build a toolkit with multiple modules (e.g., Port Scanner, Brute-Forcer) for penetration testing.

Deliverable:
- A Python-based modular toolkit
- Includes detailed documentation for setup, usage, and demonstration
- Command-line interface (CLI) for easy interaction


Toolkit Modules:

| Module Name           | Description                                         |
|-----------------------|---------------------------------------------------  |
| 🔍 Port Scanner       | Scans target host for open ports using sockets      |
| 🔐 Brute Forcer       | Performs dictionary-based password brute-force      |
| 🧠 Banner Grabber     | Fetches banner info from open ports                 |
| 💉 SQL Injection Scan | Checks for SQLi vulnerabilities in URLs             |
| ⚠️ XSS Scanner        | Detects basic reflected XSS payload vulnerabilities |


 Technologies Used:
- Python 3.x
- requests
- socket
- bs4 (BeautifulSoup)
- colorama

Sample Output:
Starting Web Vulnerability Scan...
Testing SQL Injection on: http://testphp.vulnweb.com/artists.php?artist=1
SQL Injection Vulnerability Detected with payload: ' OR 1=1 --
 Testing XSS on: http://testphp.vulnweb.com/artists.php?artist=1
✅ No XSS Vulnerability Detected.
✅ Scan Complete.




