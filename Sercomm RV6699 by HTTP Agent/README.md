# Zabbix Template for Sercomm RV6699
This template uses the HTTP Agent to collect data by extracting values from the router’s web interface.

Tested on SERCOMM RV6699, Firmware Version sc3.3.46, Hardware Version v3

## Collected metrics
CPU – Processor load in %

Memory – RAM usage in %

IP Address – Current external IPv4 address of the device

IPv6 Address – Current external IPv6 address of the device

Internet State – Internet connection status

PON State – Optical connection status

Time Since Last Boot – Time elapsed since the last reboot


## Setup Instructions
1. Add the Host

  Ensure the router's IP address is correctly set under the host configuration in Zabbix.

2. Verify Macros

  Check that the username and password are properly configured in macros:
-  {$USER} – Default: admin
-  {$PASSWORD} – Default: admin
