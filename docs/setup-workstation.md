# Setup Workstation

## Computer Hardware Components

- CPU: 8+ CPU cores
- RAM: 32+ GB
- Boot drive:  1+ TB SSD (NVMe preferred)

## Software Components

- Microsoft Windows 10 Professional 1903+
- Microsoft Windows Software
  - Microsoft Windows 10 Features
    - Containers
    - Hyper-V
    - Virtual Machine Platform
    - Windows Hypervisor Platform
    - Windows Subsystem for Linux (WSL2)
  - Ubuntu 20.04 for WSL2
  - Docker Desktop for Windows with WSL2
  - Windows Terminal
  - (optional) Cmder for Windows
  - Git for Windows
  - Visual Studio Code (VSC)
  - VSC Extensions
    - Remote Development
    - Git
  - Postman
  - Insomnia
  - Wireshark for Windows
- Ubuntu for WSL2 Software
  - docker.io
  - docker-compose
  - Git for Linux
  - curl
  - wget
  - unzip
  - (optional) tmux SSH terminal

## Network Connectivity

- Internet connection bandwidth: 100+ Mbps

## Note

As of 11/2020, VirtualBox cannot run on the same machine that uses WSL2.  WSL2 requires the Windows feature “Virtual Machine Platform”, which is not compatible with VirtualBox.