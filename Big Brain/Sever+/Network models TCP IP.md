
| OSI          |           TCP/IP            |
| ------------ | :-------------------------: |
| Application  |         Application         |
| Presentation |         Application         |
| Session      |         Application         |
| Transport    |  Transport / Host-to-Host   |
| Network      |          Internet           |
| Data Link    | Network Access / Link Layer |
| Physical     | Network Access / Link Layer |

OSI Model Cheat Sheet
[[The All-In-One OSI Model Cheat Sheet 2024 (stationx.net)](https://www.stationx.net/osi-model-cheat-sheet/)]()


1. **Layer 7: Application**
    
    - Provides an interface for software applications to communicate with the network.
    - Protocols: HTTP, HTTPS, FTP, DNS
    - Functions: Resource sharing, remote file access, directory services
2. **Layer 6: Presentation**
    
    - Translates data between the application layer and the network.
    - Protocols: SSL/TLS
    - Functions: Data encryption/decryption
3. **Layer 5: Session**
    
    - Manages sessions between end-user applications.
    - Protocols: NetBIOS names, RPC
    - Functions: Establishes session parameters including duplex operation
4. **Layer 4: Transport**
    
    - Provides reliable data transfer across a network.
    - Protocols: TCP/UDP
    - Functions: Error recovery & flow control
5. **Layer 3: Network**
    
    - Determines how data is sent to the receiver through routing.
    - Protocols: IP (IPv4 & IPv6), ICMP, OSPF, BGP
    - Functions: Routing decision-making based on logical addressing
6. **Layer 2: Data Link**
    
    - Sends and receives frames from the network layer.
    - Protocols: Ethernet, Wi-Fi, PPP
    - Functions: MAC address processing, error detection/correction
7. **Layer 1: Physical**
    
    - Transmits raw bit stream over a physical medium.
    - Protocols: Cables, Hubs, Repeaters
    - Functions: Data encoding/decoding, electrical signal transmission