# LAN-WAN-Network-Project



# LAN & WAN Network Simulation Project

This project simulates a complex network using Cisco Packet Tracer. It includes multiple LANs and WAN connections, with several servers providing key services like DHCP, DNS, TFTP, and Web services for popular websites such as Google, Facebook, and Instagram.

## Network Topology
- **3 Routers** (for WAN and LAN interconnection)
- **4 Switches** (connecting PCs and servers within the LAN)
- **Servers**: DNS, DHCP, TFTP, Web (Google, Facebook, Instagram)
- **Multiple PCs** connected to the network via switches.

## Key Services Configured
- **DHCP Server**: Automatically assigns IP addresses to devices.
- **DNS Server**: Resolves domain names like `google.com` to IP addresses.
- **TFTP Server**: Used for file transfers (e.g., device configurations).
- **Web Servers**:
  - `google.com` hosted on Server1
  - `facebook.com` hosted on Server2
  - `instagram.com` hosted on Server3

## Usage
1. Open the `.pkt` file using Cisco Packet Tracer.
2. Verify that all servers (DHCP, DNS, Web) are running.
3. Test the network by:
   - Using the web browser on any PC to access `google.com`, `facebook.com`, or `instagram.com`.
   - Ping between different network devices to ensure routing is functioning.
   
## How the Network is Structured
- **Router0**: Manages LAN1 with DHCP and DNS services.
- **Router1**: Interconnects the LANs via WAN.
- **Router2**: Hosts public web servers accessible via domain names.

## License
This project is released under the MIT License.

