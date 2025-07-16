# 🧠 CTF101 Master Toolkit
A curated list of CTF tools categorized by function, purpose, and practical lessons — perfect for beginners, educators, and ethical hackers.

---

## 🔍 Reconnaissance & Enumeration

| Tool           | Purpose                            | Lesson / Flag Type             |
|----------------|------------------------------------|-------------------------------|
| nmap           | Port scanning, OS detection        | Open ports, OS fingerprinting |
| whatweb        | Web tech fingerprinting            | CMS detection, server type    |
| theHarvester   | OSINT on domains/emails            | Subdomain discovery           |
| dnsenum        | DNS enumeration                    | Zone transfers, hidden hosts  |
| enum4linux     | SMB enumeration                    | Windows shares, user lists    |

---

## 🌐 Web Exploitation

| Tool         | Purpose                            | Lesson / Flag Type               |
|--------------|------------------------------------|----------------------------------|
| Burp Suite   | Web proxy & vuln scanner           | XSS, SQLi, auth bypass           |
| OWASP ZAP    | Automated web scanner              | Same as Burp, great for beginners|
| sqlmap       | SQL injection automation           | Dump DBs, bypass auth            |
| nikto        | Web server vuln scanner            | Misconfigs, outdated software    |
| ffuf         | URL and param fuzzing              | Hidden endpoints, brute paths    |

---

## 🔐 Brute Force & Authentication

| Tool     | Purpose                       | Lesson / Flag Type             |
|----------|-------------------------------|-------------------------------|
| hydra    | Brute-force login credentials | Weak passwords, SSH/FTP access|
| john     | Password hash cracking        | Cracked `/etc/shadow` entries |
| hashcat  | GPU-based password cracking   | MD5, SHA1, bcrypt hashes       |

---

## 🔑 Cryptography & Hashes

| Tool            | Purpose                        | Lesson / Flag Type              |
|-----------------|--------------------------------|---------------------------------|
| CyberChef       | Encoding, decoding, crypto     | Base64, XOR, JWT, etc.          |
| Ciphey          | Auto-decrypt unknown formats   | Substitution ciphers            |
| RsaCtfTool      | RSA attacks & decoding         | Low exponent vulnerabilities    |
| hash-identifier | Detect hash type               | Recognize MD5, bcrypt, SHA      |

---

## 🧬 Reverse Engineering

| Tool      | Purpose                     | Lesson / Flag Type            |
|-----------|-----------------------------|-------------------------------|
| Ghidra    | Binary disassembler         | Find hardcoded flags          |
| radare2   | Binary analysis & patching  | Logic flaws, patching exec    |
| pwntools  | Exploit dev in Python       | Buffer overflows, payloads    |
| gdb + gef | Debug binaries              | Memory analysis, exploit steps|

---

## 🧪 Forensics & Steganography

| Tool       | Purpose                          | Lesson / Flag Type           |
|------------|----------------------------------|------------------------------|
| binwalk    | Firmware analysis & carving      | Embedded files, hidden data  |
| steghide   | Image/audio steganography        | Hidden data in media         |
| exiftool   | Metadata extraction              | Flags in file metadata       |
| zsteg      | LSB stego detection              | Pixel-level data recovery    |

---

## 📡 Network & Shell

| Tool       | Purpose                          | Lesson / Flag Type             |
|------------|----------------------------------|--------------------------------|
| Wireshark  | Packet capture & analysis        | Creds in plaintext, DNS leaks  |
| tcpdump    | CLI network sniffer              | Quick traffic checks           |
| netcat     | Reverse shell & listener         | Shell access, file transfer    |
| socat      | Advanced shell relay             | Encrypted reverse shells       |

---

## 🛠️ Misc & Automation

| Tool         | Purpose                         | Lesson / Flag Type             |
|--------------|----------------------------------|--------------------------------|
| AutoRecon    | Automated full recon             | Enumeration + vuln summary     |
| CTFd         | Host your own CTF platform       | Training challenges for others |
| Python       | Scripting & automation           | Custom exploits and scans      |

---

## 🎓 Practice Platforms

| Site           | Focus Area            |
|----------------|-----------------------|
| TryHackMe       | Guided walkthroughs   |
| HackTheBox      | Realistic CTF labs    |
| OverTheWire     | Linux & networking    |
| CTF101.org      | Tool-based lessons    |
| PicoCTF         | Youth-friendly CTFs   |

---

## ✨ Notes
- Expand this doc with flags, walkthroughs, and links to your own tools (VaultApp, Slade_MITM, etc.)
- Modularize it inside CopilotKali as `teach_modules/ctf_basics.md`

