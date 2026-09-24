# -NETWORKWALKS-NAFISAH-B083-WK3--PM1-PM2
# Password cracking with JTR and NW tools
# 🔐 JTR Password Hacking (Educational)

This repository demonstrates how to use **John the Ripper (JTR)** for password auditing and security awareness in **authorized environments only**.  
⚠️ Unauthorized password cracking is illegal. This project is strictly for **educational, research, and penetration testing practice** with proper authorization.This project documents a controlled cybersecurity lab focused on recovering passwords from protected PDF files by extracting PDF hashes and performing dictionary attacks. The exercise compares a local John the Ripper (JTR) / Johnny workflow with the Networkwalks web-based tools.

---

## 📂 Repository Structure
- `docs/` → Guides and documentation  
- `examples/` → Sample hash files for practice  
- `scripts/` → Helper scripts for running JTR  
- `results/` → Benchmark and test outputs  

---

## 🚀 Getting Started

### Installation
Follow the official JTR installation guide: [John the Ripper Documentation](https://www.openwall.com/john/)

Objectives
Demonstrate the process of recovering passwords from protected PDF files by extracting their hashes and using dictionary attacks.
Compare the methodology of a local John the Ripper (JTR) installation with the web-based Network walks tools.

# Methodology
__
## Module 1 — John the Ripper (JTR)
Hash Extraction: The online tool at onlinehashcrack.com was used to extract the $pdf$ hashes from the locked PDF files.
Preparation: The extracted hash values were saved into .txt files for local processing.
Cracking Process: The hash files were imported into the Johnny GUI, which provides a graphical interface for JTR, and a dictionary attack was executed to recover the passwords.

## Module 2 — Networkwalks Tools

Hash Extraction: The target PDF files were uploaded to the Networkwalks Hash Calculator to parse the files and extract their hashes within the web browser.
Cracking Process: The extracted hashes were supplied to the Networkwalks Password Cracker, where its built-in wordlist attack was executed to recover the passwords.
Results

# Mitigation & Remediation Strategies
----

To reduce the likelihood of successful offline dictionary attacks, the following controls and policies should be implemented:

### 1. Enforce Strong Passphrases

Dictionary attacks rely heavily on common words and simple alphanumeric sequences. Long passphrases with high entropy make dictionary and brute-force attacks substantially more difficult.

### 2. Avoid Predictable Patterns

Users should avoid standard keyboard walks such as 1qaz2wsx or appending numbers to common words such as password1, because modern wordlists commonly test these patterns.

### 3. Use Strong Encryption Standards

Files should be secured using robust encryption algorithms such as AES-256 rather than legacy encryption methods, increasing the effort required for cracking attempts.
 passwords.

## Conclusion

The exercises demonstrated that predictable passwords such as password1 and 1qaz2wsx can be recovered using standard wordlists and readily available tools. The results reinforce the importance of strong password selection, avoidance of predictable patterns, and appropriate document-encryption controls when protecting files against offline hash-cracking attempts.
___
Project: PDF Hash Cracking Analysis
Training: Networkwalks Internship / B083C
Author: Nafisat Omehi Dauda 
