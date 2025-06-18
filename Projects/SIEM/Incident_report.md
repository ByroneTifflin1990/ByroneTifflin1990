Phishing email confirmation:

Analyst : Byrone Tifflin
Tools used : Splunk , VirusTotal, urlscan

timestamp : Jun 18th 2025 at 11:22
affected user : miguel.odonnell@tryhatme.com
Department : Sales

IOC: 
-Domain is flagged as malicious (VirusTotal.com)
- It is using a ".online" which is very uncommon in professional businesses.
- Primary Name Server Not Listed At Parent
- Content uses emotion to manipulate user into engaging
- Has a call to action linking to a malicious destination(Flagged by VirusTotal)

Reason for escalation : With logs provided it was unclear whether user engaged with phishing content. Further investigation into network logs required.

Recommended Actions : 
- Quarantine user device until further assessment has been done to identify if any links where engaged.
- Reset user account details ( Password)

Notes : With the trend in phishing email engagements it is required to update user engagement policy and conduct rules. Further training is required to mitigate any future exposure to risks / threats.  
