# CTF Write-Ups

Boot-to-root walkthroughs of intentionally vulnerable VMs I ran in an
isolated college labs (VirtualBox, Hyper-V, Kali Linux). Each one covers recon,
enumeration, initial access, privilege escalation, and the mitigation
that would have stopped it.

These are practice machines, not production systems or authorized
engagements. NOSS AAT grad (Clover Park), studying for Security+.

## Write-ups
- Dragon Ball Z - SUID abuse (mawk) via a password left in a web-exposed notes file
- Aliens R Real - command injection to reverse shell, then SUID escalation (date, cpulimit)
