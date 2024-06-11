
# Overview
This project showcases the creation of a virtual network environment using Kathara on a virtual machine hosted on a server. The network setup includes the implementation of both static and dynamic routing protocols, as well as the configuration of DNS and HTTP servers. The project aims to provide a comprehensive understanding of network design and management.


# Routing
Red Network (RIP): The red network utilizes the Routing Information Protocol (RIP) for dynamic routing. RIP is implemented to facilitate automatic route updates and efficient routing within the red network.

Green Network (OSPF): The green network is configured with the Open Shortest Path First (OSPF) protocol. OSPF provides faster convergence and more efficient routing decisions compared to RIP, making it suitable for the green network.

Blue Network (Static Routing): The blue network is managed using static routing. Static routes are manually configured to provide fixed paths for data packets, ensuring predictable and stable routing within the blue network.

# Servers

HTTP Servers: Servers 1 and 3 are configured as HTTP servers. These servers host web services and can be accessed within the network for testing and demonstration purposes.

DNS Servers: Servers 2 and 4 are set up as DNS servers. They handle domain name resolution, translating domain names into IP addresses for devices within the network.

# Tools and Technologies
Wireshark: Wireshark is used for packet capture and analysis. It helps in monitoring network traffic, troubleshooting issues, and verifying the implementation of routing protocols.

Cisco Packet Tracer: Cisco Packet Tracer is employed to create a visual representation of the network. This tool provides a clear and detailed view of the network topology, aiding in the design and documentation process.

Docker: Docker is utilized to create individual containers for each network device. This approach ensures isolation, scalability, and ease of management for the virtual network environment.

ESXi: The server is equipped with ESXi, a hypervisor that enables virtualization. ESXi allows the creation and management of multiple virtual machines, providing a robust platform for running the network simulation.
