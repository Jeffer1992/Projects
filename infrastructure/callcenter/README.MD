\# \[cite\_start]Implementación Integral de Infraestructura TIC: Call Center \[cite: 53]



\## \[cite\_start]📌 Resumen del Proyecto \[cite: 54]

\[cite\_start]Despliegue de infraestructura "End-to-End" para un centro de operaciones de 16 asesores\[cite: 55]. \[cite\_start]El proyecto destaca por la optimización de recursos de hardware limitado y la integración de capas eléctricas, de red, seguridad electrónica y telefonía IP\[cite: 56].



!\[Topología General](./img/diagrama\_ibague.png)



\---



\## \[cite\_start]🏗️ 1. Infraestructura Física e Ingeniería Eléctrica \[cite: 59]

\[cite\_start]Se realizó el diseño y la ejecución de la capa física, garantizando la estabilidad energética y la organización del cableado\[cite: 60].



\* \[cite\_start]\*\*Mobiliario Técnico:\*\* Diseño y ensamble de muebles modulares en madera RH para estaciones de trabajo\[cite: 61].

\* \[cite\_start]\*\*Sistema Eléctrico:\*\* Instalación de centro de carga bifásica, balanceo de cargas y cableado calibre 12\[cite: 62, 63, 64].

\* \[cite\_start]\*\*Soporte Crítico:\*\* Implementación de UPS dedicada para Servidor PBX, Gateway GSM y Core Router\[cite: 65].

\* \[cite\_start]\*\*Networking Físico:\*\* Canalización bifurcada y Rack con organizadores Panduit\[cite: 66, 67].



\---



\## \[cite\_start]🌐 2. Capa de Red y Seguridad Perimetral \[cite: 69]

\[cite\_start]Configuración robusta para garantizar la disponibilidad del servicio y la seguridad de la información\[cite: 70].



!\[Configuración Winbox](./img/image\_165b58.png)



| Dispositivo | \[cite\_start]Función / Configuración \[cite: 71] |

| :--- | :--- |

| \*\*MikroTik RB2011\*\* | \[cite\_start]Router Core, WAN Estática, NAT y Firewall Hardening\[cite: 73]. |

| \*\*Segmentación\*\* | \[cite\_start]Reserva de direcciones DHCP para dispositivos críticos\[cite: 74]. |

| \*\*CCTV\*\* | \[cite\_start]Sistema Hikvision de 3MP (6 cámaras) con monitoreo remoto\[cite: 75]. |



!\[Reglas NAT](./img/NAT.png)



\---



\## \[cite\_start]📞 3. Telefonía IP y Optimización (Asterisk/Issabel) \[cite: 78]

\[cite\_start]El núcleo del proyecto consistió en transformar un hardware de bajos recursos en un servidor de grado industrial\[cite: 79].



\### \[cite\_start]Optimización del Servidor (Intel Core i3-2120) \[cite: 80]

\[cite\_start]Para garantizar 16 llamadas concurrentes con grabación activa, se realizó un \*\*Debloating\*\* profundo\[cite: 81]:

\* \[cite\_start]\*\*OS:\*\* Instalación de CentOS Minimal\[cite: 82].

\* \[cite\_start]\*\*Seguridad:\*\* Implementación de \*\*Fail2Ban\*\* y acceso mediante \*\*SSH Keys\*\*\[cite: 84].



!\[Extensiones Issabel](./img/extensions.png)



\### \[cite\_start]Gestión de Gateway GSM (Dinstar DWG2000F) \[cite: 85]

\* \[cite\_start]\*\*Mapeo de Puertos 1:1:\*\* Cada extensión SIP se vinculó a un puerto físico (SIM) del Gateway\[cite: 87].

\* \[cite\_start]\*\*Estrategia:\*\* Eliminación de ruteo cíclico para identificar fallas de línea de forma certera\[cite: 88].



!\[Troncales SIP](./img/Trunks.png)

!\[Rutas Salientes](./img/outbound\_routes.png)



\---



\## \[cite\_start]📊 4. Eficiencia de Recursos (Métricas Reales) \[cite: 90]

\[cite\_start]Estado del servidor i3 tras la optimización de procesos\[cite: 91]:



| Recurso | Estado en Reposo | \[cite\_start]Estado en Operación (16 Ch) \[cite: 92] |

| :--- | :---: | :---: |

| \*\*Uso de CPU\*\* | \[cite\_start]\*\*1%\*\* \[cite: 94] | \[cite\_start]\*\*Optimizado\*\* \[cite: 94] |

| \*\*Memoria RAM\*\* | \[cite\_start]\*\*8% (600MB)\*\* \[cite: 95] | \[cite\_start]\*\*Sin uso de SWAP\*\* \[cite: 95] |



!\[Recursos MikroTik](./img/mikrotik\_resources.png)



\---



\## \[cite\_start]🛠️ Tech Stack \[cite: 98]

\* \[cite\_start]\*\*VoIP:\*\* Asterisk, Issabel 4.0, Linphone\[cite: 99].

\* \[cite\_start]\*\*Hardware:\*\* MikroTik, Dinstar, Intel Core i3\[cite: 100].

\* \[cite\_start]\*\*Seguridad:\*\* Hikvision, ZTE, Fail2Ban, IPsec/SSH Keys\[cite: 102].

