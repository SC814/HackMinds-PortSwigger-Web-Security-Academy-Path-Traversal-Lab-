# Building practical skills in Web Application Security, one lab at a time.

As part of my ongoing Cybersecurity and Ethical Hacking journey, I successfully completed the **File Path Traversal — Simple Case** lab on PortSwigger Web Security Academy.

This hands-on exercise focused on identifying a file path traversal vulnerability in a web application's product image functionality and understanding how improper handling of user-controlled file paths can lead to unauthorized file access.

Rather than simply memorizing payloads, I focused on understanding the underlying logic, how directory traversal works, and why insufficient server-side validation can create security risks.

### 🔍 Technical Skills Practiced

- **Web Application Testing:** Examining file-loading functionality and identifying potential attack surfaces.
- **HTTP Request Analysis:** Understanding how user-controlled parameters influence server-side behavior.
- **Path Traversal Testing:** Exploring directory navigation sequences such as `../`.
- **Linux File System Fundamentals:** Understanding file paths and the purpose of `/etc/passwd`.
- **Response Analysis:** Examining server responses to verify unauthorized file disclosure.
- **Security Awareness:** Understanding the importance of path validation, access controls, and least-privilege permissions.

### 💡 Key Learning

This lab reinforced an important security principle: **user-controlled input should never be trusted when determining which files a server can access.**

A seemingly simple filename parameter can become a security weakness when an application fails to restrict access to its intended directory.

Understanding why the vulnerability occurs — rather than relying solely on payloads — is essential to developing effective security testing and vulnerability analysis skills.

### 🛠️ Lab Details

📌 **Platform:** PortSwigger Web Security Academy  
🎯 **Lab:** File Path Traversal — Simple Case  
🧪 **Vulnerability:** Path Traversal / Directory Traversal  
💻 **Target:** Product image functionality  
✅ **Outcome:** Successfully retrieved the contents of `/etc/passwd` and completed the lab  
📚 **Focus Areas:** Web Application Security | Linux Fundamentals | Vulnerability Analysis

### 🚀 What's Next?

I'm continuing to work through hands-on security labs, strengthening my understanding of web vulnerabilities, and documenting my progress through practical write-ups.

My goal is to build a strong technical foundation, improve my analytical and problem-solving skills, and develop the practical knowledge needed for a career in cybersecurity.

Each lab is an opportunity to understand not only how vulnerabilities work, but also how to identify, assess, and prevent them.

**Learn. Practice. Analyze. Document. Improve.** 🔐

🔗 **PortSwigger Learning Resource:**  
https://portswigger.net/web-security/file-path-traversal

#HackMinds #Cybersecurity #WebApplicationSecurity #PathTraversal #EthicalHacking #PortSwigger #AppSec #PenetrationTesting #CybersecurityLearning #LearningInPublic
