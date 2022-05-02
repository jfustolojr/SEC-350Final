# SEC-350 Final
### [Technicial Demo](https://drive.google.com/file/d/1VraDYbfIpsu3LtLtYq4g5pwVPN1s5Qu8/view?usp=sharing) | [Documentation](https://drive.google.com/file/d/1LwcUYvr87KpJs9HGT-iaoXCofVcj9q5y/view?usp=sharing)

| Name | Assigned Tasks |
| ------------- | ------------- |
| Quentin  |  Windows Machines, Log01, ADDS Monitoring feed |
| Joseph  | FW01, Auth Logs, FTP feed, Jump/SSH |
| Mike  | Http-Mail, Http Access, Mail feed  |
| Everyone  | Documentation, Demostration  |

![Network Diagra](https://github.com/jfustolojr/SEC-350Final/blob/main/SEC350-FinalDiagram.png)



| **WAN** | **10.0.17.0/24** |
| ------------- | ------------- |
| fw01-bababooey | 10.0.17.104 | 
| rw01-bababooey | 10.0.17.54 |

| **DMZ** | **172.16.50.0/28** |
| ------------- | ------------- | 
| fw01-bababooey | 172.16.50.1 | 
| mail01-bababooey | 172.16.50.3 | 
| jump-bababooey | 172.16.50.2 |  

| **LAN** | **172.16.150.0/24** | 
| ------------- | ------------- | 
| fw01-bababooey | 172.16.150.1 |
| wwks1-bababooey | 172.16.150.5 | 
| wwks2-bababooey | 172.16.150.6 | 
| ftp01-bababooey | 172.16.150.10 | 

| **MGMT** | **172.16.200.0/28** | 
| ------------- | ------------- |
| fw01-bababooey | 172.16.200.1 | 
| dc01-bababooey | 172.16.200.10 | 
| dc02-bababooey | 172.16.200.11 | 
| log01-bababooey | 172.16.200.12 | 
