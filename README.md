<!-- header -->
<div align="center">

```
 ██████╗ ██████╗ ██╗     ██████╗      ██████╗ ███████╗██╗      █████╗ ██╗   ██╗
██╔════╝██╔═══██╗██║     ██╔══██╗     ██╔══██╗██╔════╝██║     ██╔══██╗╚██╗ ██╔╝
██║     ██║   ██║██║     ██║  ██║     ██████╔╝█████╗  ██║     ███████║ ╚████╔╝ 
██║     ██║   ██║██║     ██║  ██║     ██╔══██╗██╔══╝  ██║     ██╔══██║  ╚██╔╝  
╚██████╗╚██████╔╝███████╗██████╔╝     ██║  ██║███████╗███████╗██║  ██║   ██║   
 ╚═════╝ ╚═════╝ ╚══════╝╚═════╝      ╚═╝  ╚═╝╚══════╝╚══════╝╚═╝  ╚═╝   ╚═╝  
```

<div align="center">
<sub><code>30 years of backwards compatibility. &nbsp;·&nbsp; 0 years of regret. &nbsp;·&nbsp; that's the attack surface. &nbsp;·&nbsp; cold-relay maps it.</code></sub>

</div>

---

## `$ whoami`

I have one thesis: **every system trusts itself more than it should.**

Active Directory has been proving this since 1999. LLMs are catching up fast. I work both sides — Windows trust architecture and AI alignment as an attack surface — because the failure mode is identical. Confidence outpacing verification.

The rest is just tooling.

---

## Flagship — `cold-relay`

> *Identity paths, proven cold.*

Single-binary AD assessment tool written in Go. Collects authentication evidence across LDAP, Kerberos, SMB, DNS, GPO, delegation, and AD CS — then builds an offline attack graph from what it actually observed.

No percentages. No vibes. Findings are stamped `validated`, `likely`, `theoretical`, `blocked`, or `insufficient_visibility`. Because LDAP visibility and exploitability are not the same thing, and tools that pretend otherwise get people fired.

**[→ thechosenone-shall-prevail/cold-relay](https://github.com/thechosenone-shall-prevail/cold-relay)**

---

## Other Work

| | |
|--|--|
| [**infiltrator**](https://github.com/thechosenone-shall-prevail/infiltrator) | RAT with a self-healing process mesh, polymorphic build pipeline, and a custom C2 protocol over AES-256-GCM. Actually deployed, not just committed. |
| [**BASTION 2026**](https://github.com/thechosenone-shall-prevail/bastion) | CTF I designed and ran. Linux web target + Windows AD. People struggled. That was the point. |
| [**NextGenFirewall**](https://github.com/thechosenone-shall-prevail/NextGenFirewall) | Built DPI + EDR + HIPS to understand what it misses. Spoiler: a lot. |
| [**VULNNET-WINDOWS**](https://github.com/thechosenone-shall-prevail/VULNNET-WINDOWS) | Anon SMB → AS-REP → Kerberoast → DCSync. Boring path. Still works every time. |

---

## Stack

```
Go · Python · Kali · Wireshark · BloodHound · Metasploit · Burp Suite
Windows Internals · Active Directory · Kerberos · LDAP · SMB · AWS IAM
C2 Design · LLM Red Teaming · Offensive Tooling
```

---

## `$ cat creds.txt`

```
HackTheBox            Top 0.5%      — active
eJPT                  Certified     — rookie cert, not a rookie
Smart India Hackathon Finalist
BASTION 2026          CTF Organizer — designed it, ran it, watched people suffer
```

---

<div align="center">

[![Instagram](https://img.shields.io/badge/@no__auth__root-FF0040?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/no_auth_root)
&nbsp;
[![GitHub](https://img.shields.io/badge/thechosenone--shall--prevail-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/thechosenone-shall-prevail)

<br/>

```
┌──────────────────────────────────────────────────────┐
│  root@kali:~$ echo $IDENTITY                         │
│  the chosen one                                      │
│  root@kali:~$ █                                      │
└──────────────────────────────────────────────────────┘
```

*aHR0cHM6Ly9iaXQubHkvNHRqZ2Jjag==.*

</div>
