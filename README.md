![Key Kong](images/key_kong.png)

# WifiDeAuth
# Wi-Fi Security Tools

This collection of Python scripts utilizes the Scapy library to perform various Wi-Fi network operations including scanning for access points and devices, capturing probe requests, and executing deauthentication attacks. These tools are designed for educational purposes and network security testing in authorized environments.

## Requirements

- A Linux-based system with wireless capabilities.
- Python 3.x installed.
- Scapy library installed.
- Pandas library installed.
- A network interface capable of monitor mode.

## Installation

1. Ensure Python 3.x is installed on your system. You can download it from the official website or install it using your distribution's package manager.
2. Install Scapy and Pandas using pip:

   ```
   pip install scapy pandas
   ```

3. Clone this repository or download the scripts directly to your local machine.

## Levels and Challenges

Each level presents a different challenge related to web security. Here's a brief overview of each level:

1. **Basic HTML Form without Security**: Hardcoded credentials in JavaScript.
2. **Client-Side Validation**: Credentials validated only on the client side.
3. **Simple Server-Side Validation**: Credentials checked on the server side, but communication is in plaintext.
4. **Insecure Direct Object References (IDOR)**: Access control flaws allow users to access data belonging to other users.
5. **Broken Authentication**: Vulnerabilities in the authentication mechanism allow unauthorized access.
6. **SQL Injection**: Improperly sanitized inputs allow SQL code execution.
7. **Cross-Site Scripting (XSS)**: Reflective or stored XSS vulnerabilities in user inputs or messages.
8. **Cross-Site Request Forgery (CSRF)**: Lack of CSRF tokens makes the site vulnerable to CSRF attacks.
9. **File Inclusion and Upload Vulnerabilities**: The application allows unverified file uploads or includes files from untrusted sources.
10. **Server Misconfigurations and Advanced Exploitation**: Misconfigured server settings or outdated software leading to unauthorized access or information disclosure.

## Tools and Techniques

Participants are encouraged to utilize various tools and techniques to solve each challenge. Some of the recommended tools include:

- Browser Developer Tools
- Burp Suite
- sqlmap
- BeEF (Browser Exploitation Framework)
- Nikto
- Nmap
- DirBuster
- gobuster

## Disclaimer

These challenges are for educational purposes only. It's essential to have proper authorization before testing vulnerabilities on any system. Always ensure you have permission to conduct security testing on any web application or network.

## Acknowledgments

Special thanks to the creators of Kali Linux and the various security tools used in this project for their invaluable contributions to the field of cybersecurity.

