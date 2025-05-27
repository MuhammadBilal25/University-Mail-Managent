FCAI Computer Network Design - Cisco Packet Tracer Project


**📘 Project Overview:**
This project is a computer network simulation built in Cisco Packet Tracer for the Faculty of Computing and AI (FCAI). The design simulates a departmental structure with three academic departments, each equipped with labs, faculty offices, and classrooms. The network includes DNS and Mail servers, as well as full routing (static and dynamic), DHCP configuration, and subnetting.

Developed by Muhammad Bilal
Roll No: 232442
Degree Program: BS Computer Science  (Evening, Fall 2023, Section C)


**🏗️ Network Design:**
The design follows a star topology, where:
Each department includes:
1 Lab
2 Faculty Offices
2 Classrooms
Each unit is connected through switches to a dedicated department router
All department routers connect to a Main Router in the Server Room
The Server Room contains:
DNS Server
Mail Server


**📡 IP Addressing & Subnetting:**
Each department is divided into three subnetworks, and an additional subnetwork is reserved for future use:

Department 1: 192.168.1.0/26, 192.168.1.64/26, 192.168.1.128/26

Department 2: 192.168.2.0/26, 192.168.2.64/26, 192.168.2.128/26

Department 3: 192.168.3.0/26, 192.168.3.64/26, 192.168.3.128/26


**🔧 Configuration Details:**

✅ DHCP Configuration:
Routers in each department act as DHCP servers
A DHCP pool is configured for each subnetwork
PCs are set to receive IP addresses dynamically


**🌐 DNS & Mail Server:**

DNS Server: Resolves PC names (e.g., pc0, pc1, … pc41) to IP addresses
Mail Server: Configured with the domain mail.com to handle email traffic

All PCs are configured with email accounts


**🔀 Routing:**
Static Routing: Configured from the Main Router to each department
Dynamic Routing: Implemented using RIP (Routing Information Protocol) to allow inter-department communication


**📸 Screenshots:**
Includes:
Network Topology Views
DHCP Pool Configuration
DNS and Mail Server Setup
RIP and Static Routing Tables
Successful PING Results and Mail Tests

**💾 Files Included:**
projectTopology.University.pkt – Cisco Packet Tracer file (you should include this in the repo)
Group Alpha CN Project Documentation .pdf – Full project documentation
University Mail Managment.pptx – Presentation slides


**📌 How to Use:**
Open the .pkt file in Cisco Packet Tracer
Explore the topology and configurations
Test routing, DNS resolution, and email functionality
Modify and expand the network as desired


**📫 Contact**
For any questions or feedback, feel free to reach out via GitHub or contact Muhammad Bilal directly.
