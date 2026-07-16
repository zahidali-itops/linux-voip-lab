		## Day01 ##
## Debian 12 Server Installation Steps
- Step01: copy-server-iso-file-to-kvm-installation-directory
- Step02: open-virt-manager
- Step03: local-install-media
- Step04: browse-media
- Step05: choose-ios-from-list
- Step06: uncheck-automatic-os-detection-and-select-debian12
- Step07: choose-memory-cpu
- Step08: select-GUI-install-press-enter
- Step09: choose-language
- Step10: choose-country
- Step11: choose-keyboard-language
- Step12: choose-hostname
- Step13: leave-empty-domain-name-and-continue
- Step14: choose-root-password
- Step15: choose-user-account-name
- Step16: choose-user-account-password
- Step17: configure-the-clock
- Step18: start-up-partitioner
- Step19: select-disk-to-partition
- Step20: select-partition-scheme-recommended-for-new-user
- Step21: finish-partition-and-press-enter-to-continue
- Step22: write-the-changes-to-disk-YES
- Step23: start-install-the-base-system
- Step24: scane-extra-installation-media?-NO
- Step25: select-debian-archive-mirror
- Step26: HTTP-proxy-leave-blank
- Step27: participate-in-the-package-usage-survey?-NO
- Step28: select-last-two-option-for-server-installation
- Step29: install-the-GRUB-boot-loader-to-your-primary-drive?-YES
- Step30: device-for-boot-loader-installation
- Step31: Finishing-installation
- Step32: installation-completed-reboot-system
- Step33: login-screen
- Step34: VoIPServer-show-in-VM-lists
- Step35: last-step-rm-ios-from-vm-directory
All steps is reference from screenshots directory

## Debian 12 Server Deployment

## Objective
- Prepare a dedicated Debian server for VoIP and Asterisk practice

## Learning Objectives
After completing this lab I will be able to:
- Install Debian 12
- Create a KVM Virtual Machine
- Configure SSH
- Configure Git
- Configure GitHub
Prepare the server for Asterisk

## Lab Environment
- Host OS: Debian 12
- Guest OS: Debian 12 (Bookworm)

## Virtual Machine
- hostname: VoIPServer
- Operating System: Debian GNU/Linux 12 (Bookworm)
- Virtualization: KVM/QEMU

## Network
- IP Address: 192.168.122.111
- Gateway: 192.168.122.1
- Network Interface: enp1s0

## Hardware
- RAM: 2 GB
- vCPU: 2
- Disk: 20GB (virtual Disk)

## Software Installed
- OpenSSH Server
- Git
- Vim
- Curl
- Wget
- Net-tools
- Tree

## Directory Structure
linux-voip-lab/
├── backups
├── configs
├── diagrams
├── docs
│   ├── day01-server-installation.md
│   ├── day02-asterisk-installation.md
│   └── day03-sip-extensions.md
├── README.md
├── resources
├── screenshots
│   ├── day01
│   │   ├── configuration
│   │   ├── installation
│   │   └── verification
│   ├── day02
│   └── day03
└── scripts


## Summary
During Day 1, the following tasks were completed:
- Installed Debian Server
- Configured SSH
- Updated repositories
- Installed Git
- Connected GitHub using SSH authentication
- Created GitHub repository
- Created project directory structure
## Notes
This virtual machine will be used to learn:
- Asterisk PBX
- SIP
- IVR
- Call Routing
- VoIP Administration
The entire learning process will be documented in GitHub as a professional portfolio project.
