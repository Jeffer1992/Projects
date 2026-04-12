\# \[cite\_start]Comprehensive ICT Infrastructure Implementation: Call Center \[cite: 53]



\## \[cite\_start]📌 Project Summary \[cite: 54]

\[cite\_start]End-to-End infrastructure deployment for a 16-agent operations center\[cite: 55]. \[cite\_start]The project stands out for its optimization of limited hardware resources and the integration of electrical, network, electronic security, and IP telephony layers\[cite: 56].



!\[General Topology](./img/diagrama\_ibague.png)



\---



\## \[cite\_start]🏗️ 1. Physical Infrastructure and Electrical Engineering \[cite: 59]

\[cite\_start]The physical layer was designed and implemented, ensuring power stability and cable organization\[cite: 60].



\* \[cite\_start]\*\*Technical Furniture:\*\* Design and assembly of modular furniture in RH wood for workstations\[cite: 61].

\* \[cite\_start]\*\*Electrical System:\*\* Installation of a two-phase load center, load balancing, and dedicated UPS\[cite: 62, 63, 65].



\* \[cite\_start]\*\*Physical Networking:\*\* Bifurcated cabling and rack with Panduit organizers\[cite: 66, 67].



\---



\## \[cite\_start]🌐 2. Network Layer and Perimeter Security \[cite: 69]

\[cite\_start]Robust configuration to guarantee service availability and information security\[cite: 70].



!\[Winbox Configuration](./img/image\_165b58.png)



| Device | Function / Configuration |



| :--- | :--- |



| \*\*MikroTik RB2011\*\* | \[cite\_start]Router Core, Static WAN, NAT and Firewall Hardening\[cite: 73]. |



\*\*Segmentation\*\* | \[cite\_start]DHCP Address Reservation for Critical Devices\[cite: 74]. |



!\[NAT Rules](./img/NAT.png)



\---



\## \[cite\_start]📞 3. IP Telephony and Optimization (Asterisk/Issabel) \[cite: 78]

\[cite\_start]The core of the project consisted of transforming low-resource hardware into an industrial-grade server\[cite: 79].



\### \[cite\_start]Server Optimization (Intel Core i3-2120) \[cite: 80]

\* \[cite\_start]\*\*OS:\*\* CentOS Minimal Installation\[cite: 82].



\* \[cite\_start]\*\*Security:\*\* Implementation of Fail2Ban and access via SSH Keys\[cite: 84].



!\[Issabel Extensions](./img/extensions.png)



\### \[cite\_start]GSM Gateway Management (Dinstar DWG2000F) \[cite: 85]

\* \[cite\_start]\*\*1:1 Port Mapping:\*\* Each SIP extension was linked to a physical port (SIM) of the Gateway\[cite: 87].



\* \[cite\_start]\*\*Strategy:\*\* Identification of line failures and consumption auditing by advisor\[cite: 88].





!\[SIP Trunks](./img/Trunks.png)

!\[Outbound Routes](./img/outbound\_routes.png)



\---



\## \[cite\_start]📊 4. Resource Efficiency (Actual Metrics) \[cite: 90]

\[cite\_start]Server State After Process Optimization\[cite: 91]:



| Resource | Idle State | Operational State (16 Ch) |



| :--- | :---: | :---: |



\*\*CPU Usage\*\* | \*\*1%\*\* | \[cite\_start]\*\*Optimized\*\* \[cite: 94] |



\*\*RAM Usage\*\* | \*\*8% (600MB)\*\* | \[cite\_start]\*\*No SWAP Usage\*\* \[cite: 95] |



!\[MikroTik Resources](./img/mikrotik\_resources.png)



\---



\## \[cite\_start]🛠️ Tech Stack \[cite: 98]

\* \[cite\_start]\*\*VoIP:\*\* Asterisk, Issabel 4.0, Linphone\[cite: 99].

\* \[cite\_start]\*\*Hardware:\*\* MikroTik, Dinstar, Intel Core i3\[cite: 100].

\* \[cite\_start]\*\*Security:\*\* Hikvision, ZTE, Fail2Ban\[cite: 102].



\---



## Versión en Español

\# \[cite\_start]Comprehensive ICT Infrastructure Implementation: Call Center \[cite: 53]



\## \[cite\_start]📌 Project Summary \[cite: 54]

\[cite\_start]End-to-End infrastructure deployment for a 16-agent operations center\[cite: 55]. \[cite\_start]The project stands out for its optimization of limited hardware resources and the integration of electrical, network, electronic security, and IP telephony layers\[cite: 56].



!\[General Topology](./img/diagrama\_ibague.png)



\---



\## \[cite\_start]🏗️ 1. Physical Infrastructure and Electrical Engineering \[cite: 59]

\[cite\_start]The physical layer was designed and implemented, ensuring power stability and cable organization\[cite: 60].



\* \[cite\_start]\*\*Technical Furniture:\*\* Design and assembly of modular furniture in RH wood for workstations\[cite: 61].

\* \[cite\_start]\*\*Electrical System:\*\* Installation of a two-phase load center, load balancing, and dedicated UPS\[cite: 62, 63, 65].



\* \[cite\_start]\*\*Physical Networking:\*\* Bifurcated cabling and rack with Panduit organizers\[cite: 66, 67].



\---



\## \[cite\_start]🌐 2. Network Layer and Perimeter Security \[cite: 69]

\[cite\_start]Robust configuration to guarantee service availability and information security\[cite: 70].



!\[Winbox Configuration](./img/image\_165b58.png)



| Device | Function / Configuration |



| :--- | :--- |



| \*\*MikroTik RB2011\*\* | \[cite\_start]Router Core, Static WAN, NAT and Firewall Hardening\[cite: 73]. |



\*\*Segmentation\*\* | \[cite\_start]DHCP Address Reservation for Critical Devices\[cite: 74]. |



!\[NAT Rules](./img/NAT.png)



\---



\## \[cite\_start]📞 3. IP Telephony and Optimization (Asterisk/Issabel) \[cite: 78]

\[cite\_start]The core of the project consisted of transforming low-resource hardware into an industrial-grade server\[cite: 79].



\### \[cite\_start]Server Optimization (Intel Core i3-2120) \[cite: 80]

\* \[cite\_start]\*\*OS:\*\* CentOS Minimal Installation\[cite: 82].



\* \[cite\_start]\*\*Security:\*\* Implementation of Fail2Ban and access via SSH Keys\[cite: 84].



!\[Issabel Extensions](./img/extensions.png)



\### \[cite\_start]GSM Gateway Management (Dinstar DWG2000F) \[cite: 85]

\* \[cite\_start]\*\*1:1 Port Mapping:\*\* Each SIP extension was linked to a physical port (SIM) of the Gateway\[cite: 87].



\* \[cite\_start]\*\*Strategy:\*\* Identification of line failures and consumption auditing by advisor\[cite: 88].





!\[SIP Trunks](./img/Trunks.png)

!\[Outbound Routes](./img/outbound\_routes.png)



\---



\## \[cite\_start]📊 4. Resource Efficiency (Actual Metrics) \[cite: 90]

\[cite\_start]Server State After Process Optimization\[cite: 91]:



| Resource | Idle State | Operational State (16 Ch) |



| :--- | :---: | :---: |



\*\*CPU Usage\*\* | \*\*1%\*\* | \[cite\_start]\*\*Optimized\*\* \[cite: 94] |



\*\*RAM Usage\*\* | \*\*8% (600MB)\*\* | \[cite\_start]\*\*No SWAP Usage\*\* \[cite: 95] |



!\[MikroTik Resources](./img/mikrotik\_resources.png)



\---



\## \[cite\_start]🛠️ Tech Stack \[cite: 98]

\* \[cite\_start]\*\*VoIP:\*\* Asterisk, Issabel 4.0, Linphone\[cite: 99].

\* \[cite\_start]\*\*Hardware:\*\* MikroTik, Dinstar, Intel Core i3\[cite: 100].

\* \[cite\_start]\*\*Security:\*\* Hikvision, ZTE, Fail2Ban\[cite: 102].

