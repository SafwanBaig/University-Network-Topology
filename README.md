# University-Network-Topology

## Overview

This repository contains a comprehensive security assessment of a university's network infrastructure. The assessment includes a detailed analysis of the current network topology, identification of potential security risks, and proposed countermeasures to mitigate these risks. The network was mapped and analyzed using Cisco Packet Tracer.

## Table of Contents

1. [Problem Statement](#problem-statement)
2. [Network Topology Diagram and Configurations](#network-topology-diagram-and-configurations)
3. [Security Assessment Report and Countermeasures](#security-assessment-report-and-countermeasures)

## Problem Statement

The project involves selecting a university campus and analyzing its network topology. The network is mapped using Cisco Packet Tracer to identify existing security controls such as network segmentation, intrusion detection systems, firewalls, and authentication systems. An attack surface mapping is conducted to identify potential entry points for cyber-attacks, and countermeasures are proposed to mitigate these risks.

## Network Topology Diagram and Configurations

### Campus Network Analysis

The analysis covers the existing network topology, including the layout of devices and connections across the campus.

### Network Mapping

The network infrastructure was mapped using Cisco Packet Tracer, representing the placement and interconnectivity of routers, switches, firewalls, and other relevant network components. The network consists of the following devices:

- Routers (1941)
- Switches (2960-24TT)
- Email Server
- DNS Server
- Web Server (HTTP)
- Wireless Devices (Access Points)
- PCs
- Laptops
- Smartphones

### Configurations

Detailed IP configurations for various segments of the network, including administrative and academic blocks, library, and wireless access points, are provided.

## Security Assessment Report and Countermeasures

### Identified Security Risks

1. **Network Segmentation**: Lack of proper segmentation across multiple segments.
2. **Default Gateway and DNS Server Configuration**: Centralized configuration posing a single point of failure.
3. **Password Security**: Weak and uniform passwords susceptible to brute-force attacks.
4. **Lack of Network Monitoring and Intrusion Detection**: Absence of systems to monitor and detect network intrusions.

### Proposed Solutions and Countermeasures

1. **Network Segmentation**: Implementing proper network segmentation to limit the impact of attacks.
2. **Default Gateway and DNS Server Configuration**: Distributing configuration across multiple servers to reduce single point of failure risks.
3. **Password Security**: Enforcing strong, complex passwords and implementing multi-factor authentication (MFA).
4. **Network Monitoring and Intrusion Detection**: Deploying robust network monitoring and intrusion detection systems.

## Deliverables

1. **Network Topology Diagram**: Visual representation of the existing infrastructure and attack surface findings.
2. **Security Assessment Report**: Detailed report highlighting identified security risks and proposed solutions.

## Conclusion

The current network configuration exposes several security risks that need to be addressed promptly to protect the network and its assets from potential cyber threats. Implementing the proposed solutions and countermeasures will significantly improve the security posture and reduce the attack surface risks.

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
