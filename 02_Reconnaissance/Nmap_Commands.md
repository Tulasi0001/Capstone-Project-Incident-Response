# Nmap Commands

## Host Discovery

```bash
nmap -sn <LAB_NETWORK>
Used to identify active hosts within the controlled laboratory network.

Service Enumeration
nmap -sV <LAB_TARGET>

Used to identify available services and their versions.

TCP SYN Scan
nmap -sS <LAB_TARGET>

Used to identify open TCP ports.

UDP Scan
nmap -sU --top-ports 20 <LAB_TARGET>

Used to identify commonly used UDP services.

Operating System Detection
nmap -O <LAB_TARGET>

Used to obtain an operating-system fingerprint where supported.

<LAB_TARGET> and <LAB_NETWORK> represent the authorized laboratory target and network.


This is deliberate — **we're not publishing unnecessary exact lab details throughout the public repo.**

---

## `Reconnaissance_Notes.md`

```markdown
# Reconnaissance Notes

The reconnaissance stage identified the laboratory target and provided information about its exposed services.

The target was found to be active within the private laboratory network.

Service enumeration identified multiple network services, including web-related services.

The reconnaissance results were used to establish the attack surface before proceeding to application-level testing.

Detailed scan evidence is documented in the final Task 5 report.
