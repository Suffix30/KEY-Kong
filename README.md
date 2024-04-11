![Key Kong](images/key_kong.png)

# COMING SOON 

# Web Security Practice Levels

This project is designed for educational purposes to help individuals understand and practice various web security vulnerabilities. Each level introduces a specific vulnerability, allowing learners to practice detection and exploitation techniques using tools commonly found in Kali Linux.

## Overview

The project consists of 10 levels, each focusing on a different web security vulnerability. From basic HTML form vulnerabilities to advanced server misconfigurations, participants will encounter a wide range of challenges commonly found in real-world web applications.

## Getting Started

To get started with the project, follow these steps:

1. Clone or download the project repository to your local machine.
2. Ensure you have Node.js and npm (Node Package Manager) installed on your system.
3. Navigate to the project directory in your terminal.
4. Install project dependencies by running `npm install`.
5. Start the server by running `node server.js`.
6. Access the levels through your web browser by visiting `http://localhost:3000`.

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

