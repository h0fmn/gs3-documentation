# Features & Capabilities 

- **Versatile Connectivity**<br>
The GS3 works with 100Mb, 1Gb, and 10Gb Ethernet SFP/SFP+ ports, offering flexible deployment options to take control of serial ports from an Ethernet network.
- **Converged Management**<br>
The GS3 is designed to simplify network management by enabling both Ethernet and serial port control through the same switch. With its on-demand TIA-232 (RS-232) model, serial ports can be dynamically added as needed, eliminating the requirement for a separate console management device. This reduces hardware costs and provides a more environmentally friendly solution.
- **Serial Communication via RJ-45** <br>
The RJ-45 connector on the GS3 is dedicated solely to serial communication and must not be used for Ethernet connections. While standard straight-through Ethernet cables are supported, only pins 3, 4, 5, and 6 are used for the connection between the GS3 and the managed device. Custom cables are available for interfacing with mini-B and DB9 serial connectors on the target devices.
<!-- A standard straight-through Ethernet cable is suitable for an RJ-45 to RJ-45 connection. If custom cables
are required, please visit our website: https://www.glbb.jp/en/hardware/gs3/ -->
- **Streamlined IP-Based Serial Management**<br>
Each GS3 device is assigned a unique IP address, enabling direct IP-based serial communication without the complexity of managing multiple TCP ports. This streamlines serial device management, allowing them to be handled as easily as standard network devices.
- **Enhanced Security and Stability**<br>
The GS3 provides robust security features, including:
    - Support for up to five locally configured users
    - SSH client access control via Access Control Lists (ACLs)
    - Full compatibility with both IPv4 and IPv6
<!-- In the event of a failed firmware upgrade, the GS3 is designed to revert to a stable base version using its MCU bootloader, allowing the upgrade process to be retried. Additionally, if access is restricted by its own ACL, it can still be recovered through the IPv6 link-local address. The GS3 can also leverage the security features of the connected Ethernet port, such as Layer 2 and Layer 3 ACLs. -->
- **Firmware Upgradeability and User-Friendly Reset** <br>
The GS3 is firmware-upgradeable via SFTP, ensuring it remains up to date with the latest features and security updates. If the device’s password is forgotten, it can be reset to factory defaults by plugging and unplugging the RJ-45 interface more than four times within ten seconds, providing a simple recovery mechanism.
- **Operational Features**<br>
The GS3 supports multiple serial baud rates and includes a CR/LF transmit delay to prevent garbled text when copying and pasting into the management interface over SSH.
- **24/7 Monitoring and Alerts** <br>
The GS3 enables continuous monitoring of connected devices and can send alerts to Syslog or SNMP servers when specific key phrases or events—such as errors or warm reloads—are detected. This feature enhances network visibility and ensures timely responses to potential issues.