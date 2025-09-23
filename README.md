# Network Security Lab

This project shows a complete security lab setup with firewall, IDS, SIEM, and alerting.  
It was built to simulate a real network defense environment and integrate multiple tools.  

## Components
- **pfSense**: firewall and main router.  
- **Suricata**: IDS on pfSense, monitoring traffic and detecting threats.  
- **Splunk**: SIEM collecting logs and correlating events.  
- **Telegram Bot**: sends real-time alerts from Splunk to a chat.  
- **Windows Server**: configured as DNS server.  
- **Client Host**: Windows 10 machine to generate and test traffic.  

## Goal
To design and test a small SOC architecture, detect attacks, and get instant alerts.  
