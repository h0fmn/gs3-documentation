# `network ipv6 <auto/random/manual/linklocal/disable>`

## Description
Configures the IPv6 settings.

## Example 
```
[admin@ssh-to-serial]>network ipv6 disable
IPv6 is disabled
```
```
[admin@ssh-to-serial]>network show
Compiled: Jun 18 2025 09:14:01

Static IPv4 Address: 192.168.11.11
IPv4 Subnet Mask: 255.255.255.0
IPv4 Default Gateway: 192.168.11.1
IPv4 Primary DNS: 1.1.1.1
IPv4 Secondary DNS: 8.8.8.8
IPv6 Link-Local Address:
IPv6 Prefix:
IPv6 Prefix Length: 64
IPv6 Global Address:
IPv6 Default Router:
IPv6 Primary DNS:
IPv6 Secondary DNS:
Reverse SSH Port: 2222
Reverse SSH Timeout: 300 seconds
Interface Name: eth0
Hostname: ssh-to-serial
MAC Address: 8C-12-C2-00-00-CE
DHCP: disabled
SLAAC: disabled
Stable Address: disabled
IPv4: enabled
Remote NTP Server: 0.0.0.0
Remote Syslog Server: 0.0.0.0

Current configuration displayed.
```