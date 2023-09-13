
## 1.0 Network Fundamentals
    1.1 Explain the role and function of network components
        -Routers
        -Layer 2 and Layer 3 switches
        -Next-generation firewalls and IPS
        -Access points
        -Controllers (Cisco DNA Center and WLC)
        -Endpoints
        -Servers
        -PoE
    
    1.2 Describe characteristics of network topology architectures
        -Two-tier
        -Three-tier
        -Spine-leaf
        -WAN
        -Small office/home office (SOHO)
        -On-premise and cloud

    1.3 Compare physical interface and cabling types
        -Single-mode fiber, multimode fiber, copper
        -Connections (Ethernet shared media and point-to-point)

    1.4 Identify interface and cable issues (collisions, errors, mismatch duplex, and/or speed)

    1.5 Compare TCP to UDP
    
    1.6 Configure and verify IPv4 addressing and subnetting
    
    1.7 Describe the need for private IPv4 addressing
    
    1.8 Configure and verify IPv6 addressing and prefix
    
    1.9 Describe IPv6 address types
        -Unicast (global, unique local, and link local)
        -Anycast
        -Multicast
        -Modified EUI 64
    
    1.10 Verify IP parameters for Client OS (Windows, Mac OS, Linux)
    
    1.11 Describe wireless principles
        -Nonoverlapping Wi-Fi channels
        -SSID
        -RF
        -Encryption
    
    1.12 Explain virtualization fundamentals (server virtualization, containers, and VRFs)
    
    1.13 Describe switching concepts
        -MAC learning and aging
        -Frame switching
        -Frame flooding
        -MAC address table
---
## 2.0 Network Access
    2.1 Configure and verify VLANs (normal range) spanning multiple switches
        -Access ports (data and voice)
        -Default VLAN
        -InterVLAN connectivity
    
    2.2 Configure and verify interswitch connectivity
        -Trunk ports
        -802.1Q
        -Native VLAN
    
    2.3 Configure and verify Layer 2 discovery protocols (Cisco Discovery Protocol and LLDP)
    
    2.4 Configure and verify (Layer 2/Layer 3) EtherChannel (LACP)
    
    2.5 Interpret basic operations of Rapid PVST+ Spanning Tree Protocol
        -Root port, root bridge (primary/secondary), and other port names
        -Port states (forwarding/blocking)
        -PortFast
    
    2.6 Describe Cisco Wireless Architectures and AP modes
    
    2.7 Describe physical infrastructure connections of WLAN components (AP, WLC, access/trunk ports, and LAG)
    
    2.8 Describe AP and WLC management access connections (Telnet, SSH, HTTP, HTTPS, console, and TACACS+/RADIUS)
    
    2.9 Interpret the wireless LAN GUI configuration for client connectivity, such as WLAN creation, security settings, QoS profiles, and advanced settings

---
## 3.0 IP Connectivity
    3.1 Interpret the components of routing table
        -Routing protocol code
        -Prefix
        -Network mask
        -Next hop
        -Administrative distance
        -Metric
        -Gateway of last resort
        
    3.2 Determine how a router makes a forwarding decision by default
        -Longest prefix match
        -Administrative distance
        -Routing protocol metric
        
     3.3 Configure and verify IPv4 and IPv6 static routing
        -Default route
        -Network route
        -Host route
        -Floating static
        
    3.4 Configure and verify single area OSPFv2
        -Neighbor adjacencies
        -Point-to-point
        -Broadcast (DR/BDR selection)
        -Router ID
        
    3.5 Describe the purpose, functions, and concepts of first hop redundancy protocols
---
## 4.0 IP Services
    4.1 Configure and verify inside source NAT using static and pools
    
    4.2 Configure and verify NTP operating in a client and server mode
    
    4.3 Explain the role of DHCP and DNS within the network
    
    4.4 Explain the function of SNMP in network operations 2021 Cisco Systems, Inc. This document is Cisco Public. Page 4
    
    4.5 Describe the use of syslog features including facilities and levels
    
    4.6 Configure and verify DHCP client and relay
    
    4.7 Explain the forwarding per-hop behavior (PHB) for QoS, such as classification, marking, queuing, congestion, policing, and shaping
    
    4.8 Configure network devices for remote access using SSH
    
    4.9 Describe the capabilities and functions of TFTP/FTP in the network
---
## 5.0 Security Fundamentals
    5.1 Define key security concepts (threats, vulnerabilities, exploits, and mitigation techniques)
    
    5.2 Describe security program elements (user awareness, training, and physical access control)
    
    5.3 Configure and verify device access control using local passwords
    
    5.4 Describe security password policies elements, such as management, complexity, and password alternatives (multifactor authentication, certificates, and biometrics)
    
    5.5 Describe IPsec remote access and site-to-site VPNs
    
    5.6 Configure and verify access control lists
    
    5.7 Configure and verify Layer 2 security features (DHCP snooping, dynamic ARP inspection, and port security)
    
    5.8 Compare authentication, authorization, and accounting concepts
    
    5.9 Describe wireless security protocols (WPA, WPA2, and WPA3)
    
    5.10 Configure and verify WLAN within the GUI using WPA2 PSK
---
## 6.0 Automation and Programmability
    6.1 Explain how automation impacts network management
    
    6.2 Compare traditional networks with controller-based networking
    
    6.3 Describe controller-based, software defined architecture (overlay, underlay, and fabric)
        -Separation of control plane and data plane
        -Northbound and Southbound APIs
    
    6.4 Compare traditional campus device management with Cisco DNA Center enabled device management
    
    6.5 Describe characteristics of REST-based APIs (CRUD, HTTP verbs, and data encoding)
    
    6.6 Recognize the capabilities of configuration management mechanisms Puppet, Chef, and Ansible
    
    6.7 Recognize components of JSON-encoded data
    
