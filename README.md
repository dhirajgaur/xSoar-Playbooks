# xSoar-Playbooks
This is a collection of open source xSoar playbooks.

## Recorded Future Related IP Hunting Playbook (Added 24 September 2021)
This playbook needs a working integration of Recorded Future on xSOAR platform. The playbook takes one or more IP as an input and then returns the related risky 
IP addreses by querying the Recorded Future Intelligence. Risky IPs with score > 65 are retruned in the form of CSV file. This CSV file can be further used for 
threat huntin gon SIEM tools, blocking the risky IPs on the perimeter security devices, etc. 
