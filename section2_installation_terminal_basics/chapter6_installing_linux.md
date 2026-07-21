# Chapter 6: Installing Linux

## Why Install Linux?
As a Cloud & DevOps Engineer, most servers you work with run Linux:
- AWS EC2
- Azure Virtual Machines
- Google Compute Engine
- Docker Containers
- Kubernetes Worker Nodes
- Jenkins Servers
- GitLab Runners

## Ways to Use Linux
1. **Dual Boot** → Full performance, but requires partitioning.
2. **Virtual Machine (Recommended)** → Safe, easy reset, e.g. VirtualBox.
3. **Windows Subsystem for Linux (WSL)** → Fast, great for dev, but not identical to full server.
4. **Cloud VM (Best for DevOps)** → Practice on AWS EC2, closest to production.

## Which One Should You Use?
| Purpose      | Best Choice |
|--------------|-------------|
| Learning     | VirtualBox  |
| Development  | WSL         |
| DevOps       | AWS EC2     |
| Production   | Cloud Servers |

## Ubuntu Installation (VirtualBox Example)
1. Download Ubuntu ISO.
2. Install VirtualBox.
3. Create new VM.
4. Allocate RAM (4 GB), CPU (2 cores), Disk (25 GB).
5. Attach Ubuntu ISO.
6. Start VM.
7. Install Ubuntu.
