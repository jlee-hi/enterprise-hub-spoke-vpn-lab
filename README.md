# Enterprise Hub-and-Spoke IPSec VPN Lab

## 🎯 Overview
Complete enterprise-grade hub-and-spoke VPN lab featuring:
- Modern IKEv2 implementation with strong cryptography
- Redundant tunnels with automatic failover
- OSPF dynamic routing with loopback stability
- QoS for voice/video traffic
- Comprehensive SLA monitoring
- CSR1000v router configurations

## 🏗️ Network Topology
- **Hub:** Dallas (DAL-R1) with dual ISP connectivity
- **Spokes:** Los Angeles, Denver, Atlanta, Washington DC
- **Redundancy:** Primary/backup tunnels with SLA tracking
- **Routing:** OSPF with hub advertising default route

## 📁 Repository Structure
├── configs/           # Individual router configurations
├── docs/             # Documentation and guides
├── diagrams/         # Network topology diagrams
└── README.md         # This file

## 🚀 Quick Start
1. Review the [Deployment Guide](docs/deployment-guide.md)
2. Deploy configurations from the `configs/` directory
3. Follow testing procedures for verification

## 🔧 Technologies Used
- IPSec VTI with IKEv2
- OSPF dynamic routing
- QoS and traffic shaping
- SLA tracking and monitoring
- Cisco CSR1000v routers

## 📚 Learning Objectives
- Understand hub-and-spoke VPN topology
- Implement modern IPSec with IKEv2
- Configure redundancy and failover mechanisms
- Apply QoS for real-time traffic
- Monitor and troubleshoot VPN connectivity
