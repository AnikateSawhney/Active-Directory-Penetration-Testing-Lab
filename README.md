# Active-Directory-Penetration-Testing-Lab
This is an Active Directory Pentesting Lab created by me which includes attacks like IPV6 DNS takeover, Smb relay, unconstrained delegation, RBCD, ACLs, Certificates (ESC1, ESC4,ESC8), Webclient Workstation takeover etc. 
## Table of Contents
1. Certificates (ESC1,ESC4,ESC8)
2. Webclient Workstation Takeover (webdav)
3. IPV6 Dns Takeover
4. ACLs Abuse
5. RBCD (Resource-based Constrained Delegation)
6. Unconstrained Delegation
7. LLMNR Poisoning
8. SMB relay
9. As-rep Roasting
10. Kerberoasting
11. User with Null Password
12. DCSync
### I have my YouTube Channel where you can watch the solutions to all of these attacks (https://www.youtube.com/watch?v=uOzX36XXrDs&list=PLw5BjpTl2awVQGjr2V01CD3Z-OJ9K0wBa)
## Lab Info
4 OVAs
2 Domain Controllers (DC1 and DC2), 1 Windows 10 Machine, 1 Windows 2019 Server.
## Installation
Simply download the OVAs and double-click them. 

DC1 and Win10 OVA link:- https://mega.nz/folder/U6cmUaaR#nV5gl94GgMJlB1zue9JSaQ
DC2 and SERVER1 OVA link:- https://mega.nz/folder/t70CnAqB#r5IkFvfhXR653oE3bu5djQ

The 2nd mega link contains Kerberoasting video which was removed by YouTube.

Note: The lab contains all the mentioned attacks but it will not be identical to the solutions because I keep messing up the lab and make a lot of changes.For example: You cannot directly attack certificates. There is an ACL path to certificates group. Exploit that and then go for certificate attacks. 

Please be aware that the Microsoft Evaluation OVAs used in this lab are intended solely for educational and Testing purposes. I do not own or claim any rights to these Microsoft properties.
These Evaluation OVAs are provided by Microsoft for users to assess and trial their software in a controlled environment. 
