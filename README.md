# Azure Threat Hunter's Toolkit

This repository is a collection of custom Kusto Query Language (KQL) queries for use in performing proactive threat hunts for cyber security issues in Microsoft's Azure cloud hosting platform. Some require some customisation before use, there are comments next to variables that require customisation detailing what steps to take. 

These queries are primarily designed for use in the Azure Sentinel and 365 Defender, although they could also form the basis of queries for use in other tools that accept KQL like Microsoft Advanced Threat Protection (ATP).

### Microsoft Sentinel queries
* [General](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/General)
* [Active Directory](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Azure-Active-Directory)
* [Azure Active Directory](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Azure-Active-Directory)
* [Azure Bastion](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Azure-Bastion)
* [Azure Key Vault](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Azure-Key-Vault)
* [Azure Monitor](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkitk/tree/main/Sentinel/Azure-Monitor)
* [Defender for Endpoint](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Defender-for-Endpoint)
* [Defender for Identity](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Defender-for-Identity)
* [Office 365](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Sentinel/Office-365)

### Defender 365 Advanced Hunting queries
* [Email](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Defender-365/Email)
* [Networking](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Defender-365/Networking)
* [Post-compromise](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Defender-365/Post-compromise)
* [Ransomware](https://github.com/apacketofsweets/Azure-Threat-Hunters-Toolkit/tree/main/Defender-365/Ransomware)

### Attribution
Queries in this repo are a mixture of self-written Kusto and code originally obtained from [reprise99](https://github.com/reprise99/Sentinel-Queries) and [lawndoc](https://github.com/lawndoc/AdvancedHuntingQueries).




