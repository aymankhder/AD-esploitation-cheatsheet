# Active Directory Exploitation Cheatsheet

A cheatsheet that contains common enumeration and attack methods for Windows Active Directory.

This cheatsheet is inspired by the [PayloadAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings) repo.

**Credit Info:** Every tool and methodology i am describing will be referenced at the end, with a link to the actual tool and creator.

![Just Walking The Dog](https://github.com/buftas/Active-Directory-Exploitation-Cheatsheet/blob/master/WalkTheDog.png)

## Summary

- [Active Directory Exploitation Cheatsheet](#active-directory-exploitation-cheatsheet)
  - [Summary](#summary)
  - [Tools](#tools)
  - [Enumeration](#enumeration)
  - [Local Privilege Escalation](#local-privilege-escalation)
  - [Lateral Movement](#lateral-movement)
  - [Domain Persistence](#domain-persistence)
  - [Domain Privilege Escalation](#domain-privilege-escalation)
  - [Cross Forest Attacks](#cross-forest-attacks)
  - [Forest Persistence](#forest-persistence)
  - [References](#references)

## Tools
- [PowerSploit](https://github.com/PowerShellMafia/PowerSploit/tree/dev)
- [PowerUpSQL](https://github.com/NetSPI/PowerUpSQL)
- [Powermad](https://github.com/Kevin-Robertson/Powermad)
- [Impacket](https://github.com/SecureAuthCorp/impacket)
- [Mimikatz](https://github.com/gentilkiwi/mimikatz)
- [Rubeus](https://github.com/GhostPack/Rubeus) -> [Compiled Version](https://github.com/r3motecontrol/Ghostpack-CompiledBinaries)
- [BloodHound](https://github.com/BloodHoundAD/BloodHound)
- [AD Module](https://github.com/samratashok/ADModule)

## Enumeration

[PowerView 3.0 Tricks](https://gist.github.com/HarmJ0y/184f9822b195c52dd50c379ed3117993)

### With PowerView

- **Get Current Domain:** \ `Get-NetDomain`
- **Enum Other Domains:** `Get-NetDomain -Domain <DomainName>`
- **Get Domain SID:** `Get-DomainSID`
- **Get Domain Policy:** `Get-DomainPolicy`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`
- **Get Current Domain:** `Get-NetDomain`

## Local Privilege Escalation

## Lateral Movement

## Domain Persistence

## Domain Privilege Escalation

## Cross Forest Attacks

## Forest Persistence

## References
