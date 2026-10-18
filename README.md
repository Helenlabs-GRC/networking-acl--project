# Departmental Network Design and Access Control Using Cisco Packet Tracer

## Project Overview

This networking assignment demonstrates the design and testing of a departmental network in **Cisco Packet Tracer**. Three departments—**Sales, IT, and HR**—are connected through a central router and switches. The project also demonstrates network access control using an **Access Control List (ACL)** and verifies connectivity through ping tests and HTTP access.

## Project Objectives

- Build a network topology connecting Sales, IT, and HR.
- Configure IP addressing for departmental devices.
- Test communication between HR and IT.
- Demonstrate restricted communication from Sales to IT.
- Configure an ACL on the router.
- Verify that Sales can access a server's HTTP service.

## Tools and Technologies

- Cisco Packet Tracer
- Routers and switches
- IPv4 addressing
- Access Control Lists (ACLs)
- ICMP (ping) connectivity tests
- HTTP service

## Network Topology

The topology connects three departments through a central router, with switches providing connectivity to the devices in each department.

<img width="940" height="432" alt="image" src="https://github.com/user-attachments/assets/2219e6ab-f1b3-4f52-a83f-85d66f059b7d" />

## Implementation and Evidence

### 1. IP Address Configuration

IP addressing is configured on departmental devices. The assignment includes the following screenshot of a PC's IP configuration.

<img width="940" height="521" alt="image" src="https://github.com/user-attachments/assets/cdabf1ed-98d0-4e4a-bafe-26964c8f944f" />


### 2. Successful Connectivity: HR to IT

A ping test from an HR PC to an IT PC demonstrates successful connectivity between these departments.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/5868930e-dfe6-4816-b032-2bee5adf1d51" />


### 3. Restricted Connectivity: Sales to IT

A ping test from a Sales PC to an IT PC fails, demonstrating the intended access restriction.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/fd645c2b-64e7-4aad-8829-c5695220a553" />


### 4. Router ACL Configuration

An ACL is configured through the router command-line interface to implement network access restrictions. The configuration evidence is shown below.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/5d43e147-af95-402f-898d-1fc039c9459f" />


### 5. Sales Access to the Web Server

Despite the restricted Sales-to-IT ping connectivity, the Sales department can access the server's HTTP service, as shown in the browser screenshot.

<img width="940" height="529" alt="image" src="https://github.com/user-attachments/assets/aa6c8535-5ebe-41b9-899b-1e75deb37687" />

## Test Results

| Test | Observed result |
| --- | --- |
| HR PC → IT PC (ping) | Successful |
| Sales PC → IT PC (ping) | Failed / restricted |
| Router ACL | Configuration shown in router CLI |
| Sales PC → server (HTTP) | Accessible |

## Key Learning Outcomes

This assignment illustrates how network segmentation and router ACLs can help control traffic between departments while allowing access to required services. It also demonstrates practical verification using ping tests and a web browser.

## Project Files

- `README.md` — project documentation
- `screenshots/` — six screenshots taken from the assignment
## 🎓 Skills Learned

Through this networking project, I gained practical experience in:

- **Network Design and Topology:** Designing and connecting three departments (Sales, IT, and HR) using routers and switches in Cisco Packet Tracer.
- **IP Address Configuration:** Assigning static IP addresses, subnet masks, and default gateways to network devices.
- **Network Connectivity Testing:** Using the `ping` command to test communication between devices and verify network connectivity.
- **Access Control Lists (ACLs):** Configuring ACLs on a Cisco router to restrict unauthorized communication between departments.
- **Network Security:** Implementing access restrictions to prevent Sales department devices from communicating with IT department devices.
- **Router CLI Configuration:** Using Cisco IOS command-line interface commands to configure and verify network access rules.
- **HTTP Service Testing:** Verifying that Sales department devices can access a web server despite network access restrictions.
- **Network Troubleshooting:** Identifying and testing successful and blocked network connections.

### Key Takeaway

This project strengthened my understanding of network configuration, access control, and network security. I gained hands-on experience using Cisco Packet Tracer to design a departmental network, implement ACL rules, and verify that network traffic is permitted or restricted according to security requirements.
## Author

**Helen Chioma Ifionu**  
Networking Assignment  
**Date:** 7 September 2026

---

*This README documents the results shown in the submitted networking assignment. Exact router commands and full addressing tables are not transcribed because they are not reliably readable from the supplied screenshots.*
