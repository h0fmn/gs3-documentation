# `network show`

### Description
Displays the current network configuration.

### Example
```
[admin@ssh-to-serial]>network show
Compiled: Jun 18 2025 09:14:01

Static IPv4 Address: 192.168.11.11
IPv4 Subnet Mask: 255.255.255.0
IPv4 Default Gateway:
IPv4 Primary DNS:
IPv4 Secondary DNS:
IPv6 Link-Local Address: fe80::8e12:c2ff:fe00:ce
IPv6 Global Address: ::
IPv6 Default Router: ::
IPv6 Primary DNS:
IPv6 Secondary DNS:
Reverse SSH Port: 2222
Reverse SSH Timeout: 300 seconds
Interface Name: eth0
Hostname: ssh-to-serial
MAC Address: 8C-12-C2-00-00-CE
DHCP: disabled
SLAAC: enabled
Stable Address: enabled with EUI-64
IPv4: enabled
Remote NTP Server: 0.0.0.0
Remote Syslog Server: 0.0.0.0

Current configuration displayed.
```