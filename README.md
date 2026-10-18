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

![Completed network topology](screenshots/network-topology.png)

## Implementation and Evidence

### 1. IP Address Configuration

IP addressing is configured on departmental devices. The assignment includes the following screenshot of a PC's IP configuration.

![PC IP configuration](screenshots/ip-configuration.png)

### 2. Successful Connectivity: HR to IT

A ping test from an HR PC to an IT PC demonstrates successful connectivity between these departments.

![Successful ping from HR to IT](screenshots/successful-hr-to-it-ping.png)

### 3. Restricted Connectivity: Sales to IT

A ping test from a Sales PC to an IT PC fails, demonstrating the intended access restriction.

![Failed ping from Sales to IT](screenshots/blocked-sales-to-it-ping.png)

### 4. Router ACL Configuration

An ACL is configured through the router command-line interface to implement network access restrictions. The configuration evidence is shown below.

![ACL configuration in router CLI](screenshots/router-acl-configuration.png)

### 5. Sales Access to the Web Server

Despite the restricted Sales-to-IT ping connectivity, the Sales department can access the server's HTTP service, as shown in the browser screenshot.

![Sales accessing the HTTP server](screenshots/sales-http-access.png)

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

## Author

**Helen Chioma Ifionu**  
Networking Assignment  
**Date:** 7 September 2026

---

*This README documents the results shown in the submitted networking assignment. Exact router commands and full addressing tables are not transcribed because they are not reliably readable from the supplied screenshots.*
