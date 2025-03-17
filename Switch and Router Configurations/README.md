# 🚀 Static & Dynamic NAT Configuration Collection

This repository contains various NAT (Network Address Translation) configurations implemented using Cisco Packet Tracer. The projects in this repository focus on both **Static NAT** and **Dynamic NAT** configurations, demonstrating the use of these technologies in different network environments. These configurations will help you understand how to manage IP address translation in both small and large networks.

## 📂 Included Configurations

### 1️⃣ **Static NAT Configuration**
This section contains the configuration for **Static NAT**, which maps a private IP address to a specific public IP address. This configuration is commonly used for services that need to be accessed from outside the network, such as web servers or email servers. The project demonstrates how to configure a one-to-one mapping for specific internal devices.

**Key Features:**
- Static mapping of private to public IP addresses.
- Used for services requiring external access.
- Example configurations for web and email servers.

### 2️⃣ **Dynamic NAT Configuration**
The **Dynamic NAT** configuration allows a pool of public IP addresses to be dynamically assigned to devices in a private network. This configuration is useful when there are more private devices than public IP addresses available. The project includes the setup of NAT with a pool of public IPs and a configuration for translating multiple internal addresses to available public IPs.

**Key Features:**
- Dynamic assignment of public IPs from a pool.
- Translation of multiple internal IPs to available public IPs.
- Useful in environments with limited public IP addresses.
