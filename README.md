# PDF Password Recovery Lab 🔐

**A Practical Cybersecurity Exercise | Kali Linux | Password Security**

## 📌 Project Overview

This project documents a practical exercise on recovering passwords from password-protected PDF documents in an authorized laboratory environment.

The exercise involved exploring PDF password protection, hash extraction, hash analysis, and password recovery using different cybersecurity tools.

The primary goal was to gain hands-on experience with password security and understand how weak passwords can be vulnerable to password-recovery techniques.

## 🎯 Objectives

- Understand PDF password protection and encryption.
- Explore PDF hash extraction and analysis.
- Practise using John the Ripper GUI.
- Explore online hash-cracking platforms.
- Understand cryptographic hash calculations.
- Perform password recovery on personally owned PDF documents.
- Verify recovered passwords.
- Understand the importance of strong passwords.

## 🛠️ Tools and Technologies

| Tool | Purpose |
|---|---|
| Kali Linux | Testing environment |
| John the Ripper GUI (JTR GUI) | Password recovery and hash analysis |
| OnlineHashCrack | Online hash analysis and recovery |
| NetworkWalks Hash-Calculator | Hash calculation |
| NetworkWalks Password Cracker | Password recovery |
| PDF documents | Authorized test files |

## 🧪 Laboratory Environment

- **Operating System:** Kali Linux
- **Working Directory:** `~/PDF-Lab`
- **Lab Type:** Controlled cybersecurity laboratory
- **Target:** Personally owned password-protected PDF documents

### Test Documents

The following documents were used during the practical:

- `lock.pdf`
- `lock1.pdf`
- `lock2.pdf`

## ⚙️ Methodology

### 1. PDF Identification

The first step involved identifying the PDF documents and checking their file types using the Linux terminal.

Command:

```bash
file lock.pdf lock1.pdf lock2.pdf
```

This confirmed that the three files were recognized as PDF documents.

### 2. Hash Extraction

The next stage involved obtaining the relevant password-verification information associated with the protected PDF documents.

John the Ripper GUI and OnlineHashCrack were used during the hash extraction and analysis process.

### 3. Hash Calculation and Analysis

NetworkWalks Hash-Calculator was used to perform hash calculations and examine cryptographic hash values.

This provided practical exposure to hash generation and the role of cryptographic functions in information security.

### 4. Password Recovery

The password-recovery stage involved using:

- John the Ripper GUI
- OnlineHashCrack
- NetworkWalks Password Cracker

These tools were explored to understand different approaches to password recovery.

### 5. Password Verification

After the recovery process, the recovered password was used to verify access to the protected PDF document.

The practical successfully recovered the password of the tested document.

## 📸 Practical Evidence

Screenshots from the laboratory exercise are included below.

### PDF Identification

*Evidence of identifying the password-protected PDF documents using Kali Linux.*

<img width="654" height="364" alt="p1" src="https://github.com/user-attachments/assets/ad838db5-fcb2-4883-bfa0-2ef8dc6497df" />


### Hash Analysis

*Evidence of the hash extraction and analysis process.*

<img width="622" height="551" alt="pdfcrack" src="https://github.com/user-attachments/assets/c43e706d-cb9d-44cd-afe4-022db5da2179" />


### Password Recovery

*Evidence of the password-recovery process using the selected tools.*

<img width="622" height="551" alt="pdfcrack" src="https://github.com/user-attachments/assets/4bce59e9-ffda-4ec6-bf35-ab974bfd6c74" />


### Successful Verification

*Evidence confirming that the recovered password successfully opened the protected PDF.*

<img width="278" height="391" alt="flag3" src="https://github.com/user-attachments/assets/8433c104-6faa-4d05-a3fe-5e34a3dd4d81" />
<img width="425" height="403" alt="image" src="https://github.com/user-attachments/assets/2df52d4b-c30e-4862-a807-d2c6fda49241" />
<img width="282" height="393" alt="flags2" src="https://github.com/user-attachments/assets/6a06610e-17e9-424a-978a-47a4bde908f9" />



## 📚 Key Learnings

Through this practical exercise, I gained experience in:

- Identifying PDF documents using Linux commands.
- Understanding PDF password protection.
- Exploring hash extraction and analysis.
- Using John the Ripper GUI.
- Working with online password-recovery platforms.
- Understanding cryptographic hash calculations.
- Recovering and verifying PDF passwords.
- Recognizing the importance of strong password policies.

## 🔐 Security Recommendations

1. Use long, unique passwords when protecting sensitive PDF documents.
2. Avoid predictable passwords and commonly used phrases.
3. Store important passwords securely using a password manager.
4. Avoid submitting confidential documents or password hashes to untrusted online services.
5. Maintain secure backups of important documents and their credentials.

## 📝 Conclusion

This practical exercise provided valuable hands-on experience in PDF password recovery and password security.

Working with Kali Linux, John the Ripper GUI, OnlineHashCrack, and NetworkWalks tools helped me better understand the relationship between PDF encryption, hash analysis, and password recovery.

It also reinforced the importance of strong passwords and appropriate security practices when protecting sensitive documents.

## ⚠️ Disclaimer

This project was conducted strictly for educational purposes using personally owned PDF documents.

All activities were performed within an authorized laboratory environment. The techniques demonstrated are intended for legitimate password recovery and cybersecurity education only.

---

**Project by Devarotech**

*Learning. Building. Securing.*
