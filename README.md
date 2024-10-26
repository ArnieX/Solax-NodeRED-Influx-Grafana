![image](https://github.com/user-attachments/assets/71aace60-f05d-4a30-a59e-f7b1242b420f)

![image](https://github.com/user-attachments/assets/91c92de4-9fd6-478e-a994-1377b2a1933b)

# CZ: Solax X3 G4 - NodeRED toky a Grafana dashboard
Sada plug and play flow pro NodeRED a Grafana dashboard pro čtení a vizualizaci dat ze střídače Solax X3 G4.

## Požadavky
- NodeRED
- Grafana
- InfluxDB 1.8
- Střídač Solax X3 G4

## Instalace
- NodeRED - Menu >> Importovat >> Kopírovat & Vložit JSON kód nebo Nahrát soubor s JSON flow.

- Grafana - Klikněte na + >> zvolte Import dashboard >> Kopírovat & Vložit JSON kód nebo Nahrát soubor s JSON dashboardem.

## Nastavení
- V node Modbus Flex Sequencer je potřeba nastavit server, tedy IP adresu měniče, tu je vhodné mít v DHCP nastavenou jako fixní (neměnnou).

![image](https://github.com/user-attachments/assets/99ef4ebc-cdca-4441-8bbf-4d11268f8f02)

![image](https://github.com/user-attachments/assets/f60761f1-092a-4c38-b5d9-80a5c8f0fef2)

- V node InfluxDB - SolaxPower je potřeba také nastavit IP adresu Influx databáze - pozor je potřeba mít verzi InfluxDB 1.8

![image](https://github.com/user-attachments/assets/a3fa8e44-a8be-481e-8dc7-d628b84eeef3)

![image](https://github.com/user-attachments/assets/6ecb82a3-ed48-4abd-a584-344040bc3c34)

[![solaxchlazenibanner](https://github.com/user-attachments/assets/a808534b-2019-4006-8175-1abcf92a8e5c)](https://www.solaxchlazeni.cz)

# EN: Solax X3 G4 - NodeRED flows and Grafana dashboard
Set of plug and play flows for NodeRED and Grafana dashboard to read and visualize data from Solax X3 G4 inverter.

## Prerequisities
- NodeRED
- Grafana
- InfluxDB 1.8
- Solax X3 G4 inverter

## Installation
- NodeRED - Menu >> Import >> Copy & Paste JSON code or Upload File with flow JSON

- Grafana - Click + >> select Import dashboard >> Copy & Paste JSON code or Upload File with dashboard JSON

## Settings
- In Modbus Flex Sequencer node, set up correctly your inverter IP address. It is recommended to have set DHCP reservation for this device to keep the IP fixed.

![image](https://github.com/user-attachments/assets/99ef4ebc-cdca-4441-8bbf-4d11268f8f02)

![image](https://github.com/user-attachments/assets/f60761f1-092a-4c38-b5d9-80a5c8f0fef2)

- In InfluxDB node - SolaxPower also set IP for your instance of InfluxDB, be aware that this node is specifically tailored for InfluxDB v. 1.8 and will not work witch newer version of InfluxDB.

![image](https://github.com/user-attachments/assets/a3fa8e44-a8be-481e-8dc7-d628b84eeef3)

![image](https://github.com/user-attachments/assets/6ecb82a3-ed48-4abd-a584-344040bc3c34)

[![solaxchlazenibanner](https://github.com/user-attachments/assets/a26bcf5e-a7ff-4321-8274-3c6fe149f69d)](https://www.solaxchlazeni.cz)
