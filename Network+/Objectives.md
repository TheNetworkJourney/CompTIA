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

    2.2 Compare and contrast routing technologies and bandwidth management concepts.

    2.3 Given a scenario, configure and deploy common ethernet switching features.

    2.4 Given a scenario, install and configure the appropriate wireless standards and technologies.

## 3.0 Network Operations

    3.1 Given a scenario, use the appropriate statistics and sensors to ensure network availibility.

    3.2 Explain the purpose of organizational documents and policies.

    3.3 Explain high availibility and disaster recovery concepts and summarize which is the best solution.

## 4.0 Network Security

    4.1 Explain common security concepts.

    4.2 Compare and contrast common types of attacks.
  
    4.3 Given a scenario, apply network hardening tools.

    4.4 Compare and contrast remote access methods and security implications.

    4.5 Explain the importance of physical security.

## 5.0 Network Troubleshooting

    5.1 Explain the network troubleshooting methodology.

    5.2 Given a scenario, troubleshoot common cable connectivity issues and select the appropriate tools

    5.3 Given a scenario, use the appropriate network software tools and commands.

    5.4 Given a scenario, troubleshoot common wireless connectivity issues.

    5.5 Given a scenario, troubleshoot general networking issues.

