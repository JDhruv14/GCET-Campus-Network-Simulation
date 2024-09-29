# GCET-Campus-Network-Simulation

This project simulates the network setup for G H Patel College of Engineering and Technology (GCET) using Cisco Packet Tracer. The simulation showcases the integration of various network components and technologies to facilitate communication across multiple departments.

## What We Are Trying to Achieve
The goal of this project is to create a functional model of the college's network infrastructure. We aim to connect various departments—including Computer, IT, EC, Civil, and Administration—demonstrating efficient communication and resource access. By implementing technologies such as dynamic routing with RIP and DNS services, we provide a practical application of networking concepts, enhancing students' understanding of real-world network setups.

## Technologies Used
- **Dynamic Routing using RIP**: Enables efficient data routing between different networks.
- **DNS Server**: Resolves domain names to IP addresses, facilitating easier access to resources.
- **Router Extension**: Allows for additional serial connections between routers.
- **Cisco Packet Tracer**: A network simulation tool used to design and visualize network topologies.

## Network Setup
The simulation includes:
- **Devices**: 
  - **10 PCs**: Distributed across various departments for user access.
  - **6 Switches**: Connect the PCs within their respective departments.
  - **2 Routers**: Manage routing between different network segments.
  - **2 Servers**: Host services like DNS and HTTP.
  - **1 Laptop**: Connected to the network for additional user access.
- **Connections**:
  - Each department is connected through switches to the main campus router.
  - The Civil Department is connected to a secondary router, which links back to the main router using a serial cable.

## Installation
1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/gcet-campus-network-simulation.git

# Conclusion
- The GCET Campus Network Simulation effectively illustrates the configuration and management of a campus network. This project not only enhances understanding of networking principles and practices but also demonstrates the practical application of theoretical knowledge. By successfully implementing dynamic routing, DNS services, and multi-department connectivity, the simulation provides valuable insights into building and managing real-world network infrastructures in an educational environment.
