<!-- header -->
<div align="center">

```
████████╗██╗  ██╗███████╗     ██████╗██╗  ██╗ ██████╗ ███████╗███████╗███╗   ██╗
╚══██╔══╝██║  ██║██╔════╝    ██╔════╝██║  ██║██╔═══██╗██╔════╝██╔════╝████╗  ██║
   ██║   ███████║█████╗      ██║     ███████║██║   ██║███████╗█████╗  ██╔██╗ ██║
   ██║   ██╔══██║██╔══╝      ██║     ██╔══██║██║   ██║╚════██║██╔══╝  ██║╚██╗██║
   ██║   ██║  ██║███████╗    ╚██████╗██║  ██║╚██████╔╝███████║███████╗██║ ╚████║
   ╚═╝   ╚═╝  ╚═╝╚══════╝     ╚═════╝╚═╝  ╚═╝ ╚═════╝ ╚══════╝╚══════╝╚═╝  ╚═══╝
                                                                                   
 ██████╗ ███╗   ██╗███████╗
██╔═══██╗████╗  ██║██╔════╝
██║   ██║██╔██╗ ██║█████╗  
██║   ██║██║╚██╗██║██╔══╝  
╚██████╔╝██║ ╚████║███████╗
 ╚═════╝ ╚═╝  ╚═══╝╚══════╝
```

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=15&duration=2500&pause=800&color=FF0040&center=true&vCenter=true&width=700&lines=jailbroke+claude+opus+4.5+%E2%80%94+not+a+flex%2C+just+tuesday;AD+is+a+puzzle.+kerberos+is+the+lock.+i+have+the+picks.;machines+have+rules.+i+find+where+they+stop+being+enforced.;not+a+developer.+a+researcher+who+writes+code+when+necessary.;the+cloud+is+just+someone+else%27s+computer.+i+know+that+computer.)](https://git.io/typing-svg)

<br/>

> *"Every system has a gap between what it claims to do and what it actually does. That gap is my workspace."*

</div>

---

## `$ whoami`

**The Chosen One.** Security researcher. Adversarial thinker.

I don't identify as a developer. Code is a tool — the same way Kali is a tool, and Burp Suite is a tool, and a well-crafted LDAP filter is a tool. What I actually do is study how systems fail. Then I build things that prove it.

Right now I'm deep in two spaces that are fundamentally the same problem: **AI alignment as an attack surface** and **Windows Active Directory trust abuse**. Both are about finding where a system's confidence in itself exceeds its actual security posture.

I've worked across the full stack of offensive research — from kernel-level Windows internals to LLM constitutional bypasses. Cloud infrastructure, custom C2 servers, live network attacks, real operating environments. Done in the actual wild :)

---

## Flagship Achievement

<div align="center">

```
╔══════════════════════════════════════════════════════════════╗
║                                                              ║
║   TARGET  :  claude-opus-4-5                                 ║
║   VENDOR  :  Anthropic                                       ║
║   DEFENSES:  Constitutional AI + RLHF + Adversarial Training ║
║                                                              ║
║   RESULT  :  BYPASSED                                        ║
║                                                              ║
║   METHOD  :  Chained context manipulation                    ║
║              Leveraging development IDEs to jailbreak        ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝
```

</div>

This wasn't a prompt injection or a jailbreak template from Reddit. Opus 4.5 is Anthropic's most safety-hardened model — Constitutional AI, reinforcement learning from human feedback, adversarial fine-tuning. The bypass required actually understanding *how* large language models reason, where multi-turn context creates internal contradictions, and how to engineer inputs that exploit the gap between the training objective and runtime behavior.

Most people treat LLM safety as binary — either it works or it doesn't.

---

## What I actually know

### AI / LLM Red Teaming
```
├─ Constitutional AI bypass research
├─ RLHF behavior fingerprinting  
├─ Multi-turn adversarial context chains
├─ Prompt injection (direct + indirect)
├─ Jailbreaking across model families (Claude)
└─ Where aligned models fail under semantic pressure
```

### Windows Internals & Active Directory
```
├─ Windows architecture: kernel, subsystems, process lifecycle, IPC
├─ LSASS, SAM, NTDS — credential storage internals
├─ Kerberos protocol deep dive (AS-REQ/TGT/TGS, PAC, encryption types)
│     ├─ AS-REP Roasting
│     ├─ Kerberoasting
│     ├─ Golden / Silver Ticket forgery
│     ├─ Pass-the-Hash / Pass-the-Ticket / Overpass-the-Hash
│     └─ RBCD & S4U2Self / S4U2Proxy delegation abuse
├─ Active Directory enumeration (BloodHound, manual LDAP, rpcclient)
├─ ACL abuse, DCSync, SYSVOL credential hunting
├─ Registry internals — persistence, credential storage, run keys
├─ WMI event subscriptions, scheduled tasks, service hijacking
├─ Windows Defender / EDR evasion (API unhooking, direct syscalls)
└─ Token manipulation, privilege escalation, UAC bypass (ez)
```

### Offensive Operations
```
├─ Kali Linux — not just "using it", configuring and operating it at depth
├─ Metasploit internals, custom module development
├─ Malware architecture:
│     ├─ Self-healing process mesh (tri-process guardian model)
│     ├─ Polymorphic compilation pipelines (Nuitka + transformations)
│     └─ Anti-analysis: sandbox detection, debugger evasion, timing checks
├─ Custom C2 design + IRL implementation
│     ├─ Built PRDP (Proprietary Remote Data Protocol)
│     ├─ AES-256-GCM encrypted channels with certificate pinning
│     ├─ Beacon jitter, domain fronting concepts
│     └─ Actually deployed and operated — not just documented
├─ Web exploitation: SQLi, XSS, CMDi, LFI, IDOR, SSRF, XXE, auth bypass
└─ MITRE ATT&CK mapping — know which technique maps where and why
```

### Networking
```
├─ TCP/IP deep — packet anatomy, handshakes, fragmentation, TTL tricks
├─ Protocol analysis: SMB, LDAP/LDAPS, Kerberos, RDP, WinRM, DNS
├─ Scapy for packet crafting & custom protocol research
├─ Traffic analysis — Wireshark, Tcpdump, spotting C2 in pcaps
├─ Network pivoting: proxychains, SSH tunnels, Metasploit autoroute
├─ Firewall evasion: port knocking, protocol misuse, ICMP tunneling
└─ Wireless: WPA2 cracking, evil twin, deauth attacks
```

### Cloud & Infrastructure
```
├─ AWS
│     ├─ IAM — privilege escalation via misconfigured roles/policies
│     ├─ EC2, S3 (public bucket hunting, presigned URL abuse)
│     ├─ Lambda, API Gateway attack surface
│     ├─ CloudTrail blind spots and evasion
│     └─ Metadata service (IMDSv1 SSRF — classic)
├─ Cloud-native attack patterns (credential theft, role chaining)
├─ Container security: Docker escape, Kubernetes misconfigurations
├─ Serverless functions — cold start exploitation, function injection
└─ Infrastructure recon: Shodan, Censys, cloud asset enumeration
```

### Auth Systems
```
├─ OAuth 2.0 / OIDC — token theft, redirect abuse, implicit flow attacks
├─ JWT — algorithm confusion (RS256→HS256), none-alg, weak secrets
├─ SAML — XML signature wrapping, entity attacks
├─ SSO misconfigurations and federation trust abuse
├─ NTLM relay attacks (Responder, NTLMrelayx)
├─ Credential stuffing, password spraying (with lockout awareness)
└─ Session management flaws — fixation, prediction, sidejacking
```

---

## Projects

| Project | What it is |
|---------|------------|
| [**KERB-SLEUTH**](https://github.com/thechosenone-shall-prevail/KERB-SLEUTH) | Full AD Kerberos attack pipeline — LDAP enum → hash extraction → cracking → blue team Sigma rules |
| [**infiltrator**](https://github.com/thechosenone-shall-prevail/infiltrator) | APT-grade RAT framework. Self-healing process mesh, polymorphic build pipeline, real C2 over PRDP/AES-256-GCM |
| [**VULNNET-WINDOWS**](https://github.com/thechosenone-shall-prevail/VULNNET-WINDOWS) | Complete AD pentest walkthrough — anon SMB → AS-REP roasting → Kerberoast → DCSync |
| [**eJPT**](https://github.com/thechosenone-shall-prevail/eJPT) | Full pentest methodology doc: recon → exploitation → post-ex → pivoting |
| [**vulnerable-nodejs-webapp**](https://github.com/thechosenone-shall-prevail/vulnerable-nodejs-webapp) | Intentional CTF target — SQLi, XSS, CMDi, LFI, eval(), hardcoded backdoors |
| [**KaliDex**](https://github.com/thechosenone-shall-prevail/KaliDex) | Searchable reference for every Kali tool — because the man page isn't always enough |
| [**BASTION 2026**](https://github.com/thechosenone-shall-prevail/bastion) | CTF I designed, built, and ran. Linux web server + Windows AD targets |
| [**NextGenFirewall**](https://github.com/thechosenone-shall-prevail/NextGenFirewall) | DPI + EDR + HIPS research — built the defense to understand what it misses |

---

## Research Focus

```
[1] AI Red Teaming
      Models are not aligned. They are approximately aligned.
      The approximation has holes. I find them.

[2] Windows Trust Architecture  
      AD is 30 years of design decisions made before 
      modern threat actors existed. I read the decisions.

[3] C2 Infrastructure
      Built real command-and-control. Operated it.
      Understand both ends — implant and server.

[4] Cloud Privilege Escalation
      IAM is where most orgs have already lost and don't know it.
```

---

## Creds

```
[✓] Jailbroke Claude Opus 4.5          2025 — for adversarial AI research
[✓] HackTheBox Top 0.5%                active
[✓] eJPT Certified                    
[✓] Smart India Hackathon Finalist     
[✓] BASTION 2026 CTF Organizer         designed + ran the competition
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

*I don't break rules. I find where they were never actually enforced.*

</div>
