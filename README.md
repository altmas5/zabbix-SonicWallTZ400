Code from [redrouteone](https://github.com/redrouteone) on [zabbix share](https://share.zabbix.com/cat-app/firewall/sonicwall-tz400).  
Imported to Zabbix 5.4 and translated to English. 

### Troubleshoot
In case of getting the error message `Cannot find host interface on "Sonicwall" for item key "ifInOctets.0"` you have to first add a SNMP interface on your host:

Configuration -> 
  Hosts -> 
    Click on your SonicWall Host -> 
      On the default tab (Host) go to "Interfaces" -> 
        Add -> 
          SNMP ->
            Input IP Addr or DNS name
