See [Analysis Types](https://github.com/TonyPhipps/SIEM/wiki/Analysis-Types) for further explanation.

All IOC/Tactics listed assume there will be some whitelisting required to eliminate false positives unique to any environment.

| Description                                        | Type                    | Notes | 
|----------------------------------------------------|-------------------------|-------| 
| Newly-observed executables (1)                     | Rolling Whitelist Alert |       | 
| Newly-observed network connections (3)             | Rolling Whitelist Alert |       | 
| Non-PowerShell process loading powershell DLLs (7) | Rolling Whitelist Alert |       | 


