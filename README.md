# 🔐 NetworkWalks B083 — Week 3 PM1 & PM2: Password Security & Authorized Password Recovery



![Cybersecurity](https://img.shields.io/badge/Focus-Cybersecurity-red)




![NetworkWalks](https://img.shields.io/badge/Training-NetworkWalks-blue)




![Batch](https://img.shields.io/badge/Batch-B083-purple)




![Week](https://img.shields.io/badge/Week-03-orange)




![Topic](https://img.shields.io/badge/Topic-Password%20Security-black)



## 📌 Project Overview

This repository documents my Week 3 practical cybersecurity exercises as part of the **NetworkWalks Cybersecurity & Ethical Hacking Internship — Batch B083**.

The practical focused on understanding how password-protected PDF documents can be tested in a controlled laboratory environment using **dictionary-based password recovery techniques**.

The exercises provided practical exposure to:
- Password hashing
- PDF password protection
- Hash extraction
- Dictionary-based password recovery
- John the Ripper
- Wordlists
- Password strength
- Ethical password-security testing
- Capture-the-Flag (CTF) style challenges

All activities were performed against intentionally provided training files, within the authorized NetworkWalks learning environment.

---

## 🎯 Objectives

1. Understand how password-protected PDF files use password-derived hashes.
2. Extract password hashes from protected PDF documents.
3. Understand the concept of dictionary-based recovery.
4. Use an authorized password-recovery laboratory tool to test password hashes.
5. Observe how wordlists can be used to test possible passwords.
6. Verify recovered passwords by opening the corresponding protected PDF files.
7. Capture the flags provided by the training environment.
8. Understand why weak and commonly used passwords are vulnerable to dictionary-based recovery.
9. Develop practical cybersecurity skills in a controlled environment.

---

## 🧠 Concepts Covered

### 1. Password Hashing
A password hash is a transformed representation of a password. Instead of storing a password directly, many systems store a derived value used for verification.

These exercises demonstrate that password security doesn't depend on the hashing algorithm alone — the password itself matters. Weak or commonly used passwords can often be identified through guessing techniques.

### 2. Dictionary-Based Password Recovery
This technique tests possible passwords from a predefined wordlist, rather than attempting every possible combination — targeting words and patterns users are more likely to choose.

```text
Password Hash
      │
      ▼
Candidate Password
      │
      ▼
Hash Candidate
      │
      ▼
Compare With Target Hash
      │
   ┌──┴──┐
   │     │
 Match  No Match
   │     │
   ▼     ▼
Success Continue


🛠️ Tools Used
Tool / Resource
Purpose
NetworkWalks Password Recovery Lab
Controlled password-security exercise
NetworkWalks Hash Calculator
Hash-related laboratory exercise
PDF Hash Extraction Tool
Extracting password hashes from protected PDFs
John the Ripper
Password-recovery and hash-testing tool
Wordlists
Providing candidate passwords
Protected PDF files
Authorized training targets
Microsoft Edge / Web Browser
Accessing the training laboratory
Windows
Host environment


🔬 Practical Methodology
Phase 1 — Password Recovery Lab
The NetworkWalks password-recovery laboratory was used to understand dictionary-based password testing. The interface provided a PDF hash input area, wordlist selection, a recovery-progress display, and password-match results.
Phase 2 — Dictionary-Based Testing
The supplied training wordlists were used to test candidate passwords against the provided PDF password hashes. The lab displayed recovery progress and flagged a matching candidate when the correct password was found — demonstrating the effectiveness of dictionary-based recovery against weak or predictable passwords.
Phase 3 — PDF Password Verification
Recovered passwords were used to open the corresponding protected PDF files. Successful access confirmed the recovered value wasn't just a hash match, but an actual working password.


🖥️ Evidence of Successful Password Recovery
Three separate password-recovery exercises were completed:
Exercise 1 — First training PDF password recovered via dictionary-based recovery; verified against the protected PDF.
Exercise 2 — Second training PDF tested using the supplied wordlist; correct candidate identified and document accessed.
Exercise 3 — Third training PDF tested and recovered; verified by opening the protected document.
Note: Recovered training passwords are intentionally not reproduced in this README. Screenshots in this repository provide the visual evidence of the results (with sensitive values redacted).


🔑 John the Ripper Verification
John the Ripper was also used as part of the practical. Screenshots show it processing PDF password hashes, including:
The imported PDF hash
The recovered password
PDF as the identified format
A completed recovery status
A successful recovery result
The final status confirmed the supplied hash had been successfully recovered.
🏁 Capture The Flag Results
The practical also included CTF-style objectives. Screenshots provide evidence of the captured flags for the individual PDF challenges.
Actual flag values are intentionally omitted / redacted from this README and screenshots for security and documentation purposes.
📸 Evidence
The repository contains screenshots documenting:
Password Recovery Results — PDF hash input, selected wordlists, dictionary-based recovery progress, candidate testing, successful matches
PDF Verification — Recovered passwords being used to access protected training PDFs
John the Ripper — Imported hashes, recovered passwords, PDF hash format, completion status
Captured Flags — Successful completion of the three training challenges



📊 Results Summary
Exercise
Technique
Result
PDF Challenge 1
Dictionary-Based Recovery
✅ Successful
PDF Challenge 2
Dictionary-Based Recovery
✅ Successful
PDF Challenge 3
Dictionary-Based Recovery
✅ Successful
PDF Verification
Password Testing
✅ Successful
John the Ripper
Hash Recovery
✅ Successful
CTF Challenge 1
Flag Capture
✅ Captured
CTF Challenge 2
Flag Capture
✅ Captured
CTF Challenge 3
Flag Capture
✅ Captured


🔐 Security Lessons Learned
Password Predictability Matters — Passwords based on common words or simple patterns are vulnerable to dictionary-based recovery.
Wordlists Can Be Effective — A well-constructed wordlist significantly reduces the guesses needed to identify weak passwords.
Length and Complexity Matter — Longer, unique passwords provide a much larger search space than short, predictable ones.
Hashes Alone Don't Guarantee Safety — Hashing is important, but security also depends on how passwords are chosen and protected.
Password Testing Should Be Authorized — These tools are legitimate in penetration tests, labs, CTFs, personal systems, and training environments — never without explicit permission.


🧪 Practical Skills Demonstrated
🔐 Password security · 🔎 Hash analysis · 📄 PDF password protection · 🧩 Dictionary-based recovery · 📚 Wordlists · 🛠️ John the Ripper · 🧪 Security testing · 🏁 CTF methodology · 📸 Technical documentation · ⚖️ Ethical cybersecurity practices


💡 Key Takeaways
A password that seems difficult to guess manually may still exist in a common password dictionary. From a defensive standpoint, organizations should encourage users to:
Use long, unique passwords
Avoid common words and predictable patterns
Avoid password reuse
Use password managers where appropriate
Implement strong authentication controls
Apply secure password-storage practices
Monitor authentication systems for suspicious activity


⚠️ Ethical & Legal Disclaimer
This project was performed strictly as part of an authorized cybersecurity training exercise. These techniques should only be used against:
Systems you own
Files you have explicit permission to test
Authorized penetration-testing targets
Cybersecurity training environments
CTF challenges
Unauthorized password cracking or access to protected information may violate laws, policies, or the rights of system owners. Always obtain appropriate authorization before performing security testing.


📂 Repository Structure
Exact filenames may vary depending on how the evidence files are organized.


🎓 Training Information
Field
Details
Program
NetworkWalks Cybersecurity & Ethical Hacking Internship
Batch
B083
Week
Week 3
Practical
PM1 & PM2
Focus
Password Security & Authorized Password Recovery
Environment
Authorized Training Lab
Repository
GitHub


👨🏽‍💻 Author
Oretuyi Babajide Chinedu
Computer Science Undergraduate · Cybersecurity Enthusiast
NetworkWalks Cybersecurity Internship — Batch B083
GitHub: @oretuyibabajide3-bit

🚀 Conclusion
The Week 3 password-security practical provided hands-on experience with password hashing, dictionary-based recovery, PDF password verification, wordlists, and John the Ripper. Successful recovery and verification of the training PDF passwords, together with captured CTF flags, demonstrated the practical impact of weak and predictable passwords — and reinforced the importance of strong password practices and responsible use of cybersecurity tools.
