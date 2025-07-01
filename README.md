# 🧪 HA: Forensics – VulnHub Investigation Walkthrough

A complete digital forensic analysis and CTF-style exploitation exercise conducted on the **HA: Forensics** virtual machine from VulnHub. This investigation simulates a real-world cyber forensic scenario involving compromised systems, hidden artifacts, privilege escalation, and disk image analysis.

---

## 📝 Summary

This repository contains a full step-by-step walkthrough and documentation for investigating the HA: Forensics machine, demonstrating capabilities in:

- Bootloader manipulation and root access recovery
- FTP enumeration and file extraction via anonymous login
- Steganography detection and extraction (JPEG)
- Forensic disk image mounting and analysis using Autopsy
- User privilege escalation through misconfigurations
- Data decryption and evidence recovery

---

## 🧩 Flags Captured

| Flag # | Description | Method Used |
|--------|-------------|-------------|
| Flag 1 | Hidden message in JPEG | Steghide |
| Flag 2 | Sensitive file via FTP access | Anonymous FTP login |
| Flag 3 | Evidence in disk image | Autopsy forensic analysis |
| Flag 4 | Root-level access | Base64 decode + sudo misconfig |

---

## 🔧 Tools Used

- **Metasploit Framework** – for enumeration & scanning
- **Autopsy** – for disk image forensic analysis
- **Steghide** – for hidden data extraction
- **fcrackzip** – for password-protected zip cracking
- **GPG & JohnTheRipper** – for encrypted key cracking
- **SimpleHTTPServer** – for file transfer over HTTP
- **Linux Privilege Escalation Techniques**

---

## 📄 Documentation

- [HA Forensics.docx](./HA%20Forensics.docx) – Full technical report with screenshots and explanations
- `README.md` – Summary of techniques and tool usage

---

## 📌 Highlights

- ✅ Realistic Linux boot exploitation via GRUB tampering
- ✅ Deep forensic investigation of `.001` image files
- ✅ Privilege escalation to root using default sudo permissions
- ✅ Clear documentation and artifact recovery

---

## 🔗 Source

Target VM: [HA: Forensics – VulnHub](https://www.vulnhub.com/entry/ha-forensics,764/)

---

