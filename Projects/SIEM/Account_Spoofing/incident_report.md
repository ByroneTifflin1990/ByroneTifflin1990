Incident : Potential Compromised Account
Analyst : Byrone Tifflin
Tools Used :

- Splunk (json log analysis)
- VirusTotal (Malicious scan of domain address)
- MxToolbox ( DNS scan and assessment )

Timestamp: 2025-06-18 11:19:31.143
Sender: liam.espinoza@tryhatme.com
Recipient: best@modernmillinerygroup.online
Subject: "Grow Your Hat Business Overnight with this Secret Formula"
Direction: Outbound
Attachment: None
Content: Redacted per privacy/security policy
The detection was triggered by an email sent to an unusual top-level domain (.online). The SOC was notified for review and escalation.

IOC : 
- Outgoing DNS could not be resolved (modernmillinerygroup.online).  Domain may have been taken down which is common with phishing attempts.
- Top level domain uses (.online) which is uncommon in business practices
- The sender (liam.espinoza@tryhatme.com) is not a registered user of the client(We have no record of that user or what their department is). This could indicate an account illegally onboarded/compromised or potential email spoofing. This user has sent a total multiple emails out to various domains with phishing subject lines

Recommended Actions : 
- Block all domains user has contacted.
- Remove user account
- Conduct internal investigation into the accounts creating and source
- Notify HR about the breach

Recommended escalation to Tier 2 SOC
