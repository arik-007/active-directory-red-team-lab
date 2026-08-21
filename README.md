# Active Directory Penetration Testing Lab

Hands-on Active Directory penetration testing lab built in a controlled virtual environment using Kali Linux and Windows Active Directory.

## Objective

Practice and document:

- Active Directory enumeration
- SMB / LDAP / Kerberos enumeration
- SharpHound & BloodHound
- Credential and ticket attacks
- Privilege escalation
- Lateral movement

## Lab Environment

- **Attacker:** Kali Linux
- **Target:** Windows Active Directory environment
- **Virtualization:** VirtualBox

## Attack Flow

```
Initial Access
      ↓
Enumeration
      ↓
SharpHound
      ↓
BloodHound
      ↓
Attack Path Discovery
      ↓
Privilege Escalation
      ↓
Lateral Movement
```

## Documentation

- [Lab Setup](docs/lab-setup.md)
- [Enumeration](docs/enumeration.md)
- [Attack Narrative](docs/attack-narrative.md)
- [Remediation](docs/remediation.md)

## Evidence

Screenshots and network diagrams are included in the `screenshots/` and `diagrams/` directories.

> All testing was performed in an isolated lab environment for educational purposes.
