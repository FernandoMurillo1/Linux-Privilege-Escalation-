# Linux Privilege Escalation 

## Objective 

With linux Privilege Escalation is to gain elevated acess to resources that are normally protected from the stadard users of a system. Specifically, it involved obtaining adminerstrative (root) privileges to perform actions that are otherwise restricted. 

### Skills Learned 

- Access Control Bypass allows a user to bypass access controls and security measures put in plae to protect system integrity and user data.
- System Controls while elevating privileges a user can control system process and install or uninstall software to be able to congifgure and make changes to the whole system.
- Data Access allows all files and directories on the system including sensitive information and not accessible to regular users.
- Persistence can be used to install backdoors and other malicious software that can still be active even when a system reboots and remains hidden from standard users.
- Explotation in Privilege escalation is on the largers scale or the attack chain, It also allows the attacker to get into the system and move laterally across a network.

### Tools Used 

- LinPEAS is a script that searches for possible paths to escalate privileges on Linux machines
- Metaslpoit is a computer security poroject that provides data on security vulnerabilties and help with penetration testing, and contains modules for local explotation such as privilege escalation exploits
- SUID files are used to find and list files that can be potentially used for explotations
- Kernel exploits such as Dirty Cow (CVE-2016-5195) are a big part of this exploit because it's a race condition in the implementation of the 'copy-on-write' mechanism in the Linux kernal
- Wrtiable scripts are files that are writable and an attacker can modify them to escalate privileges
- John the Ripper is used as a password cracking tool that can be used to crack hashes to be able to escalate privileges as well.
- Capsh is a tool to print out the capabilties of the current process and help manipulate them for escalation.
- Path Manipulation exploits the PATH environment variable to execute malicious binaries in plae of legititmate ones.

## Steps 

