<img src="https://github.com/user-attachments/assets/b4dbe4d0-77dc-4899-bff5-c872c4eb8f8e" width="300" />

# Russian APT Tool Matrix
A tool matrix for Russian APTs based on the [Ransomware Tool Matrix](https://github.com/BushidoUK/Ransomware-Tool-Matrix/)

# Russian APT Tool Matrix
- This repository contains a list of which tools each Russian APT group uses
- As defenders, we should exploit the fact that many of the tools used by these Russian APT groups are often reused
- We can threat hunt, deploy detections, and block these tools to eliminate the ability of adversaries to launch intrusions
- This project will be updated as additional intelligence on Russian APT group TTPs is made available

> [!TIP]
>  This Russian APT Tool Matrix has several use cases, which are as follows:
> - As a list of leads for threat hunting inside the environments available to you
> - As a list of leads to look for during incident response engagements
> - As a checklist of tools to identify patterns of behaviour between certain Russian APTs
> - As an adversary emulation resource for threat intelligence-led purple team engagements

## Russian APT Tool Matrix
- [RMM Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/RMM-Tools.md)
- [Exfiltration Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/Exfiltration.md)
- [Credential Theft Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/CredentialTheft.md)
- [Defense Evasion Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/DefenseEvasion.md)
- [Networking Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/Networking.md)
- [Discovery Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/Discovery.md)
- [Offensive Security Tools](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/Offsec.md)
- [Living-off-the-Land Binaries and Scripts](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/LOLBAS.md)

## Sources
- [Threat Intelligence](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Other/ThreatIntelligence.md)

## Additional Resources
- [List of Russian APT group profiles](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/tree/main/GroupProfiles)
- [List of All Russian APT Tools by Type](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Tools/AllToolsRU.csv)

## Types of Russian APTs
> [!TIP]
> This repo also contains multiple types of Russian APTs, this includes the GRU, SVR, and FSB. The alias of each Russian APT group has been chosen by what the author of this repo believes it is most well-known as.
> - **Russian GRU:** Main Intelligence Directorate (Russian Military)
> - **Russian SVR:** Foreign Intelligence Service of the Russian Federation
> - **Russian FSB:** Federal Security Service of the Russian Federation

## Challenges
> [!IMPORTANT]
> Using the Russian APT Tool Matrix comes with its own challenges. While it is undoubtedly useful to have a list of tools commonly used by Russian APTs to hunt, detect, and block, there are some risks.
> - Many of the tools referenced in this repository may be currently used by your IT team or even your Cybersecurity team.
> - When hunting for these tools, you may uncover many installations of them inside your environment.
> - Deciphering whether a tool is being used legitimately, by an employee, with permission is difficult in a large or global environment.
> - If you create a detection rule, you may generate a large amount of alerts, which may get ignore or turned off without investigating them.
> - If you block these tools without investigating for legitimate usage, you may cause disruption to legitimate business operations and potentially impose costs on your own organisation.

#### How To Contribute
- Please see the following [guidelines](https://github.com/BushidoUK/Russian-APT-Tool-Matrix/blob/main/Other/HowToContribute.md) to contribute to this repo.
