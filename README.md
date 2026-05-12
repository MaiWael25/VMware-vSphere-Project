# VMware-vSphere-Project

## Overview
This project demonstrates building a VMware vSphere environment using VMware Workstation.

The lab includes:
- Multiple ESXi hosts
- vCenter Server
- vSphere Cluster
- HA, DRS, FT, and vMotion configuration
- Shared NFS storage
- Virtual machine management

---

# Tasks Completed

## 1. ESXi Installation
- Installed 2 ESXi hosts as virtual machines in VMware Workstation

## 2. vCenter Deployment
- Deployed and configured vCenter Server Appliance (VCSA)

## 3. Add Hosts to vCenter
- Connected both ESXi hosts to vCenter

## 4. Create Cluster
- Created a vSphere cluster
- Enabled:
  - HA
  - DRS

## 5. Virtual Networking
Configured:
- Management Network
- VM Network
- Storage & vMotion Network

## 6. NFS Datastore
- Created and mounted shared NFS datastore

## 7. Virtual Machines
- Created VMs
- Installed Windows/Linux operating systems

## 8. Content Library
- Uploaded ISO files to a content library

## 9. VM Operations
Performed:
- Cloning
- Snapshots
- Template creation

## 10. vMotion
- Migrated VMs between ESXi hosts successfully

## 11. HA Testing
- Simulated ESXi host failure
- Verified VM restart on another host

## 12. Fault Tolerance (FT)
- Enabled FT for a virtual machine

---

# Lab Components

| Component | Description |
|---|---|
| VMware Workstation | Nested virtualization platform |
| ESXi Hosts | Hypervisors |
| vCenter Server | Centralized management |
| NFS Storage | Shared datastore |
| Windows/Linux VM | Guest operating systems |

---

# Skills Learned
- VMware ESXi
- vCenter Management
- vSphere Clustering
- HA & DRS
- FT & vMotion
- Virtual Networking
- Shared Storage

---
