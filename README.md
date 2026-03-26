# XSS Testing on OWASP Juice Shop

## 📌 Project Overview
This project demonstrates basic Cross-Site Scripting (XSS) testing on a vulnerable web application.

## 🎯 Objectives
- Identify input fields in a web application
- Test basic XSS payloads
- Observe application response and behavior

## 🛠 Tools Used
- OWASP Juice Shop
- Web Browser (Chrome)
- Developer Tools (F12)

## 🔍 Testing Performed
- Identified input fields such as search bar and login form
- Tested Reflected XSS using payloads like:
  - <script>alert('XSS')</script>
  - <img src=x onerror=alert('XSS')>
- Observed input sanitization and encoding behavior

## 📊 Results
- Application did not execute script payloads
- Input was properly sanitized and encoded
- No XSS vulnerability found using basic payloads

## 📄 Report
Detailed report is available in the repository.

## 🚀 Learning Outcome
Gained practical understanding of:
- XSS (Cross-Site Scripting)
- Input validation
- Output encoding
- Web application security basics
