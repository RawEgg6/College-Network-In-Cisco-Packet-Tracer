# 🎓 College Network Infrastructure – Cisco Packet Tracer Project

This project simulates a complete campus network for a college environment using **Cisco Packet Tracer**. It includes multiple departments, a hierarchical topology, subnetting, routing, centralized services, and interdepartmental connectivity.

---

## 📁 Project Overview

This simulated college network includes the following departments:

- 🖥️ **IT Department**
- 🧪 **Labs (Lab1 & Lab2)**
- 🗂️ **Student Records**
- 🏢 **Admission Office**
- 🛠️ **Admin Office (Hosting DNS & Web Server)**

Each department is placed on a separate subnet, connected via switches and routers, forming a secure and segmented infrastructure.

---

## 🧱 Network Architecture

- **Routers:** 5 core routers for inter-departmental routing
- **Switches:** Layer 2 switches for end-device connectivity
- **PCs:** Simulated endpoints for users across departments
- **Servers:**
  - **DNS Server** (IP: `192.168.5.2`)
  - **Web Server** (IP: `192.168.5.2`)
- **Subnetting:** Each department uses its own 192.168.x.x/24 subnet
- **Routing Protocol:** Static routing (can be upgraded to RIP/OSPF)
- **End-to-End Connectivity:** Verified using `ping` and `web` simulation

---

## 🌐 Features

- ✔️ Simulated intra- and inter-department connectivity
- ✔️ Fully segmented subnets
- ✔️ Centralized services in Admin Office
- ✔️ Hierarchical topology with logical cable management
- ✔️ Realistic IP addressing scheme
- ✔️ Ready for testing DNS resolution and web traffic

---

## 📦 Files Included

- `college-network.png` - Image of the network
- `college-network.pkt` – Cisco Packet Tracer project file  
- `README.md` – You’re reading it!

---

## 🚀 How to Run

1. Download and install [Cisco Packet Tracer](https://www.netacad.com/courses/packet-tracer).
2. Open `college-network.pkt` in Packet Tracer.
3. Use the **Simulation Mode** to:
   - Ping across departments
   - Test DNS resolution
   - Access the web server from any PC

4. **Note** - The DNS is not configured for all the computers, so update DNS in config settings and search 'pesu' in the web browser
---

## 🛠️ Possible Extensions

- Add VLANs and inter-VLAN routing
- Implement dynamic routing protocols (RIP, OSPF)
- Set up wireless APs for mobility
- Configure DHCP server
- Introduce ACLs and firewall rules for access control

---

## 📚 Author

- **Vikramaditya Sharma** – _Student / Networking Enthusiast_

---

## 📝 License

This project is open-source and free to use for educational purposes.  
Feel free to fork and enhance!

