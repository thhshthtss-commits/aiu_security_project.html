# Secure Web Authentication & Penetration Testing Project
**University:** Alamein International University (AIU)
**Course:** Cybersecurity & Ethical Hacking
## 📝 Project Overview
This project is a secure web application featuring a user registration and login system. It was developed to demonstrate best practices in **Secure Coding** and to test resilience against common web vulnerabilities.

## 🛡️ Implemented Security Features
We have integrated multiple layers of defense to protect user data:
1. **Password Hashing:** Utilizing `bcrypt` to salt and hash passwords before storing them in the SQLite database.
2. **SQL Injection (SQLi) Protection:** Using **Parameterized Queries** to prevent malicious database manipulation.
3. **XSS Defense:** Implementing automatic HTML escaping and input sanitization.
4. **Brute Force Protection:** Account lockout mechanism that triggers after **5 failed login attempts**.
5. **Strong Password Policy:** Mandatory complexity requirements (Minimum 8 characters, including symbols and numbers).

## 🛠️ Tech Stack
- **Language:** Python
- **Framework:** Flask
- **Database:** SQLite
- **Environment:** Google Colab

## ⚖️ Ethical Statement
> "All testing activities were conducted solely on our own application in accordance with ethical and legal guidelines."

---
© 2026 AIU Cybersecurity Team
