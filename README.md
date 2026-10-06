# 🌐 Network Security & ACL Lab

## 📌 Project Overview

This project demonstrates the design and implementation of a segmented network environment using Cisco Packet Tracer.

The lab was designed to separate HR and Finance network resources while using Access Control Lists (ACLs) to control communication between network segments and restrict access to sensitive resources.

The project provided hands-on experience with network configuration, routing, DHCP/DNS services, connectivity testing, and the application of security controls to enforce access requirements.

---

## 🎯 Objectives

The objectives of this project were to:

- Design a functional network topology in Cisco Packet Tracer
- Configure separate network segments for HR and Finance
- Configure IP addressing and network connectivity
- Implement DHCP and DNS services
- Configure routing between network segments
- Apply ACLs to control access between departments
- Restrict access to protected network resources
- Test permitted and denied traffic
- Develop practical network-security and troubleshooting skills

---

## 🛠️ Technologies & Skills

| Technology / Skill | Purpose |
|---|---|
| Cisco Packet Tracer | Network simulation and configuration |
| Cisco Router | Routing and ACL implementation |
| Cisco Switch | Endpoint connectivity |
| DHCP | Automatic IP address assignment |
| DNS | Name resolution |
| Extended ACLs | Traffic filtering and access control |
| TCP/IP | Network communication |
| Network Segmentation | Separation of departmental resources |

---

## 🏗️ Network Architecture

The simulated environment consisted of separate HR and Finance network segments connected through Cisco networking infrastructure.

A server was included to provide network services and represent a protected resource within the environment.

ACL rules were implemented to control which network segment could access specific resources.

---

## 🔐 Access Control Implementation

Extended Access Control Lists were used to enforce network-security requirements.

The ACL configuration was designed to:

- Permit authorised HR traffic to protected resources
- Restrict unauthorised Finance access where required
- Control traffic based on source, destination and service
- Demonstrate the principle of least privilege
- Reduce unnecessary communication between network segments

---

## 🧪 Testing & Validation

Connectivity and access-control tests were performed after configuration.

Testing included:

- Verifying endpoint IP configuration
- Testing connectivity between network devices
- Confirming DHCP address assignment
- Verifying DNS functionality
- Testing permitted traffic
- Testing traffic expected to be denied by the ACL
- Confirming that ACL behaviour matched the intended security policy

---

## 🔎 Security Significance

Network segmentation and ACLs can reduce unnecessary access to sensitive systems and limit communication between different areas of an organisation.

This lab demonstrates how network-level security controls can be used to enforce access requirements and support the principle of least privilege.

---

## 🧠 Key Takeaways

This project strengthened my understanding of:

- Network segmentation
- Cisco router and switch configuration
- IP addressing and routing
- DHCP and DNS services
- Extended Access Control Lists
- Traffic filtering
- Connectivity testing
- Network troubleshooting
- Least-privilege access control

---

## 📸 Project Evidence

Screenshots demonstrating the network topology, device configuration, ACL implementation and connectivity testing will be documented below.

---

## ⚠️ Disclaimer

This project was completed in a controlled Cisco Packet Tracer lab environment for cybersecurity training and educational purposes.


---

## 📸 Project Evidence

The following screenshots document the configuration and testing performed during the lab.

### 1. Network Topology
The completed Cisco Packet Tracer topology showing the segmented HR and Finance network environment.

![Network Topology](images/01-network-topology%5B1%5D.png)

### 2. DHCP Configuration
DHCP configuration used to automatically assign IP addressing information to network hosts.

![DHCP Configuration](images/02-dhcp-configuration%5B1%5D.png)

### 3. DNS Configuration
DNS service configuration used within the simulated network environment.

![DNS Configuration](images/03-dns-configuration%5B1%5D.png)

### 4. Web Server Configuration
Configuration of the internal web server used as a protected network resource during access-control testing.

![Web Server Configuration](images/04-web-server-configuration%5B1%5D.png)

### 5. HR — Permitted Access
Successful connectivity test demonstrating that authorised HR traffic can reach the protected resource.

![HR Access Successful](images/05-hr-access-success%5B1%5D.png)

### 6. Finance — Access Blocked
Connectivity test demonstrating that Finance traffic is denied access to the protected resource in accordance with the ACL policy.

![Finance Access Blocked](images/06-finance-access-blocked%5B1%5D.png)

---

## ✅ Project Outcome

This lab demonstrated how network segmentation and Access Control Lists can be used to enforce least-privilege access between departments. The testing confirmed that authorised HR traffic could reach the protected resource while Finance traffic was restricted according to the configured ACL policy.
