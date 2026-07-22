# Multi-Site Campus Network Lab

Design and implementation of a multi-site enterprise network with full routing, services, and access control.

## Project Scope

Simulated a realistic multi-campus network connecting several sites with different needs. Each site has its own subnets, services, and security policies, all interconnected through dynamic routing.

## Protocols and Technologies

| Protocol/Service | Implementation |
|-----------------|---------------|
| OSPF | Dynamic routing between sites, area design |
| DHCP Server | Centralized IP allocation per VLAN |
| DNS Server | Internal name resolution across sites |
| ACLs | Traffic filtering between departments |
| VLANs | Logical segmentation per department |
| Inter-VLAN Routing | Router-on-a-stick / L3 switch |
| NAT/PAT | Internet access for internal hosts |

## Network Design

- Multiple campus sites (different geographic locations)
- Each site: separate VLANs for admin, students, servers
- OSPF backbone connecting all sites
- Centralized services (DNS, DHCP) with redundancy considerations
- ACLs restricting inter-departmental access where needed

## Tools

- Cisco Packet Tracer (simulation)
- Cisco IOS (router/switch configuration)

## Documentation

Full report with topology diagrams, IP addressing plans, and all configurations: `Rapport_Projet_Semestre3_Reseaux.pdf` (French).

## What I Learned

- Designing scalable network architectures from requirements
- OSPF area planning and route summarization
- Combining multiple protocols into a coherent design
- Troubleshooting connectivity across complex topologies
- Writing clear network documentation

## Context

Semester 3 final project at KBU (Knowbridge University Institute). This was a team project that required designing the full topology from business requirements, then implementing and testing every component.

---

Timothe ALOGNON | Cybersecurity Student | KBU, Togo
