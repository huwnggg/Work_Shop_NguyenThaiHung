---
title: "Week 7 Worklog"
date: 2024-01-01
weight: 1
chapter: false
pre: " <b> 1.7. </b> "
---

### Week 7 Objectives:
* Gain an overview of hybrid networking (VPC, Transit Gateway) and hybrid DNS management (Route 53 Resolver).
* Prepare hybrid lab environments: create custom VPC, Key Pairs, deploy CloudFormation Templates, and configure Security Groups.
* Deploy and configure Microsoft Active Directory (AD) on EC2 to simulate an On-premise DNS Server.
* Establish secure Hybrid DNS configurations utilizing Route 53 Resolver Inbound/Outbound Endpoints and custom Resolver Rules.
* Build multi-network routing topologies using Transit Gateway as a central hub connecting Cisco CSR Routers and Site-to-Site VPN with ECMP.
* Connect isolated VPCs directly via VPC Peering and establish secure service links via VPC Endpoints (AWS PrivateLink).
* Deploy Transit Gateway Network Manager and Network Insights for unified monitoring and traffic path debugging.
* Execute total resource cleanup tasks across both labs to optimize cloud usage budgets.

### Tasks to be carried out this week:
| Day | Task | Start Date | Completion Date | Reference Material |
| --- | --- | --- | --- | --- |
| Friday | **Day 1: Overview and Environment Preparation** <br>- Study the theory of VPC, Transit Gateway, and Route 53 Resolver architectures. <br>- Provision VPC resources, create Key Pairs, execute CloudFormation templates, and configure Security Groups for both labs. | 29/05/2026 | 29/05/2026 | [Networking Prep](https://000092.awsstudygroup.com/2-prerequiste/) <br>[DNS Prep](https://000010.awsstudygroup.com/2-prerequiste/) |
| Sat - Sun | **Day 2: VPC Deep Dive & Active Directory Setup** <br>- Dive deep into VPC components (Subnets, Route Tables, Internet Gateways, NAT Gateways). <br>- Access the environment via RDGW and configure Microsoft Active Directory (AD) on EC2. | 30/05/2026 | 31/05/2026 | [VPC Deep Dive](https://000092.awsstudygroup.com/3-vpcs/) <br>[RDGW Connection](https://000010.awsstudygroup.com/3-connecttordgw/) <br>[Setup Active Directory](https://000010.awsstudygroup.com/4-setupad/) |
| Monday | **Day 3: Hybrid DNS Resolution using Route 53 Resolver** <br>- Enforce Hybrid DNS patterns: configure Inbound and Outbound Endpoints and define Resolver Rules to route traffic between AWS and local zones. | 01/06/2026 | 01/06/2026 | [Setup Hybrid DNS](https://000010.awsstudygroup.com/5-setuphyriddns/) |
| Tuesday | **Day 4: Multi-Network Routing via Transit Gateway & VPN** <br>- Launch Transit Gateway as a centralized hub connecting local and cloud resources. <br>- Establish VPN links with Cisco CSR Routers and activate ECMP multipathing. | 02/06/2026 | 02/06/2026 | [Transit GW & VPN](https://000092.awsstudygroup.com/4-transitgatewayandvpn/) |
| Wednesday | **Day 5: VPC Peering, DNS Endpoints & AWS PrivateLink** <br>- Connect direct VPC networks using VPC Peering. <br>- Set up internal Route 53 zones, configure VPC Endpoints (AWS PrivateLink), and define endpoint services. | 03/06/2026 | 03/06/2026 | [Route 53 Internal](https://000092.awsstudygroup.com/5-route53/) <br>[VPC Endpoints](https://000092.awsstudygroup.com/6-vpcendpointaws/) <br>[VPC Peering](https://000092.awsstudygroup.com/8-vpcpeering/) |
| Thursday | **Day 6: Central Network Governance (Network Manager)** <br>- Set up Transit Gateway Network Manager to map out connected sites. <br>- Use AWS Network Insights to analyze routing and firewall rule paths. | 04/06/2026 | 04/06/2026 | [Network Manager](https://000092.awsstudygroup.com/9-transitgatewaynetworkmanager/) |
| Friday | **Day 7: Resource Cleanup** <br>- Clean up and tear down all provisioned hybrid network structures (VPC, Transit Gateway, VPN, Route 53 Resolver) to avoid charge leakages. | 05/06/2026 | 05/06/2026 | [DNS Cleanup](https://000010.awsstudygroup.com/6-cleanup/) <br>[Networking Cleanup](https://000092.awsstudygroup.com/10-cleanup/) |

### Week 7 Achievements:
* Understood Hybrid Cloud networking mechanics, including cross-premise DNS query resolution via Route 53 Resolver.
* Successfully built a simulated local network with Active Directory running on an EC2 instance.
* Provisioned Transit Gateway hub architectures to handle massive VPC routing, configuring VPN trunks with active ECMP load sharing.
* Enforced private data boundaries using secure VPC Peering and VPC Endpoints powered by AWS PrivateLink.
* Mastered Transit Gateway Network Manager and Network Insights diagnostics to locate routing faults.
* Completed a thorough teardown of all S3 endpoints, Route 53 Resolver Outbound links, Transit Gateways, and VPN instances.
