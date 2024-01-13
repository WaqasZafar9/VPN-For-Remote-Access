# VPN Project Repository

## Introduction

A Virtual Private Network (VPN) is a service designed to establish a secure, encrypted connection to ensure privacy and anonymity while utilizing the internet. VPNs extend a private network across a public network, enabling users to securely send and receive data.

## Why use a VPN?

1. **Privacy and Anonymity:** VPNs hide a user's browser history, IP address, and geographical location, enhancing security and preventing unauthorized access to personal data.
2. **Bypassing Geographical Restrictions:** VPNs enable access to restricted content based on location, allowing users to visit otherwise unavailable websites.
3. **Remote Access:** VPNs provide secure remote access to a company's network, facilitating work from home or while traveling.
4. **Public WiFi Security:** VPNs protect users on public WiFi networks from hackers and cybercriminals attempting to intercept sensitive information.

## How VPNs Work

1. **Tunneling Protocols:** VPNs utilize tunneling protocols like OpenVPN, SSTP, and IKEv2 for data encryption and decryption.
2. **Encryption:** VPNs use encryption to secure data transmitted over the internet, preventing unauthorized reading without the decryption key.
3. **IP Address Masking:** VPNs replace a user's IP address with that of the VPN server, maintaining anonymity and preventing tracking.

## Types of VPNs

1. **Remote Access VPNs:** Allow individual users to securely connect to a private network over the internet.
2. **Site-to-Site VPNs:** Connect entire networks in different locations, ensuring secure communication between them.
3. **Hardware VPNs:** Physical devices providing VPN functionality, commonly used for added security in enterprise environments.

## Software Used

- Cisco Packet Tracer

## Visual Representation

*Insert visual representation here*

## Process

In this scenario, specific network devices were chosen, including Cisco 1941 routers, a 2960-24 switch with a battery backup, and a server.

### Cisco 1941 Routers

- **High-Performance Routing:** Known for high-performance capabilities suitable for routing tasks.
- **Scalability:** Offers scalability to accommodate growing network needs.
- **Security Features:** Advanced security features for firewall capabilities, access control, and VPN support.
- **Modular Design:** Flexibility in adding modules for specific functionalities.
- **Reliability:** Ensures uninterrupted connectivity and minimizes downtime.

### Cisco 2960-24 Switch

- **Network Switching:** Used for local network switching, providing high-performance and low-latency communication.
- **Port Density:** With 24 ports, accommodates numerous devices within the local network.
- **Battery Backup:** Ensures continuous power supply, crucial for maintaining network operations during power outages.

### Server

The server serves various purposes, contributing to the overall functionality, efficiency, and management of the network:

- Centralized Resource Hosting
- User Authentication and Authorization
- Network Services
- Data Storage and Backup
- Application Hosting
- Security Management
- Power Resilience and Controlled Shutdown
- Centralized Updates and Patch Management
- Network Administration and Monitoring

## Working

### Network Connectivity

The Cisco 1941 routers are responsible for routing traffic within your network. They facilitate communication between different subnets and connect your local network to the internet.

### VPN Tunnel Configuration

The routers are configured to establish an IPSec VPN tunnel between them. This tunnel allows secure communication between the routers, even if they have duplicate LAN subnets. The VPN ensures that data exchanged between the routers is encrypted and secure.

### Switching and Local Network Connectivity

The Cisco 2960-24 switch is used for local network switching. It provides efficient communication between devices within your local network, allowing devices to connect, communicate, and share resources seamlessly.

### Server Functionality

The server serves as a centralized hub for hosting various resources, including applications, databases, and shared files. It provides a platform for user authentication and authorization, ensuring secure access to network resources.

### Accessing Server from Worker 1

*Insert specific details on how to access the server from Worker 1.*

### Worker 3 to Main Office

*Insert details on Worker 3 accessing the Main Office.*

## Conclusion

In conclusion, the successful implementation of this project relies on the Cisco 1941 routers, which play a pivotal role in establishing a secure and efficient network infrastructure. Through the deployment of IPsec VPN tunnels, the project ensures data confidentiality and integrity, addressing challenges related to duplicate LAN subnets. The routers excel in routing tasks, enhancing network scalability and reliability. Emphasizing the strategic use of Cisco 1941 routers, the project showcases their adaptability, high-performance routing, and security features, particularly in firewall configurations and intrusion prevention. This streamlined approach underscores the routers' cost-effectiveness, providing a resilient and secure network infrastructure.

## Reference Videos

- [Video 1](https://youtu.be/LlL2DkFkACo?si=IPsOMUctbyxPouGO)
- [Video 2](https://youtu.be/SYGdxsDApyM?si=zbzzzsL6C5M8rKBF)
- [Video 3](https://youtu.be/lkUq6Pl6his?si=1F5TJhH2QunpZBRV)
- [Video 4](https://youtu.be/8uWmFkrn6qE?si=eLMZ46x2v4IG6UuO)

" > README.md
