# 🔐 Cisco Switch Port Security

## 📌 Project Overview

This lab demonstrates how to configure and verify switch port security using Cisco IOS.

Port security helps control which devices are allowed to connect to a switch port by restricting the MAC addresses that can use the port.

## 🎯 Objectives

- Configure switch port security
- Restrict access to a switch port
- Configure a maximum number of MAC addresses
- Configure a secure MAC address
- Configure a violation mode
- Verify the port-security configuration
- Understand how unauthorized devices are handled

## 🛠️ Tools Used

- Cisco Packet Tracer
- Cisco IOS
- Cisco Catalyst Switch
- PC

## 🌐 Network Configuration

The lab uses a Cisco switch connected to end devices.

The switch port is configured with port-security to control device access.

## ⚙️ Configuration

Enter privileged EXEC mode:

```bash
enable
```

Enter global configuration mode:

```bash
configure terminal
```
Select the interface:

```bash
interface fastethernet 0/1
```

Set the port as an access port:

```bash
switchport mode access
```
Enable port security:

```bash
switchport port-security
```

Limit the number of allowed MAC addresses:

```bash
switchport port-security maximum 1
```

Configure the violation mode:

```bash
switchport port-security violation shutdown
```

Configure the secure MAC address:

```bash
switchport port-security mac-address sticky
```

Exit interface configuration:

```bash
exit
```

Save the configuration:

```bash
copy running-config startup-config
```

## 🔍 Verification

To verify the port-security configuration:

```bash
show port-security
```

To view detailed information about a specific interface:

```bash
show port-security interface fastethernet 0/1
```

To view learned MAC addresses:

```bash
show mac address-table
```

## 🚨 Security Violation

If an unauthorized device is connected to a protected port, the switch can take action according to the configured violation mode.
In this lab, the violation mode is configured as:

```bash
shutdown
```

This causes the interface to be placed into an error-disabled state when a security violation occurs.

## 📚 What I Learned

Through this lab, I learned how to:

- Configure Cisco switch interfaces
- Enable port security
- Limit the number of MAC addresses
- Use sticky MAC address learning
- Configure security violation modes
- Verify port-security settings
- Understand basic switch access control
  
## 🖼️ Lab Evidence

Screenshots and supporting lab evidence are stored in the repository's images folder.

🚀 Future Improvements

Future switch-security labs may include:

- VLAN configuration
- Multiple secure MAC addresses
- Port-security violation testing
- Sticky MAC address management
- VLAN-based security
- DHCP snooping
- Dynamic ARP Inspection

