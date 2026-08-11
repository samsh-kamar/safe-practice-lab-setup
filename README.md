# Safe Practice Lab Setup

## Goal
Build an isolated lab environment on Linux to practice cybersecurity safely and legally.

## What I Built
- **Host OS**: Ubuntu 24.04 LTS
- **Hypervisor**: VirtualBox 7.x
- **VM**: Ubuntu Server 24.04 LTS
- **Network**: NAT for internet + Host-only network for VM-to-VM comms

## Steps Followed
1. Installed VirtualBox on Ubuntu host
2. Created Ubuntu Server VM for target practice
3. Configured Host-only adapter to isolate lab network from internet
4. Enabled snapshots to safely test commands and roll back
5. Practiced SSH between host and VM, and basic Linux CLI: users, permissions, `apt`, `systemctl`

## Skills Used
- Linux as daily OS: CLI, file permissions, process management
- Virtualization and VM networking: NAT, Host-only
- Safe lab practices: snapshots, network isolation
- Documentation

## Screenshots
`/screenshots`

- VirtualBox VM dashboard
- Host-only network settings
- SSH from host to VM
- ls -l output in VM
- whoami output in VM

## lesson learned
Running Linux as host taught me Linux fundamentals faster. Network isolation is key to practicing safely without affecting my main system.

