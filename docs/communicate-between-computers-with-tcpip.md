# Communicate Between Computers With TCP/IP

## Basics

* [TCP/IP (Ric Messier)](https://learning.oreilly.com/videos/tcp-ip/9781771370790)
* [Network Analysis Using Wireshark 3 (Mohamed Mahjoub)](https://learning.oreilly.com/videos/network-analysis-using/9781838825164/)

## Advanced

* [TCP/IP Fundamentals (Michael J. Shannon)](https://learning.oreilly.com/videos/tcp-ip-fundamentals/9780135450161)
* [Networking and IP Addressing Fundamentals LiveLessons (Learning@Cisco)](https://learning.oreilly.com/videos/networking-and-ip/9780133479904)
* [Mastering Wireshark 3 (Rick Bodnar)](https://learning.oreilly.com/videos/mastering-wireshark-3/9781839213953/)
* [Wireshark for Packet Analysis and Ethical Hacking (David Bombal)](https://learning.oreilly.com/videos/wireshark-for-packet/9781839212352/)

## Resources

* [Wireshark for Windows](https://www.wireshark.org/download.html)
* [Wireshark for Ubuntu](https://launchpad.net/ubuntu/+source/wireshark)

## Recommendations

Be able to setup a virtual network on your workstation with the following components:

* host Windows machine
* 2 or more Linux virtual machines on the same IPv4 subnet
* WSL2 instance on a separate IPv4 subnet
* virtual network switch on the host Windows machine
* virtual IPv4 router on the host Windows machine
* virtual NAT device on the host Windows machine

Enable the following communication paths:

* ping both ways between Linux virtual machines
* ping both ways between Linux virtual machines and host Windows machine virtual network adapter connected to Linux virtual machine IPv4 subnet
* ping both ways between WSL2 instance and host Windows machine virtual network adapter connected to WSL2 IPv4 subnet
* ping from Linux virtual machines to host Windows machine virtual network adapter connected to WSL2 IPv4 subnet
* ping from Linux virtual machines to WSL2 instance
* ping from WSL2 instance to host Windows machine virtual network adapter connected to Linux virtual machine IPv4 subnet
* ping from WSL2 instance to Linux virtual machines
* curl from WSL2 instance to www.google.com
* curl from Linux virtual machines to www.google.com

When you have Docker Desktop for Windows running with integration to WSL2, setup and check the communication paths between Docker containers and Linux virtual machines and the host Windows machine.