# Cloud Deployment for PCS HA Gateway

## Purpose
This repository documents how the PCS-based HA gateway is deployed on cloud
infrastructure.

## Cloud Considerations
- Unicast Corosync communication
- Security group/firewall rules
- Cloud VM failure scenarios
- Cloud-compatible fencing mechanisms

## Environment
- Cloud VMs in the same network/VPC
- Private IP communication

## Note
The core PCS architecture remains unchanged from the local setup.



## Related Architecture Documentation

- Core PCS HA Architecture Overview:  
  https://github.com/khushi-org/architecture-docs
- PCS Architecture Diagrams (if available):  
  https://github.com/khushi-org/architecture-docs/tree/main/diagrams
- PCS HA Gateway Implementation:  
  https://github.com/khushi-org/pcs-ha-gateway
