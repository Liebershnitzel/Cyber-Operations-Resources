


**General Overviews**

- Microsoft ADDS Documentation: https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview
- Learning Active Directory: https://learn.microsoft.com/en-us/training/modules/introduction-to-ad-ds/1-introduction
- Services Overview: [Active Directory Domain Services Overview | Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/get-started/virtual-dc/active-directory-domain-services-overview)
- Attacking Active Directory : https://zer1t0.gitlab.io/posts/attacking_ad/
- Hacking Active Directory - Learning and Practice : https://github.com/zjja/Cyber-Notes/blob/main/Learning/Active_Directory.md

**SERVER ROLES**


**Security/Enable Hardening**

- AD Security: https://adsecurity.org/
- Top Strategies to harden AD Infrastructure: https://blog.netwrix.com/2023/04/28/harden-active-directory/
- Best Practices for Securing AD: https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/best-practices-for-securing-active-directory
- SANS Best Practices Overview: https://www.sans.org/blog/overview-of-microsofts-best-practices-for-securing-active-directory/


**Forensics**
- NTDS.dit: https://www.dataforensics.org/microsoft-active-directory/
- Active Directory Offline hash Dump and Forensics Analysis: https://www.exploit-db.com/docs/english/18244-active-domain-offline-hash-dump-&-forensic-analysis.pdf
- Cyber Forensics Active Directory Investigation: https://www.valencynetworks.com/blogs/cyber-forensics-active-directory-investigation/
- Active Directory ACL Permissions: https://technet440.rssing.com/chan-6827930/article24102.html



**ATTACKS AND DETECTION**

- **DC SYNC** 
	- What is a DC Sync?: https://blog.netwrix.com/2021/11/30/what-is-dcsync-an-introduction/
	- Detecting DC Sync:  https://blog.blacklanternsecurity.com/p/detecting-dcsync

- **DC Shadow**
	- What is a DC Shadow? : https://www.dcshadow.com/
	- Performing a DC Shadow Attack? : https://blog.netwrix.com/2022/09/28/dcshadow_attack/
	- DC Shadow Detection: https://www.sentinelone.com/blog/detecting-a-rogue-domain-controller-dcshadow-attack/

- **Password Spray**
	- What is A password Spray/Tutorial: https://www.netwrix.com/password_spraying_tutorial_defense.html
	- Performing Password Spray's :https://book.hacktricks.xyz/windows-hardening/active-directory-methodology/password-spraying
	- Red Team Notes : https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/active-directory-password-spraying
	- Detecting Password Spraying with Security Event Auditing: https://www.hub.trimarcsecurity.com/post/trimarc-research-detecting-password-spraying-with-security-event-auditing
	  
- **Pass-The-Hash**
	- What is a Pass-The-Hash Attack: https://www.beyondtrust.com/resources/glossary/pass-the-hash-pth-attack
	- What is a Pass-The-Hash Attack: https://www.crowdstrike.com/cybersecurity-101/pass-the-hash/
	- Detecting Pass-The-Hash: https://blog.netwrix.com/2021/11/30/how-to-detect-pass-the-hash-attacks/

- **Golden Ticket**
	- What is a golden ticket attack : https://www.crowdstrike.com/cybersecurity-101/golden-ticket-attack/
	- What is a golden ticket attack: https://blog.quest.com/golden-ticket-attacks-how-they-work-and-how-to-defend-against-them/
	- Detecting Golden Ticket Attacks: https://www.extrahop.com/company/blog/2021/detect-kerberos-golden-ticket-attacks/

- **adminSDHolder**
	- Understanding AdminSDHolder:  https://specopssoft.com/support/en/password-reset/understanding-privileged-accounts-and-adminsdholder.htm
	- Defending Against SDHolder Attacks: https://www.sentinelone.com/blog/protecting-your-active-directory-from-adminsdholder-attacks/
	- Finding Privileged Accounts with AdminCount Attribute: https://blog.netwrix.com/2022/09/30/admincount_attribute/

- **Active Directory Certificate Services**
	- Attacks, Misconfigurations and Detections: https://posts.specterops.io/certified-pre-owned-d95910965cd2
	- Using Bloodhound and Certipy: https://medium.com/@shaunwhorton/certifried-bloodhound-active-directory-certificate-services-abuse-f28850ffefc9

- **Kerberoast & Service Principal Name**
	- What is a keberoasting attack? : https://www.crowdstrike.com/cybersecurity-101/kerberoasting/
	- Performing a Kerberoast: https://book.hacktricks.xyz/windows-hardening/active-directory-methodology/kerberoast
	- https://adsecurity.org/?p=3458

- **ASREPROAST**
	- What is AS-REP Roasting? : https://blog.netwrix.com/2022/11/03/cracking_ad_password_with_as_rep_roasting/
	- Kerberos Pre-Auth: One checkbox can mean a lot: https://www.linkedin.com/pulse/kerberos-pre-auth-one-checkbox-can-mean-lot-darryl/
	- Detecting Kerberos Pre-Auth: https://www.ultimatewindowssecurity.com/securitylog/encyclopedia/event.aspx?eventid=4771
	- Detecting AS-REP Roast: https://jsecurity101.medium.com/ioc-differences-between-kerberoasting-and-as-rep-roasting-4ae179cdf9ec

- **File Share Enumeration**
	- Default Shares
		- Default Shares: [Remove administrative shares - Windows Server | Microsoft Learn](https://learn.microsoft.com/en-us/troubleshoot/windows-server/networking/remove-administrative-shares)
	- IPC$
		- What is the $IPC Share? : https://smallvoid.com/article/winnt-ipc-share.html
		- How Chinese Hackers Attack $IPC : https://www.giac.org/paper/gcih/466/ipc-share-exploit-methodology-chinese-attackers/103860
		- RID Brute : https://wiki.porchetta.industries/smb-protocol/enumeration/enumerate-users-by-bruteforcing-rid
	- SYSVOL & NETLOGON
		- Importance of Sysvol & NETLOGON: http://www.techiebird.com/Sysvol_netlogon_importance_ActiveDirectory.html
		- Credential Harvesting from Domain Shares:https://www.sentinelone.com/blog/credentials-harvesting-from-domain-shares/
	- ADMIN$
		- How Psexec Works: https://www.lifewire.com/psexec-4587631

- **Applocker Bypass**
	- Bypassing AppLocker: https://juggernaut-sec.com/applocker-bypass/

- **Abusing Active Directory ACL/ACE
	- Red Team Notes:  https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/abusing-active-directory-acls-aces
	- Kerberos Resource-Based Constrained Delegation: Computer object takeover: https://www.ired.team/offensive-security-experiments/active-directory-kerberos-abuse/resource-based-constrained-delegation-ad-computer-object-take-over-and-privilged-code-execution
- Privilege Abuses
	- Windows Privilege Abuses [Windows Privilege Abuse: Auditing, Detection, and Defense | by Palantir | Palantir Blog](https://blog.palantir.com/windows-privilege-abuse-auditing-detection-and-defense-3078a403d74e)

- SID History injection Expose
	- [Windows Security Identifier (SID) History Injection Exposure (sentinelone.com)](https://www.sentinelone.com/blog/windows-sid-history-injection-exposure-blog/)

- Dumping SAM
	- [Credential Dumping: SAM - Hacking Articles](https://www.hackingarticles.in/credential-dumping-sam/)
