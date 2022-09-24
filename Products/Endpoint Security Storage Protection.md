# Endpoint Security Storage Protection

## Product Overview
Endpoint Security Storage Protection (ENS SP) detects and removes viruses, malware, and other potentially unwanted software programs from your network-attached storage (NAS) devices.

Endpoint Security Storage Protection (ENS SP) is added to McAfee Endpoint Security and expands its capability. The software performs remote scanning on NAS devices such as NetApp filers and Internet Content Adaptation Protocol (ICAP) storage appliances

## Usage
We want to scan our NetApp storage all the time, so we will configure a NetApp scanner server (regular server with the ENS SP installed) and assign an ENS SP policy telling him how to scan the NetApp.

The NetApp scanner server needs to be in our Clustered Data ONTAP Antivirus Connector software.

After the NetApp scanner server scans the file, it informs the NetApp filer whether the file is a threat and then repairs the malicious file. All generated events are sent to McAfee ePO and it can be reviewed under Threat Event Log (and from there can be analyzed in our SIEM).

## Resources
- [Endpoint Security Storage Protection Product Guide](/PDF/Endpoint%20Security%20Storage%20Protection/mcafee_endpoint_security_storage_protection_2.2.x_product_guide_9-24-2022.pdf)
- [Endpoint Security Storage Protection Installation Guide](/PDF/Endpoint%20Security%20Storage%20Protection/endpoint_security_storage_protection_2.2.x_installation_guide_9-24-2022.pdf)

[Back to Homepage](/README.md)