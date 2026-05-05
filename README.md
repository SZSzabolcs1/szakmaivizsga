# EV Cars Enterprise Network Infrastructure Project

> Szakmai vizsgaprojekt – Informatikai rendszer- és alkalmazás-üzemeltető technikus  
> 5-0612-12-02

## Projekt leírás

Ez a projekt egy elektromos autókat gyártó vállalat magyarországi infrastruktúrájának teljes hálózati megtervezését és kivitelezését mutatja be.

A cél egy biztonságos, skálázható és magas rendelkezésre állású vállalati hálózat létrehozása három különböző telephely számára:

- **Központi iroda**
- **Gyár**
- **Ügyfélszolgálat**

A projekt tartalmazza:

- hálózattervezést
- Packet Tracer szimulációt
- gyakorlati szerver konfigurációkat
- hálózatbiztonsági megoldásokat
- automatizációs scriptet

---

## Projekt funkciók

### Hálózati technológiák

- VLAN segmentation
- Inter-VLAN routing
- EtherChannel (LACP)
- STP / Rapid PVST
- HSRP redundancy
- IPv4 + IPv6 addressing
- Static & Dynamic routing
- NAT / PAT
- Static NAT
- ACL filtering
- VPN tunnel (IPSec)
- CHAP authentication

### Szerver szolgáltatások

### Windows Server
- Active Directory
- Group Policy
- DHCP
- DNS
- File sharing
- Print server
- Automated software deployment
- Backup

### Linux Server (Debian)
- ISC DHCP Server
- Bind9 DNS
- Apache2 Web Server
- Rsyslog
- NTP

### Biztonság

- SSH v2 remote management
- Port Security
- Disabled unused ports
- Firewall appliance
- ACL rules
- VPN encryption
- Password policies

### Automatizálás

Python script használata:

- Netmiko
- Paramiko

Lekérdezések:

- running-config
- interface states
- CPU / RAM usage
- device status monitoring


---

## Használt technológiák

| Terület | Technológia |
|---|---|
| Network Simulation | Cisco Packet Tracer |
| Routers | Cisco Catalyst / Cisco 2811 |
| Switching | Cisco CBS350 |
| Firewall | Cisco Secure Firewall |
| Server OS | Windows Server 2016 |
| Linux Server | Debian |
| Automation | Python |
| Remote Access | SSH |

---

## Telephelyek

## 1. Központi iroda

Funkciók:

- VLAN-ok emeletek szerint
- WiFi hálózat
- HSRP redundancia
- Windows Server infrastruktúra
- DHCP / DNS / AD

---

## 2. Gyár

Funkciók:

- IPv4 + IPv6
- robot hálózat
- hardveres tűzfal
- dual addressing
- szerver alapú frissítés

---

## 3. Ügyfélszolgálat

Funkciók:

- Linux server
- webserver
- static NAT
- HTTPS only access
- IP telefonok
- Syslog

---

## Tesztelés

Elvégzett tesztek:

- VLAN működés
- EtherChannel failover
- HSRP failover
- Wireless connectivity
- VPN tunnel
- NAT/PAT
- Static NAT
- ACL validation
- Server services

---

## Készítők

- **Szécsényi Szabolcs**
- **Pintyák Róbert**

Debreceni SZC Mechwart András Gépipari és Informatikai Technikum  
2025

---

## Megjegyzés

Ez a repository oktatási és szakmai vizsga célokat szolgál.

---
