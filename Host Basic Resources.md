- These resources are extensions to the JQR Line Items


**Host Fundamentals**
- Volatile Memory Resources
	- Order of Volatility [Order of Volatility (briancarr.org)](https://www.briancarr.org/post/order-of-volatility)\
	- Memory Acquisition on Windows/Linux : https://alexandreborgesbrazil.files.wordpress.com/2014/06/memory-acquisition_win_linux1.pdf 
	- Page Tables, VAD and PEB: [Page tables, VAD and PEB | Infosec Resources (infosecinstitute.com)](https://resources.infosecinstitute.com/topic/finding-enumerating-processes-within-memory-part-2/)


- SETUID, SETGID and SUDO
	- Understanding SETUID and SETGID: [SetUID, SetGID, and Sticky Bits in Linux File Permissions - GeeksforGeeks](https://www.geeksforgeeks.org/setuid-setgid-and-sticky-bits-in-linux-file-permissions/#)
	- GTFOBINS: [GTFOBins](https://gtfobins.github.io/)
	- Why Adversaries use SETUID and SETGID: [Setuid and Setgid - Red Canary Threat Detection Report](https://redcanary.com/threat-detection-report/techniques/setuid-setgid/#:~:text=Adversaries%20most%20often%20leverage%20this%20technique%20by%20finding,least%2C%20perform%20an%20action%20as%20the%20privileged%20user.)

- Windows/Linux Logging: 
	- Windows Logging the basics [Windows Logging Guide: The Basics - CrowdStrike] (https://www.crowdstrike.com/guides/windows-logging/)
	- Linux Logging the basics: [Linux Logging Guide: The Basics - CrowdStrike](https://www.crowdstrike.com/guides/linux-logging/)s

- Registry Keys
	- Hunting for Persistence, Run Keys and Startup Folders: [Hunting for Persistence: Registry Run Keys / Startup Folder | Cyborg Security](https://www.cyborgsecurity.com/cyborg-labs/hunting-for-persistence-registry-run-keys-startup-folder/)
	- Interesting-Windows-Registry Keys : [hacktricks/forensics/basic-forensic-methodology/windows-forensics/interesting-windows-registry-keys.md at master · carlospolop/hacktricks · GitHub](https://github.com/carlospolop/hacktricks/blob/master/forensics/basic-forensic-methodology/windows-forensics/interesting-windows-registry-keys.md)

- DLL Sideloading
	- Detecting DLL Hijacking: [SANS Digital Forensics and Incident Response Blog | Detecting DLL Hijacking on Windows | SANS Institute](https://www.sans.org/blog/detecting-dll-hijacking-on-windows/)
	- Youtube Videos
		- [Red Team TTPs: Evade EDR like a Chad through DLL Sideloading! - YouTube](https://www.youtube.com/watch?app=desktop&v=WX9io57sexM)

- For Active Directory, see AD Section

- Rootkits
	- Understanding Rootkits: [What is Rootkit? Attack Definition & Examples - CrowdStrike](https://www.crowdstrike.com/cybersecurity-101/malware/rootkits/)
	- Windows Rootkit: [Understanding Rootkits: Using Memory Dump Analysis for Rootkit Detection - Forensic Focus](https://www.forensicfocus.com/articles/understanding-rootkits/)
	- Linux Rootkits: [Understanding, Detecting, & Preventing Modern Linux Rootkits (securityinnovation.com)](https://blog.securityinnovation.com/modern-linux-rootkits)

- For Portable Executable, See Anti-Virus Evasion Section

- Exfiltration
	- What is Data Exfiltration: [Data Exfiltration Defined and How to Prevent It - CrowdStrike](https://www.crowdstrike.com/cybersecurity-101/data-exfiltration/#:~:text=Data%20exfiltration%20can%20be%20conducted%20by%20outsiders%2C%20who,device%20that%20is%20connected%20to%20the%20corporate%20network.)
	- Data Exfiltration Techniques : [Data exfiltration techniques | Pen Test Partners](https://www.pentestpartners.com/security-blog/data-exfiltration-techniques/)

- Process Handles, See Windows Forensics
- Services, See Windows Forensics
- For Evidence of Program Execution see Windows Forensics
- For Baseline see Windows Forensics, and DFIR

- Hash Comparison
	- Hash Filtering: [SANS Digital Forensics and Incident Response Blog | Extracting Known Bad Hash Set From NSRL | SANS Institute](https://www.sans.org/blog/extracting-known-bad-hash-set-from-nsrl/)

- Virus Total Forensics
	- What is Virus Total? : [How it works – VirusTotal](https://support.virustotal.com/hc/en-us/articles/115002126889-How-it-works)
	- Why you shouldn't automate your VirusTotal uploads : [Why you shouldn’t automate your VirusTotal uploads (malwarebytes.com)](https://www.malwarebytes.com/blog/news/2022/04/why-you-shouldnt-automate-your-virustotal-uploads#:~:text=It%20is%20important%20to%20realize%20that%20uploading%20certain,as%20does%20VirusTotal%20itself%20on%20their%20home%20page.)

- Privilege Levels
	- Understanding Windows Local Accounts: [Local Accounts - Windows Security | Microsoft Learn](https://learn.microsoft.com/en-us/windows/security/identity-protection/access-control/local-accounts)
	- Privileged accounts and groups in Active Directory : [Appendix B - Privileged Accounts and Groups in Active Directory | Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/plan/security-best-practices/appendix-b--privileged-accounts-and-groups-in-active-directory)
	- Linux Security: What is Sudo: [Linux security: What is sudo and why is it so important? | ZDNET](https://www.zdnet.com/article/why-sudo-is-so-important-in-linux-and-how-to-use-it/)

- Checking for outdated Patches
	- Understanding SCCM : [What is SCCM? What is the use of SCCM? And How its Works? - Technoresult](https://technoresult.com/what-is-sccm-what-is-the-use-of-sccm-and-how-its-works/)
	- Understanding Forescout: [All you need to know about Forescout - Gologica](https://www.gologica.com/elearning/all-you-need-to-know-about-forescout/)
	- Managing Windows 10/11 Software Updates in Intune: [Learn about using Windows Update for Business in Microsoft Intune | Microsoft Learn](https://learn.microsoft.com/en-us/mem/intune/protect/windows-update-for-business-configure#windows-10-feature-updates)

- Administrative Shares, More in Active Directory
	- [SMB/Windows Admin Shares - Red Canary Threat Report](https://redcanary.com/threat-detection-report/techniques/windows-admin-shares/)

- See Command Lists

- Using the AT command to run processes as NT Authority/System : [Run Cmd or any process as System account on Windows – GabSoftware](https://www.gabsoftware.com/tips/run-cmd-or-any-process-as-system-account-on-windows/)

- Understanding some Windows Security Features
	- SID : [Security identifiers | Microsoft Learn](https://learn.microsoft.com/en-us/windows-server/identity/ad-ds/manage/understand-security-identifiers)
		- Windows SID History Injection Exposure: [Windows Security Identifier (SID) History Injection Exposure (sentinelone.com)](https://www.sentinelone.com/blog/windows-sid-history-injection-exposure-blog/)
	- For ACL see Active Directory
	- SAM: [Security Account Manager (SAM) - Windows Active Directory (windows-active-directory.com)](https://www.windows-active-directory.com/windows-security-account-manager.html)
		- See Active Directory for Dumping SAM
	- Token's : [Access Tokens - Win32 apps | Microsoft Learn](https://learn.microsoft.com/en-us/windows/win32/secauthz/access-tokens)
		- Token Manipulation : [MITRE ATT&CK vulnerability spotlight: Access token manipulation | Infosec Resources (infosecinstitute.com)](https://resources.infosecinstitute.com/topic/mitre-attck-access-token-manipulation/)
	- Kerberos Ticket and Authentication : [Kerberos Tickets and Authentication in Active Directory (calcomsoftware.com)](https://www.calcomsoftware.com/kerberos-tickets-and-authentication-in-active-directory/#:~:text=When%20a%20client%20wants%20to%20verify%20himself%20to,password%20won%E2%80%99t%20be%20sent%20over%20an%20insecure%20network%29.)

- Trusted Installer vs System
	- What is trusted Installer? : [What Is TrustedInstaller and Is It Safe? (helpdeskgeek.com)](https://helpdeskgeek.com/windows-10/what-is-trustedinstaller-and-is-it-safe/)


- Firewall Misconfigurations : 
	- Zero Trust Architecture: [Zero Trust Policy: Who, What, When, Where, Why, and How (tigera.io)](https://www.tigera.io/learn/guides/zero-trust/zero-trust-policy/)
	- Firewall Misconfigurations: [Firewall Configuration and Common Misconfigurations · Wiki · Bush, Sammie L. (S&T-Student) / ICI Wiki · GitLab (mst.edu)](https://git.mst.edu/slbnmc/ici-wiki/-/wikis/Firewall-Configuration-and-Common-Misconfigurations)

- Collecting Linux User Shell History
	- What is Bash History: https://www.inmotionhosting.com/support/server/linux/how-to-review-bash-history/
	- Collecting the command history: https://www.sciencedirect.com/topics/computer-science/command-history
- Describe /etc/passwrd, /etc/shadow and /etc/group
	-  Understanding Each: https://www.ques10.com/p/17404/explain-role-of-etcpasswd-etcshadow-etcgroups-file/?
- Describe the artifacts that can be found in /proc, See Linux Forensics
- 5 phases of ethical hacking
	- https://www.invensislearning.com/blog/phases-of-ethical-hacking/
	- Foot Printing: https://www.techtarget.com/searchsecurity/definition/footprinting
	- FingerPrinting: https://www.tutorialspoint.com/ethical_hacking/ethical_hacking_fingerprinting.htm
	- Enumeration:https://www.tutorialspoint.com/ethical_hacking/ethical_hacking_enumeration.htm
	- Initial Entry/ Exploitation: https://socprime.com/blog/what-is-initial-access-mitre-attck-initial-access-tactic-ta0001/
	- Privilege Escalation : https://www.crowdstrike.com/cybersecurity-101/privilege-escalation/
	- Covering Your Tracks / Hiding Evidence : https://www.globalknowledge.com/us-en/resources/resource-library/articles/the-5-phases-of-hacking-covering-your-tracks/
	- Maintaining Access : https://www.globalknowledge.com/us-en/resources/resource-library/articles/the-5-phases-of-hacking-covering-your-tracks/
	- Data Mining: https://www.trendmicro.com/vinfo/es/security/news/cyber-attacks/data-breach-101
- For Memory/Disk Analysis see Memory and Disk Analysis Section
- For Redline See Memory and Disk Analysis
- EndGame
  	- Welcome Endgame : https://www.elastic.co/blog/endgame-joins-forces-with-elastic
  	- Understanding EPP vs EDR VS XDR : https://resources.infosecinstitute.com/topic/comparing-endpoint-security-epp-vs-edr-vs-xdr/
- Carbon Black
	- Carbon Black Technical Overview : https://carbonblack.vmware.com/resource/carbon-black-enterprise-edr-technical-overview#what-is-carbon-black-enterprise-edr
   	- Carbon Black Review: : https://www.fool.com/the-ascent/small-business/endpoint-security/vmware-carbon-black-review/
   	- Carbon Black Limitations : https://community.carbonblack.com/t5/Knowledge-Base/EDR-What-Are-the-Live-Query-Limitations/ta-p/103143
- Tanium
	- Tanium VS SCCM : https://www.wwt.com/article/tanium-vs-microsoft-sccm-the-ferrari-or-the-sedan-or-both
 - 

