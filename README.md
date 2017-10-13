# NetOps: Excercises for Network Automation Workshop

This repository contains sources for excercises generated during the
[Network Automation workshop](http://www.ipspace.net/NetAutWS)

## Subdirectories 
* Ansible: Ansible playbooks
* topology: Overview over the used topology

## Installation

I'm running Ansible in an virtual Ubuntu box on VMware ESXi Server. On the same server I installed the VIRL thing and extended it with a flat network connecting to the Ubuntu box. 

The networking examples are focused on Cisco IOS and Nexus OS. I run them in VIRL with a set up topology as described in [topology](topology/README.md). They are built for this particular setup consisting of two csr1000v Routers and two nx-osv switches running on VIRL.

