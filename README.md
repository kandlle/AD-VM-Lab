# AD-VM-Lab
This lab was created to better understand enterprise tech enviroments by replicating one using Windows Server 2022 and Windows 11 Pro.
![Lab Overview](https://github.com/kandlle/AD-VM-Lab/blob/2aa83ba99fbea482ed6c1d9e85cf58739f7f7cad/AD_VM%20Diagram.png)
Active Directory was setup with 1000+ users with a [powershell script](https://github.com/kandlle/AD-VM-Lab/blob/main/1_CREATE_USERS.ps1) drawing in names from a [text file](https://github.com/kandlle/AD-VM-Lab/blob/main/names.txt).
A scope of IP's was created from 172.16.0.100 - 200.
After this I domain joined the PC named as CLIENT1 which I had previously installed without updates.
<br/>
![Scans](https://github.com/kandlle/AD-VM-Lab/blob/023ab0ef8fb363926b49aeefb77878182cd54fb1/media/VM-scans.png)
<br/>
Using Nessus Essentials I scanned the PC, remediated the Vulnerabilites and created a report for my findings.
![Assessment](https://github.com/kandlle/AD-VM-Lab/blob/102dd021a907c8db6c3a23011b4a8478e2de0fb6/VAReport.png)
After that I did some more poking around.![Side Lab](./helpdesk.md)
