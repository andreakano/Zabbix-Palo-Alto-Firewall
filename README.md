# Zabbix template for Palo Alto Networks Next-Generation Firewall
Template to monitor Palo Alto Networks NGFW with RAM Memory Graph update.

# Overview
Template to monitor Palo Alto Networks NGFW PAN-OS by Zabbix using SNMP v2c. For Zabbix version: 5.4 and higher.

This template was tested on:
- PAN-OS, version 10.0

# Setup
- See Zabbix templates importing for basic instructions on how to import a template.
https://www.zabbix.com/documentation/5.2/manual/xml_export_import/templates#importing

# Zabbix configuration

- Set/change the SNMP community in the host SNMP settings to match your community string. See CONFIGURING SNMP MONITORING
- Set SNMP community on the NGFW and commit. See [Enable SNMP Monitoring] (https://docs.paloaltonetworks.com/pan-os/10-0/pan-os-web-interface-help/device/device-setup-operations/enable-snmp-monitoring.html)
