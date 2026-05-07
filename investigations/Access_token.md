# T1134.005 Access Token Manipulation (SID History Injection)
SID Injection is an AD privilege escalation technique to add malicious account.
## MITRE Technique
T1134 : Access Token Manipulation
 ## MITRE SubTechnique
 .005 SID History Injection
## SPL Query

##spl Query
source="m365_defender_security_alerts.log" host="Michael" index="std_23150413" sourcetype="Security investigations" severity=High classification=TruePositive  "mitreTechniques{}"="T1134"

## Findings
- High severity alert
- SID History Injection
- Classification: TruePositive


## Screenshot
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/bdb77934-787d-4994-b3eb-6848a713fad5" />
