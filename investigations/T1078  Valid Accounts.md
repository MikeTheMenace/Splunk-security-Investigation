#T1078 Valid Accounts

## MITRE Techniques
T1078- Valid Accounts.
Cloud accounts are created to allow remote users to be able to access on-premises resources.This accounts are highly targeted using phishing emails or brute force attacks to give adversaries access to our services.

 ## SQL QUERY
 source="m365_defender_security_alerts.log" host="Michael" index="std_23150413" sourcetype="Security investigations" severity=High classification=TruePositive  "mitreTechniques{}"="T1078
 
<img width="959" height="539" alt="image" src="https://github.com/user-attachments/assets/6586dd35-d69f-44d5-8f76-72a13f9f694b" />
<img width="746" height="378" alt="image" src="https://github.com/user-attachments/assets/388b69ed-fdb3-4b02-9db8-b37f21456d3b" />
<img width="557" height="206" alt="image" src="https://github.com/user-attachments/assets/cc62f6f6-892f-4650-8c65-a7c43df922d6" />
<img width="554" height="205" alt="image" src="https://github.com/user-attachments/assets/b76049ed-6303-4996-8ec1-b14fa2bb3030" />

## Investigation Findings

-Sign in from unfamiliar Location as the properties not recently seen to the given user.
- Impossible Travel between IPs which one is registered in the second image where one IP is registered in Australia while the other is in Singapore
- Alert classified as TruePositive
- Activity status marked as Resolved
  ## Reccomendations
   -MFA Trigger for unfamilia location.
  -Adopt digital certificates for authenticating devices.
  - 
  
  
  
