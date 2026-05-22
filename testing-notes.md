# Testing Notes

## Project: Web Application Security Assessment

This file is used to record my testing process, evidence, and follow-up tasks while assessing a controlled web application environment.

---

## Day 1: Environment Setup and Initial Reconnaissance

### Setup Details

Target Environment IP: 
Hosts File Updated: Yes  
Web Application Opened: Yes  
Burp Suite Capturing Traffic: Yes  

---

### What I Completed

- Started the target web application environment.
- Started the AttackBox testing machine.
- Added the target IP and local domain to the AttackBox `/etc/hosts` file.
- Confirmed that the local web application domain resolved to the target IP.
- Opened the web application successfully in the AttackBox browser.
- Opened Burp Suite and used Burp Browser to access the application.
- Fixed the Burp Browser sandbox issue by allowing Burp’s browser to run without a sandbox.
- Confirmed that Burp Suite was capturing HTTP traffic in `Proxy > HTTP history`.
- Reviewed the initial homepage response.
- Reviewed the JavaScript bundle response to understand the application structure.

---
