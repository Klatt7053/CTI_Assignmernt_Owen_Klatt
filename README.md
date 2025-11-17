# CTI_Assignmernt_Owen_Klatt
For Cyber Threat Intelligence Assignment for CST Program

Task 3 

Iranian Government-Sponsored APT Cyber Actors Exploiting Microsoft Exchange and Fortinet Vulnerabilities 

Adversary - Iranian Goverment-sponsored APT Group

Infrastructure - They used IP addresses, Emails, and Ports (Ex. Domains: WeAreHere@secmail.pro)

Capability - They used Credentail Theft, Privilage escalation, data archiving, and Ransomware Deployment. The Tools they are are Mimikatz, WinPEAS, SharpWMI, and WinRAR

Victim - They targeted the Transportation Sector, Healthcare and Public Health sector, and U.S municipal governments, and the geographies they attacked are US, and Austrialla 

Task 5 

Threat Actor: Iranian State-Sponsored APT Group 

An Iranian government-backed advanced persistent threat (APT) group poses a serious nation-state cyber risk to critical infrastructure. Their campaigns primarily target U.S. and Australian organizations in healthcare, transportation, and government sectors, with objectives ranging from espionage and data theft to ransomware deployment.
This group leverages sophisticated tactics to gain initial access, exploiting known vulnerabilities such as Microsoft Exchange (CVE-2021-34473) and Fortinet devices (CVE-2018-13379). After breaching networks, they employ tools like Mimikatz for credential harvesting, WinPEAS for privilege escalation, and WinRAR for data compression and exfiltration. Their operations demonstrate advanced persistence techniques and the ability to execute impactful follow-on actions, including ransomware attacks.
Using the Diamond Model, clear relationships emerge: the adversaries control infrastructure—such as IP addresses 91.214.124[.]143 and 162.55.137[.]20—used to deliver capabilities against victims. This model highlights how their technical resources enable compromises of healthcare and government systems, with infrastructure serving as the delivery mechanism for attacks.
To mitigate these threats, organizations should prioritize patching the identified CVEs, enforce multi-factor authentication, and implement strong password policies. Additional measures include monitoring for unusual RDP activity, auditing scheduled tasks for unauthorized entries, and maintaining offline backups. Network segmentation and regular security assessments are essential to limit lateral movement and detect these actors early in the attack chain.

Task 6 

How does the Diamond Model help in understanding threat Actors? 
It helps by visualizing the entire scope of threat actor and there strategies. It also helps to break down what they were doing and why 

What challenges did I face in identifying each vertex? 
I had some uncertainty when trying to identify the vertex for Adversary because Nation-state actors can use false flags or work through intermediaries. 

I also had some issues with Capability becuase these APT group are ever evolving with developing new exploits and the reports mentions specific tools but not specific details about them 

How could this model support proactive defence stratigies? 
This model can show the threat actors stratige from a more broad perspective and gives insights to the how and why. 
