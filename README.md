# Azure Threat Hunting Playbook

This repository contains a number of resources for use in performing proactive Threat Hunting in Microsoft's Azure cloud hosting platform. These resources are primarily designed for use in the Microsoft Sentinel and 365 Defender, although the principles should also apply to other SIEM and Endpoint protection tools. 

The Sentinel and 365 Defender Advanced Hunting queries are written in Kusto Query Language (KQL), meaning they should be able to run in other tools that accept KQL with minimal changes required to them - this would probably be the most useful in Microsoft Advanced Threat Protection. These queries can be used to perform proactive threat hunts for common Cyber Security issues. Some require some customisation before use, there are comments next to variables that require customisation detailing what steps to take. 

## Threat Hunting queries

### Microsoft Sentinel
* [General](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/General)
* [Active Directory](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Azure-Active-Directory)
* [Azure Active Directory](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Azure-Active-Directory)
* [Azure Bastion](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Azure-Bastion)
* [Azure Key Vault](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Azure-Key-Vault)
* [Azure Monitor](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Azure-Monitor)
* [Defender for Endpoint](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Defender-for-Endpoint)
* [Defender for Identity](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Defender-for-Identity)
* [Office 365](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Sentinel/Office-0365)

### Defender 365 Advanced Hunting
* [Email](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Defender-365/Email)
* [Networking](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Defender-365/Networking)
* [Post-compromise](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Defender-365/Post-compromise)
* [Ransomware](https://github.com/apacketofsweets/Azure-Threat-Hunting-Playbook/tree/main/Queries/Defender-365/Ransomware)
