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

### Usage
Run JTR on sample hashes:
```bash
john examples/sample_hashes.txt
