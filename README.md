#Lab di Network Security

Questo progetto mostra un laboratorio completo di sicurezza di rete, con firewall, IDS, SIEM e sistema di alerting.
È stato costruito per simulare un ambiente difensivo reale e integrare diversi strumenti tra loro.

#Componenti

pfSense: firewall e router principale.

Suricata: IDS installato su pfSense, monitora il traffico e rileva attività sospette o malevole.

Splunk: SIEM che raccoglie i log e correla gli eventi.

Bot Telegram: invia alert in tempo reale da Splunk a una chat dedicata.

Windows Server: configurato come server DNS.

Client Windows 10: host usato per generare traffico e testare rilevamenti.

#Obiettivo

Progettare e testare una piccola architettura da SOC, rilevare attacchi e ricevere avvisi immediati quando vengono identificati.
