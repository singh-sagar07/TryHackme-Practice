# TryHackMe Linux Privilege Escalation Practice

This repository documents my hands-on journey with Linux privilege escalation, based on challenges and methods learned in the TryHackMe "Linux Privilege Escalation" room.

## 🛠️ Techniques Practiced

- **SUID binary exploitation and PATH hijacking**
- **Writable cron job script exploitation**
- **NFS no_root_squash misconfiguration**
- **Linux capabilities misconfiguration investigation**
- **Public Linux kernel exploit research and attempts (e.g., PwnKit/CVE-2021-4034)**
- **Manual troubleshooting of file transfers, compilation, and exploit execution**

## 🚩 Step-by-Step Summary

1. **Enumeration**: Identified vulnerable binaries, permissions, capabilities, and NFS shares (`id`, `find`, `ls`, `getcap`, `showmount`, etc.).
2. **SUID abuses**: Practiced compiling, uploading, and hijacking SUID binaries.
3. **Cron jobs**: Located writable scheduled scripts and injected commands for escalation.
4. **NFS exploitation**: Mounted no_root_squash NFS shares; copied SUID shells for privesc.
5. **Kernel exploits**: Downloaded, transferred, and attempted compilation and execution of CVEs.
6. **Obstacles resolved**: Documented troubleshooting steps for failed downloads, segfaults, file permissions, and environment differences.

## 📚 Learning Outcomes

- Practical insight into real-world Linux privilege escalation scenarios.
- Strong troubleshooting skills for exploit and environment issues.
- Confident use of enumeration and exploitation tools.
- Documentation of research, tool usage, and methodology.

---

**Disclaimer:** This repository is for educational purposes only. Do not attempt on systems you do not own or have explicit permission to test.
