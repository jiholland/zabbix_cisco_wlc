cisco catalyst 9k wlc by snmp
=============================

This [template](https://www.zabbix.com/documentation/current/en/manual/xml_export_import/templates#importing) monitors:
- high availability redundancy state
- high availability peer state
- accesspoint operational state
- maximum number of supported accesspoints

The template uses
[snmp bulk requests](https://www.zabbix.com/documentation/current/en/manual/config/items/itemtypes/snmp?hl=SNMP%2Cdiscovery#native-snmp-bulk-requests)
for discovery which require Zabbix version 6.4 or greater.

☕️ Jørn Ivar
