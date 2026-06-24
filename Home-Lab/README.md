# Home Lab

## Purpose

This folder documents the development of my cybersecurity home lab.

The lab will be used to practice:

- Networking
- Linux administration
- Windows administration
- Security tools
- Vulnerability assessment
- Packet analysis

## Virtual Machines

### Windows 10 Lab

Status: In Progress

Learning points:
- Created a Windows 10 virtual machine in VirtualBox
- Learned how ISO installation media works
- Learned about boot order and virtual hard disks
- Installed Windows 10 using a virtual disk

## Lessons Learned

### Lesson 1: Boot Order

After Windows finished installing, I accidentally booted from the ISO again and started the installation process a second time.

This helped me understand how computers decide whether to boot from installation media or the installed operating system.

### Lesson 2: DHCP, DNS and Gateways

Using Kali Linux, I identified:

- IP Address: 10.0.2.15
- Default Gateway: 10.0.2.2
- DNS Server: 10.0.2.3

I learned that DHCP automatically provided these settings to the machine.

I also learned that DNS converts names such as google.com into IP addresses, allowing devices to communicate across the network.
