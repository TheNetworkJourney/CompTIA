This is my own personal knowledge of the subjects of the Network+ as I am learning it. This is by no means all inclusive of what someone would need for the exam but I will try and put out it simply as it is shown on the objectives so people could start with. I will also include resources I used to deepen the knowledge.

## 1.0 Networking Fundamentals

    1.1 Compare and contrast the Open System Interconnection (OSI) model layers and encapsulation concepts.
        OSI model
        -Layer 1 Physical
        -Layer 2 Data Link
        -Layer 3 Network
        -Layer 4 Transport
        -Layer 5 Session
        -Layer 6 Presentation
        -Layer 7 Application

        Data Encapsulation adn Decapsulation
        -Ethernet Header
        -IP Header
        -TCP/UDP Headers
        -TCP flags
        -Payload
        -Maximum Transmission unit (TMU)
        
    1.2 Explain the characteristics of network topologies and network types.
        Topologies
        -Mesh
        -Star/Hub-and-Spoke
        -Bus
        -Ring
        -Hybrid

        Network Types
        -Peer-to-Peer
        -Client-Sever
        -Local Area Network (LAN)
        -Metropolitan Area Network (MAN)
        -Personal Area Network (PAN)
        -Wide Area Network (WAN)
        -Wireless Local Area Network (WLAN)
        -Campus Area Network (CAN)
        -Storage Area Network (SAN)
        -Software-defined Wide Area Network (SDWAN)
        -Multiprotocol Label Switching (MPLS)
        -Multipoint Generic Routing Encapsulation (mGRE)

        Service-related Entry Point
        -Demarcation Point
        -Smartjack

        Virtual Network Concepts
        -vSwitch
        -Virtual Network Interface Card (vNIC)
        -Network Function Virtualization (NFV)
        -Hypervisor

        Provider Links
        -Satellite
        -Digital Subscriber Line (DSL)
        -Cable
        -Leased Line
        -Metro-optical
        
    1.3 Summarize the types of cables and connectors and explain which is the apprpriate type for a solution.
        Copper
        -Twisted Pair
            -Cat 5
            -Cat 5e
            -Cat 6
            -Cat 6a
            -Cat 7
            -Cat 8
        -Coaxial/RG-6
        -Twinaxial
        -Termination Standards
            -TIA/EIA-568A
            -TIA/EIA-568B
            
        Fiber
        -Single-mode
        -Multimode

        Connector Types
        -Local Connector (LC)
        -Straight Tip (ST)
        -Subscriber Connector (SC)
        -Mechanical Transfer (MT)
        -Registered Jack (RJ)
        -Angled Physical Contact (APC)
        -Ultra-physical Contact (UPC)
        -RJ11
        -RJ45
        -F-type Connector
        
        Transceivers/Media Converters
        -Transceiver Type
            -Small form-factor plyggable (SFP)
            -Enhanced form-facto pluggable (SFP+)
            -Quad small form-factor pluggable (QSPF)
            -Enhanced quad small form-factor pluggable (QSPF+)

        Cable Management
        -Patch Panel/Patch Bay
        -Fiber Distribution Panel
        -Punchdon Block
            -66
            -110
            -Krone
            -Bix

        Ethernet Standards
        -Copper
            -10BASE-T
            -100BASE-TX
            -1000BASE-T
            -10GBASE-T
            -40GBASE-T
        -Fiber
            -100BASE-FX
            -100BASE-SX
            -1000BASE-SX
            -10000BASE-LX
            -10GBASE-SR
            -10GBASE-LR
            -Coarse Wavelength Division Multiplexing (CWDM)
            -Dense Wavelength Division Multiplexing (DWDM)
            -Bidirectional Wavelenght Division Multiplexing (WDM)

    1.4 Given a scenario, configure a subet and use appropriate IP addressing schemes.
        Public vs Private
        -RFC1918
        -Network Address Translation (NAT)
        -Port Address Translation (PAT)

        IPv4 vs IPv6
        -Automatic Private IP Addressing (APIPA)
        -Extended Unique Identifier (EUI-64)
        -Multicast
        -Unicast
        -Anycast
        -Broadcast
        -Link Local
        -Loopback
        -Default Gateway

        IPv4 Subnetting
        -Classless (variable-length subnet mask)
        -Classful
            -A
            -B
            -C
            -D
            -E
        -Classless Inter-Domain Routing (CIDR) Notation

        IPv6
        -Tunneling
        -Dual Stack
        -Shorthand Notation
        -Router Advertisement
        -Stateless Address Autoconfiguration (SLAAC)

        Virtual IP (VIP)

        Subinterfaces
        
    1.5 Explain common ports and protocols, their application, and encrypted alternatives.
        -20/21 File Transfer Protocol (TFP)
        -22 Secure Shell (SSH)
        -22 Secure File Transfer Protocol (SFTP)
        -23 Telnet
        -25 Simple Mail Transfer Protocol (SMTP)
        -53 Domain Name System (DNS)
        -67/68 Dynamic Host Configuration Protocol (DHCP)
        -69 Trivial File Transfer Protocol (TFTP)
        -80 Hypertext Transfer Protocol (HTTP)
        -110 Post Office Protocol v3 (POP3)
        -123 Network Time Protocol (NTP)
        -143 Internet Message Access Protocol (IMAP)
        -161/162 Simple Network Management Protocol (SNMP)
        -389 Ligthweight Directory Access Protocol (LDAP)
        -443 Hypertext Transfer Protocl Secure (HTTPS)[Secure Sockets Layer (SSL)]
        -443 HTTPS [Transport Layer Security (TLS)]
        -445 Server Message Block (SMB)
        -514 Syslog
        -587 SMTP TLS
        -636 Lightweight Directory Access Protocol (over SSL)(LDAPS)
        -993 IMAP over SSL
        -995 POP3 over SSL
        -1433 Structured Query Language (SQL) Server
        -1521 SQLnet
        -3306 MySQL
        -3389 Remote Desktop Protocol (RDP)
        -5060/5061 Session Initiation Protocol (SIP)

        IP Protocol Types
        -Internet Control Message Protocl (ICMP)
        -TCP
        -UDP
        -Generic Routing Encapsulation (GRE)
        -Internet Protocol Security (IPSec)
            -Authentication Header (AH)/Encapsulation Security Payload (ESP)
        -Connectionless vs Connection-oriented
        
    1.6 Explain the use and purpose of network services.
        DHCP
        -Scope
        -Exclusion Ranges
        -Reservations
        -Dynamic Assignment
        -Static Assignment
        -Lease Time
        -Scope Options
        -Available Leases
        -DHCP Relay
        -IP Heper/UDP Forwarding

        DNS
        -Record Types
            -Address (A vs AAAA)
            -Canonical Name (CNAME)
            -Mail Exchange (MX)
            -Start of Authority (SOA)
            -Pointer (PTR)
            -Text (TXT)
            -Service (SRV)
            -Name Server (NS)
        -Global Hierarchy
            -Root DNS Server
        -Internal vs External
        -Zone Transfer
        -Authoritative Name Servers
        -Time To line (TTL)
        -DNS Caching
        -Reverse DNS/Reverse Lookup/Forward Lookup
        -Recursive lookup/iterative lookup

        NTP
        -Stratum
        -Clients
        -Servers
        
    1.7 Explain basic corporate and datacenter network architecture.
        Three-tiered
        -Core
        -Distribution/Aggregation Layer
        -Access/Edge

        Software-Definded Netwoking
        -Application Layer
        -Control Layer
        -Infrastructure Layer
        -Management Plane

        Spine and Leaf
        -Software-defined network
        -Top-of-Rack Switching
        -Backbone

        Traffic Flows
        -North-South
        -East-West

        Branch Office vs On-premises datacenter vs colocation

        Storage Area Networks
        -Connection Types
            -Fibre Channels over Ethernet (FCoE)
            -Fibre Channel
            -Internet Small Computer Systems Interface (iSCI)
            
    1.8 Summarize cloud concepts and connectivity options.
        Deployment Models
        -Public
        -Private
        -Hybrid
        -Community

        Service Models
        -Software as a Service (SaaS)
        -Infrastructure as a Service (IaaS)
        -Platform as a Service (PaaS)
        -Desktop as a Service (DaaS)

        Infrastructure as code
        -Automation/Orchestration

        Connectivity Options
        -Virtual Private Network (VPN)
        -Private-Direct Connection to cloud Provider

        -Multitenancy
        -Elasticity
        -Scalability
        -Security Implications
        
## 2.0 Network Fundamentals

    2.1 Compare and contrast various devices, their features, adn their appropriate placement on the network.
        Networking Devices
        -Layer 2 Switch
        -Layer 3 Capable Switch
        -Router
        -Hub
        -Access Point
        -Bridge
        -Wireless LAN Controller
        -Load Balancer
        -Proxy Server
        -Cable Modem
        -DSL Modem
        -Repeater
        -Voice Gateway
        -Media Converter
        -Intrusion Prevention System (IPS)/Intrusion Detection System (IDS) Device
        -Firewall
        -VPN Headend

        Networked Devices
        -Voice over Internet Protocol (VoIP) Phone
        -Printer
        -Physical Access Control Devices
        -Cameras
        -Heating, Ventilation, and Air Conditioning (HVACS) sensors
        -Internet of Things (IoT)
        -Industrial Control Systems/Supervisory Control and Data Acquisition (SCADA)
        
    2.2 Compare and contrast routing technologies and bandwidth management concepts.
        Routing
        -Dynamic Routing
            -Protocols (RIP,OSPF,EIGRP,BGP)
            -Link state vs distance vector vs hybrid
        -Static Routing
        -Default Routing
        -Administrative Distance
        -Exterior vs Interior
        -Time to Live

        Bandwidth Management
        -Traffic Shaping
        -Quality of Server (QoS)
    2.3 Given a scenario, configure and deploy common ethernet switching features.
        -Data Virtual Local Area Network (VLAN)
        -Voice VLAN
        Port Configuration
            -Port Tagging/802.1Q
            -Port Aggregation
                Link Aggregation Contol Protocol (LACP)
            -Duplex
            -Speed
            -Flow Control
            -Port Mirroring
            -Port Security
            -Jumbo Frames
            -Auto-medium-dependent interface crossover (MD-X)
        -Media Access Control (MAC) address Tables
        -Power of Ethernet (PoE)/Power over Ethernet plus (PoE+)
        -Spanning Tree Protocol
        -Carrier-sense multiple access with collision detection (CSMA/CD)
        -Address Resolution Protocol (ARP)
        -Neighbor Discovery Protocol
        
    2.4 Given a scenario, install and configure the appropriate wireless standards and technologies.
        802.11 Standards
        -a
        -b
        -g
        -n
        -ac
        -ax

        Freq and Range
        -2.4
        -5

        Channels
        -Regulatory Impacts

        Service Set Identifier (SSID)
        -Basic Service Set
        -Extended Service Set
        -Independent basic service set (Ad-hoc)
        -Roaming

        Antenna Types
        -Omni
        -Directional

        Encryption Standards
        -WiFi Protected Access (WPA)/WPA2 Personal[Advanced Encryption Standard (AES)]/Temporal Key Integrity Protocol (TKIP)
        -WPA/WPA2 Enterprise(AES/TKIP)

        Cellular Technologies
        -Code-division mutliple access (CDMA)
        -Global System for Mobile Communications (GSM)
        -Long-term Evolution (LTE)
        -3G,4G,5G

        Multiple input, multiple output (MIMO) and Mulit user MIMO (MU-MIMO)
        
## 3.0 Network Operations

    3.1 Given a scenario, use the appropriate statistics and sensors to ensure network availibility.
        Performance Metrics/Sensors
        -Device/Chassis
            -Temp
            -CPU Usage
            -Memory
        -Network Metrics
            -Bandwidth
            -Latency
            -Jitter
            
        SNMP
        -Traps
        -Object Identifiers (OIDs)
        -Management Information Bases (MIBs)

        Network Device Logs
        -Log Reviews
            -Traffic
            -Audit
            -Syslog
        -Logging Levels/Severity Levels
        
        Interface Statistics/Status
        -Link State (up/down)
        -speed/duplex
        -send/receive traffic
        -Cyclic Redundancy checks (CRCs)
        -Protocol Packet and byte count
        
        Interface Errors or Alerts
        -CRC erros
        -Giants
        -Runts
        -Encapsulation errors
        
        Enviromental Factors and Sensors
        -Temp
        -Humidity
        -Electrical
        -Flooding
        
        Baselines

        NetFlow Data

        Uptime/Downtime
        
    3.2 Explain the purpose of organizational documents and policies.
        Plans and Procedures
        -Change management
        -Incident Response Plan
        -Disaster Recovery Plan
        -Business Continuity Plan
        -System Life Cycle
        -Standard Operating Procedures

        Hardening and Security Policies
        -Password Policy
        -Acceptable Use Policy
        -Bring your own device (BYOD) Policy
        -Remote Access Policy
        -Onboarding and offboarding Policy
        -Security Policy
        -Data Loss Prevention

        Common Documentation
        -Physical Network Diagram
            -Floor Plan
            -Rack Diagram
            -Intermediate Distribution Frame (IDF)/Main Distribution Frame (MDF) Documentation
        -Logical Network Diagram
        -Wiring Diagram
        -Site Survey Report
        -Audit and Assessment Report
        -Baseline Configurations

        Common Agreements
        -Non-Disclosure Agreement (NDA)
        -Service-level Agreement (SLA)
        -Memorandum of Understanding (MOU)
        
    3.3 Explain high availibility and disaster recovery concepts and summarize which is the best solution.
        Load Balancing
        
        Multipathing
        
        Network Interface Card (NIC) teaming
        
        Redundant Hardware/Clusters
            -Switch
            -Firewall
            -Routers

        Facilities and Infrastructure Support
        -Uninterrptible Power Supply (UPS)
        -Power Distrobution Unit (PDU)
        -Generator
        -HVAC
        -Fire Suppression

        Redundancy and High Availibility (HA) Concepts
        -Cold Site
        -Warm Site
        -Hot Site
        -Cloud Site
        -Active-acitve vs. active-passive
            -Multiple Internet Service Providers (ISPs)/Diverse Paths
            -Virtual Router Redundancy Protocol (VRRP)/First Hop Redundancy Protocol (FHRP)
        -Mean time to repair (MTTR)
        -Mean time between failure (MTBF)
        -Recovery Time Objective (RTO)
        -Recovery Point Objective (RPO)

        Network Device Backup/Restore
        -State
        -Configuration
        
## 4.0 Network Security

    4.1 Explain common security concepts.
        Confidentiality, Integrity, Availibility (CIA)

        Threats
        -Internal
        -External

        Vulnerabilities
        -Common vulnerabilities and Exposures (CVE)
        -Zero-day

        Exploits

        Least Pivilige

        Role-based Access

        Zero Trust

        Defense in Depth
        -Network Segmentation Enforcement
        -Perimeter Network (DMZ)
        -Separation of Duties
        -Network Access Control
        -Honeypot

        Authentication Methods
        -Multifactro
        -Terminal Access Controller Access-control System Plus (TACACS+)
        -Single Sign-on (SSO)
        -Remote Authentication Dial-in User Service (RADIUS)
        -Lightweight Directory Access Protocol (LDAP)
        -Kerberos
        -Local Authentication
        -802.1X
        -Extensible Authentication Protocol (EAP)

        Risk Management
        -Security Risk Assessment
            -Threat Assessment
            -Vulnerability Assessment
            -Penetration Testing
            -Posture Assessment
        -Business Risk Assessments
            -Process Assessment
            -Vendor Assessment

        Security Information and Event Management (SIEM)
        
    4.2 Compare and contrast common types of attacks.
        Technology-Based
        -Denial-of-Service (DoS)/Distributed Denial-of-Service (DDoS)
        -On-path attach (Man-in-the-middle attack)
        -DNS Poisoning
        -VLAN Hopping
        -ARP Spoofing
        -Rogue DHCP
        -Rogue Access Point (AP)
        -Evit Twin
        -Ransomware
        -Password Attacks
            -Brute-force
            -Dictionary
        -MAC Spoofing
        -IP Spoofing
        -Deauthentication
        -Malware

        Human and Environment
        -Social Engineering
            -Phishing
            -Taligating
            -Piggybacking
            -Shoulder Surfing
            
    4.3 Given a scenario, apply network hardening tools.
        Best Practices
        -Secure SNMP
        -Router Advertisement (RA) Guard
        -Port Security
        -Dynamic ARP Inspection
        -Contol Plane Policing
        -Private VLANs
        -Disable unneeded switchports
        -Disable unneeded network services
        -Change Default Passwords
        -Password Complexity/length
        -Enable DHCP Snooping
        -Change Default VLAN
        -Patch and Firmware Management
        -Access Control List
        -Role-based Access
        -Firewall Rules
            -Explicit Deny
            -Implicit Deny

        Wireless Security
        -MAC Filtering
        -Antenna Placement
        -Power Levels
        -Wireless Client Isolation
        -Guest Network Isolation
        -Preshared Keys (PSKs)
        -EAP
        -Geofencing
        -Captive Portal

        IoT Access Considerations
        
    4.4 Compare and contrast remote access methods and security implications.
        Site-to-site VPN

        CLient-to-site VPN
        -Clientless VPN
        -Split Tunnel vs Full Tunnel

        Remote Desktop Connection

        Remote Desktop Gateway

        SSH

        Virtual Networking Comptuing (VNC)

        Virtual Desktop

        Authentication and Authorization Considerations

        In-band vs Out-of-band Management
        
    4.5 Explain the importance of physical security.
        Detection Methods
        -Camera
        -Motion Detection
        -Asset Tags
        -Tamper Detection

        Prevention Methods
        -Employee Training
        -Access Control Hardware
            -Badge Readers
            -Biometrics
        -Locking Racks
        -Locking Cabinets
        -Access Control Vestibule (Mantrap)
        -Smart Lockers

        Asset Disposal
        -Factory reset/wipe configuration
        -Sanitize Devices for Disposal
        
## 5.0 Network Troubleshooting

    5.1 Explain the network troubleshooting methodology.

    5.2 Given a scenario, troubleshoot common cable connectivity issues and select the appropriate tools

    5.3 Given a scenario, use the appropriate network software tools and commands.

    5.4 Given a scenario, troubleshoot common wireless connectivity issues.

    5.5 Given a scenario, troubleshoot general networking issues.

