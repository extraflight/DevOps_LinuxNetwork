## 🖧 Linux Network

A hands-on project focused on configuring and managing Linux network infrastructure using virtual machines. This project covers core networking concepts from IP addressing and routing to advanced services like firewalls, DHCP, and NAT.

### 🛠️ Skills & Technologies Practiced

*   **IP Addressing & Subnetting:** Mastered calculating network addresses, netmasks, and host ranges using `ipcalc`.
*   **Static Routing:** Configured manual and persistent static routes between multiple machines and subnets.
*   **Network Diagnostics:** Utilized tools like `ping`, `traceroute`, `tcpdump`, `nmap`, and `iperf3` for connectivity testing and performance measurement.
*   **Firewall Management:** Implemented packet filtering and security policies using `iptables` to control traffic and secure services.
*   **Dynamic Host Configuration (DHCP):** Set up and configured an `isc-dhcp-server` for automatic IP address assignment, both dynamic and MAC-based.
*   **Network Address Translation (NAT):** Configured SNAT (for outbound traffic masquerading) and DNAT (for port forwarding) to enable access to internal services from external networks.
*   **SSH Tunneling:** Established both Local and Remote TCP forwarding to securely access services behind firewalls.

### 📁 Project Structure

The project is divided into logical parts, each building upon the previous one:

1.  **Part 1:** IP address and subnet mask calculations with `ipcalc`.
2.  **Part 2:** Static routing between two hosts.
3.  **Part 3:** Network bandwidth testing with `iperf3`.
4.  **Part 4:** Implementing a network firewall with `iptables` and host discovery with `nmap`.
5.  **Part 5:** Building a multi-subnet network with static routing and IP forwarding.
6.  **Part 6:** Automating IP configuration using a DHCP server.
7.  **Part 7:** Configuring NAT (SNAT & DNAT) for network access and service publishing.
8.  **Part 8 (Bonus):** Securely accessing services through SSH tunnels.

This project demonstrates a systematic understanding of building, securing, and troubleshooting a complex Linux network environment.