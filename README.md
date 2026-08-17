# Awesome Computer Networking Resources with stars

An [awesome list](https://github.com/sindresorhus/awesome) ⭐ 496,614 | 🐛 100 | 📅 2026-06-30 of resources to design, implement and operate computer networks.

# Contents

* [Network Design Resources](#network-design-resources)
* [Network Implementation](#network-implementation)
  * [Routing](#routing)
  * [Switching](#switching)
  * [VPN](#vpn)
  * [Network Services](#network-services)
  * [Network Simulators and Traffic Generators](#network-simulators-and-traffic-generators)
  * [Network Connectivity](#network-connectivity)
* [Network Operations](#network-operations)
  * [Network Change Management](#network-change-management)
  * [Network Automation](#network-automation)
  * [Network Monitoring](#network-monitoring)
  * [Security Monitoring](#security-monitoring)
  * [Network Inventory](#network-inventory)
  * [Networking Labs](#networking-labs)
* [Related resources](#related-resources)
  * [DevNet Tools](#devnet-tools)
  * [DevNet Monitoring](#devnet-monitoring)
  * [DevNet Knowledgebase](#devnet-knowledgebase)
  * [DevNet Inventory](#devnet-inventory)
  * [Knowledge Resources](#knowledge-resources)

# Network Design Resources

* [Arista Design and Deployment Guides](https://www.arista.com/en/solutions/design-guides)
* [Cisco Design Zone](https://www.cisco.com/c/en/us/solutions/design-zone.html#~stickynav=1)
* [Cumulus Networks Validated Design Guides](https://cumulusnetworks.com/learn/web-scale-networking-resources/?validated-design-guides)
* [Juniper Solution Center](https://www.juniper.net/documentation/en_US/release-independent/solutions/information-products/pathway-pages/solutions/index.html)

# Network Implementation

## Routing

* [Free Range Routing](https://frrouting.org/) - IP routing protocol suite for Linux and Unix platforms which
  includes protocol daemons for BGP, IS-IS, LDP, OSPF, PIM, and RIP.
* [VyOS](https://vyos.io/) - Open source network operating system that can be installed on physical hardware or a virtual machine on your own server, or a cloud platform.

### SD-WAN

* [Silver Peak](https://www.silver-peak.com/) - SD-WAN Solution(Commercial).

## Switching

* [snabb](https://github.com/snabbco/snabb) ⭐ 3,034 | 🐛 15 | 🌐 Lua | 📅 2026-07-30 - Snabb (formerly "Snabb Switch") is a simple and fast packet networking toolkit.

## VPN

* [Firezone](https://github.com/firezone/firezone) ⭐ 9,035 | 🐛 410 | 🌐 Elixir | 📅 2026-08-17 - Open-source VPN server and egress firewall for Linux built on WireGuard. Firezone is easy to set up (all dependencies are bundled thanks to Chef Omnibus), secure, performant, and self hostable.
* [Pilot Protocol](https://github.com/TeoSlayer/pilotprotocol) ⭐ 133 | 🐛 5 | 🌐 Go | 📅 2026-08-16 - Overlay network stack for AI agents with virtual addresses, encrypted UDP tunnels (AES-256-GCM), NAT traversal, and mutual trust. Written in Go with zero dependencies.
* [PiVPN](https://www.pivpn.io/) - Simplest OpenVPN setup and configuration, designed for Raspberry Pi.

## Network Services

* [Pi-Hole](https://pi-hole.net/) - Network-wide ad blocking via your own Linux hardware.
* [PortNox](https://www.portnox.com/pricing/) - Network Access Control as a Service (Commercial)
* [Bunny.net](https://bunny.net/) - Global Content Delivery Platform

## Network Simulators and Traffic Generators

* [Arkime](https://github.com/arkime/arkime) ⭐ 7,447 | 🐛 35 | 🌐 C | 📅 2026-08-16 - Arkime augments your current security infrastructure to store and index network traffic in standard PCAP format, providing fast, indexed access.
* [snabb](https://github.com/snabbco/snabb) ⭐ 3,034 | 🐛 15 | 🌐 Lua | 📅 2026-07-30 - Snabb (formerly "Snabb Switch") is a simple and fast packet networking toolkit.
* [vqfx10k-vagrant](https://github.com/juniper/vqfx10k-vagrant) ⭐ 137 | 🐛 22 | 🌐 HTML | 📅 2020-11-21 - Vagrant files to bring up Juniper virtual QFX instances.
* [Multi-Generator](https://github.com/USNavalResearchLaboratory/mgen) ⭐ 106 | 🐛 10 | 🌐 C++ | 📅 2025-10-02 - Open source software that provides the ability to perform IP network performance tests and measurements using TCP and UDP/IP traffic.
* [Packet Communication Investigator](https://github.com/michoo/pci) ⚠️ Archived - import network traffic into a graphtool to analyse packet interactions between machines and network.
* [Network-Conditions-Emulator](https://github.com/marty90/Network-Conditions-Emulator) ⭐ 20 | 🐛 1 | 🌐 Shell | 📅 2021-10-27 - Artificially limit uplink and downlink bandwidth, delay and loss rate on selected interfaces.
* [GNS3](https://www.gns3.com/) - Network software emulator that allows the combination of virtual and real devices, used to simulate complex networks.
* [Mininet](http://mininet.org/) - Instant Virtual Network on your Laptop.
* [WANem](http://wanem.sourceforge.net/) - Wide Area Network Emulator.
* [Ostinato](https://ostinato.org/) - Packet crafter, network traffic generator and analyzer with a friendly GUI.
* [SIPp](http://sipp.sourceforge.net/index.html) - Free Open Source test tool / traffic generator for the SIP protocol.
* [StarTrinity SIP Tester™](https://startrinity.com/VoIP/SipTester/SipTester.aspx) - VoIP monitoring and testing tool, VoIP recorder.
* [SafePcap](https://omnipacket.com/safepcap) - GDPR and NISTIR 8053 Compliance for your Pcap files.
* [pyNTM](https://pyntm.readthedocs.io/en/latest/index.html) - a network traffic modeler written in python 3.

## Network Connectivity

* [Packetfabric](https://packetfabric.com/) - Network as a service provider (commercial)
* [Prosimo](https://prosimo.io/) - Autonomous Multi-Cloud Network (commercial)
* [Subtelforum Online Map](https://subtelforum.com/online-map/) - Submarine cables map
* [Megaport](https://www.megaport.com/) - Network as a Service (NaaS) platform (commercial)

# Network Operations

## Network Change Management

* [Oxidized](https://github.com/ytti/oxidized) ⭐ 3,498 | 🐛 54 | 🌐 Ruby | 📅 2026-08-15 - Network device configuration backup tool. It's a [RANCID](https://www.shrubbery.net/rancid/) replacement.
* [Batfish](https://github.com/batfish/batfish) ⭐ 1,453 | 🐛 281 | 🌐 Java | 📅 2026-08-17 - Network configuration analysis tool that can find bugs and guarantee the correctness of (planned or current) network configurations.
* [Jazigo](https://github.com/udhos/jazigo) ⭐ 230 | 🐛 1 | 🌐 Go | 📅 2023-11-02 - Jazigo is a tool written in Go for retrieving configuration for multiple devices, similar to rancid, fetchconfig, oxidized, Sweet.
* [sweet](https://github.com/AppliedTrust/sweet) ⚠️ Archived - Network device configuration backups and change alerts for the 21st century - inspired by RANCID.
* [stockpiler](https://github.com/lykinsbd/stockpiler) ⭐ 43 | 🐛 10 | 🌐 Python | 📅 2020-05-15 - Stockpiler gathers network device configurations and stores them in a local Git repository.
* [fetchconfig](https://github.com/udhos/fetchconfig) ⭐ 15 | 🐛 1 | 🌐 Perl | 📅 2017-02-01 - fetchconfig is a Perl script for retrieving configuration of
  multiple devices.
* [Netshot](http://www.netfishers.onl/netshot) - Network configuration and compliance management software.
* [Jerikan](https://github.com/jerikan-network) - a configuration management system for network teams

## Network Automation

* [Ansible](https://github.com/ansible/ansible) ⭐ 70,334 | 🐛 830 | 🌐 Python | 📅 2026-08-11 - IT automation platform that makes your applications and systems easier to deploy by using SSH, with no agents to install on remote systems.
* [AWX](https://github.com/ansible/awx) ⭐ 15,525 | 🐛 1,870 | 🌐 Python | 📅 2026-08-17 - the upstream project for Tower / AAP2, a commercial derivative of AWX.
* [netmiko](https://github.com/ktbyers/netmiko) ⭐ 4,246 | 🐛 61 | 🌐 Python | 📅 2026-07-24 - Multi-vendor library to simplify Paramiko SSH connections to network devices.
* [nornir](https://github.com/nornir-automation/nornir) ⭐ 1,611 | 🐛 50 | 🌐 Python | 📅 2026-08-12 - Pluggable multi-threaded framework with inventory management to help operate collections of devices.
* [ntc-templates](https://github.com/networktocode/ntc-templates) ⭐ 1,287 | 🐛 35 | 🌐 Python | 📅 2026-07-27 - TextFSM templates for parsing show commands of network devices.
* [TextFSM](https://github.com/google/textfsm) ⭐ 1,246 | 🐛 16 | 🌐 Python | 📅 2025-04-17 -  Python module for parsing semi-structured text into Python tables.
* [trigger](https://github.com/trigger/trigger) ⭐ 559 | 🐛 66 | 🌐 Python | 📅 2026-08-09 - Robust network automation toolkit written in Python that was designed for interfacing with network devices.
* [TTP](https://github.com/dmulyalin/ttp) ⭐ 393 | 🐛 43 | 🌐 Python | 📅 2026-03-24 - TTP is a Python library for semi-structured text parsing using templates.
* [CNaaS-NMS](https://github.com/SUNET/cnaas-nms) ⭐ 90 | 🐛 36 | 🌐 Python | 📅 2026-08-13 - Campus Network-as-a-Service - Network Management System. Software to automate management of a campus network (LAN).
* [gotextfsm](https://github.com/sirikothe/gotextfsm) ⭐ 70 | 🐛 1 | 🌐 Go | 📅 2026-04-18 - Port of Google's TextFSM library from Python to Go/Golang.
* [GitNOps](https://github.com/mcgonagle/GitNops) ⭐ 27 | 🐛 1 | 🌐 HCL | 📅 2026-05-31 - GitNops is an operational framework that takes DevOps best practices used for application development such as version control, collaboration, compliance, and CI/CD, and applies them to network automation.
* [Napalm](https://napalm-automation.net/) - Vendor neutral, cross-platform open source project that provides a unified API to network devices.
* [pyats](https://developer.cisco.com/pyats/) - pyATS enable network engineers to perform stateful validation of their device operational status.
* [itential.com](https://www.itential.com/) - Low-Code Automation for Physical, Virtual, and Cloud Networks (commercial).
* [Unimus](https://unimus.net/) Unimus makes Network Automation and Configuration Management easy (commercial).
* [Blackbox](https://backbox.com/) - Network automation for the hybrid multi-cloud era (commercial).
* [Nephio](https://nephio.org/) - Nephio’s goal is to deliver carrier-grade, simple, open, Kubernetes-based cloud native intent automation and common automation templates.

## AI for Networking

* [DefenseClaw](https://github.com/cisco-ai-defense/defenseclaw) ⭐ 819 | 🐛 42 | 🌐 Go | 📅 2026-08-16 - DefenseClaw is the enterprise governance layer for OpenClaw
* [NetClaw](https://github.com/automateyournetwork/netclaw) ⭐ 635 | 🐛 0 | 🌐 Python | 📅 2026-08-16 - A CCIE-level AI network engineering coworker, built on OpenClaw
* [Cisco LLM Security Leaderboard](https://leaderboard.aidefense.cisco.com/methodology) - Comprehensive model safety and security rankings, including single-turn score, multi-turn score, and detailed metrics.

## Network Monitoring

* [Elastiflow](https://github.com/robcowart/elastiflow) ⚠️ Archived - Netflow collector and reporting.
* [vFlow](https://github.com/EdgeCast/vflow) ⭐ 1,155 | 🐛 71 | 🌐 Go | 📅 2024-08-22 - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector (written in pure Golang).
* [BGPAlerter](https://github.com/nttgin/BGPalerter) ⭐ 1,008 | 🐛 11 | 🌐 JavaScript | 📅 2026-07-28 - Self-configuring BGP monitoring tool
* [goFlow](https://github.com/cloudflare/goflow) ⚠️ Archived - a NetFlow/IPFIX/sFlow collector in Go.
* [Vaping](https://github.com/20c/vaping) ⭐ 538 | 🐛 48 | 🌐 Python | 📅 2024-12-20 - vaping is a healthy alternative to smokeping.
* [ToDD](https://github.com/toddproject/todd) ⚠️ Archived - Distributed, testing-on-demand system focused on testing network related conditions.
* [xpresso](https://github.com/CiscoTestAutomation/xpresso) ⭐ 89 | 🐛 5 | 🌐 Shell | 📅 2022-03-09 - the standard pyATS UI dashboard
* [UDPing](https://github.com/yahoo/UDPing) ⭐ 85 | 🐛 4 | 🌐 C++ | 📅 2026-08-12 - Measure latency and packet loss across a link.
* [OSPF Watcher](https://github.com/Vadims06/ospfwatcher) ⭐ 84 | 🐛 8 | 🌐 Python | 📅 2026-06-23 - Monitors OSPF topology changes and LSA updates in real time. Provides event visualization and historical tracking via Topolograph or centralized logging through ELK.
* [rkik](https://github.com/aguacero7/rkik) ⭐ 58 | 🐛 3 | 🌐 Rust | 📅 2026-07-10 - Light, easy-to-use monitoring tool for NTP servers
* [IS-IS Watcher](https://github.com/Vadims06/isiswatcher) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2026-06-21 - Monitors IS-IS topology changes and PDU updates in real time. Provides event visualization and historical tracking via Topolograph or centralized logging through ELK.
* [NexusFlowMeter](https://github.com/Collgamer0008/NexusFlowMeter) ⭐ 2 | 🐛 0 | 🌐 Python | 📅 2025-10-19 - high-performance network flow analysis tool that converts packet capture (PCAP) files into comprehensive flow-based insights, includes various productibity features.
* [perfSONAR](https://www.perfsonar.net) - Network measurement toolkit designed to provide federated coverage of paths, and help to establish end-to-end usage expectations.
* [veryflow](https://www.veriflow.net/) - Continuous network verification system.
* [Forward Networks](https://www.forwardnetworks.com/) - Network Behavior Analysis (Commercial).
* [pmacct](http://www.pmacct.net/) - Small set of multi-purpose passive network monitoring tools, including Netflow or IPFIX generation.
* [LibreNMS](https://www.librenms.org/) - Network monitoring system that supports automatic discovery, alerting, distributed polling and others.
* [Observium](https://observium.org/) - Low-maintenance auto-discovering network monitoring platform.

## Security Monitoring

* [PyREBox](https://github.com/Cisco-Talos/pyrebox) ⚠️ Archived - Python scriptable Reverse Engineering Sandbox, a Virtual Machine instrumentation and inspection framework based on QEMU.
* [Malcolm](https://github.com/idaholab/Malcolm) ⭐ 478 | 🐛 4 | 🌐 Python | 📅 2026-08-09 - Malcolm is a powerful, easily deployable network traffic analysis tool suite for full packet capture artifacts (PCAP files) and Zeek logs.
* [cPacket](https://www.cpacket.com) - Performance monitoring solutions that deliver real-time analysis and coverage (Commercial).
* [Proxmox Mail Gateway](https://www.proxmox.com/en/proxmox-mail-gateway) - Open-source email security solution helping you to protect your mail server against all email threats the moment they emerge.
* [FastNetMon](https://fastnetmon.com/) - DDoS detection tool (Open Source or Commercial).
* [Canary](https://canary.tools/) - Honeypot solution (commercial).
* [CanaryTokens](https://canarytokens.org/generate) - Free honeytoken.
* [Zeek](https://zeek.org/) - Zeek is an open source network security monitoring tool.
  * [zeek2es](https://github.com/corelight/zeek2es) ⭐ 40 | 🐛 0 | 🌐 Python | 📅 2022-08-18 - A Zeek log to Elastic/OpenSearch log converter.
* [DrKeithJones.com](https://drkeithjones.com) - Keith Jones' blog on cyber security and security monitoring.

## Network Inventory

* [netbox](https://github.com/digitalocean/netbox) ⭐ 21,318 | 🐛 211 | 🌐 Python | 📅 2026-08-16 - IP address management (IPAM) and data center infrastructure management (DCIM) tool.
* [nautobot](https://github.com/nautobot/nautobot) ⭐ 1,576 | 🐛 1,000 | 🌐 Python | 📅 2026-08-16 - Network Source of Truth & Network Automation Platform.
* [drawthe.net](https://github.com/cidrblock/drawthe.net) ⭐ 1,182 | 🐛 18 | 🌐 JavaScript | 📅 2024-03-19 - Draws network diagrams dynamically from a text file describing the placement, layout and icons.
* [infrahub](https://github.com/opsmill/infrahub) ⭐ 502 | 🐛 482 | 🌐 Python | 📅 2026-08-17 -  Infrahub is a graph-based data management platform with built-in version control, CI workflows, peer review, and API access. It’s purpose-built to power reliable infrastructure automation at scale.
* [nsot](https://github.com/dropbox/nsot) ⭐ 407 | 🐛 64 | 🌐 Python | 📅 2024-02-13 - Network Source of Truth is an open source IPAM and network inventory database.
* [phpipam](https://phpipam.net/) - Open-source web IP address management application (IPAM).
* [ipfabric](https://ipfabric.io/product/network-mapping) - Network Topology Mapping & Visualization (Commercial).

## Networking Labs

* [containerlab](https://github.com/srl-labs/containerlab) ⭐ 2,741 | 🐛 68 | 🌐 Go | 📅 2026-08-16 - Container-based networking labs, though support has been added to integrate Virtual Machines (VMs).
* [netlab](https://github.com/ipspace/netlab) ⭐ 723 | 🐛 27 | 🌐 Python | 📅 2026-08-16 - netlab is bringing infrastructure-as-code concepts to networking labs. You'll describe your high-level network topology and routing design in a YAML file, and the tools in this repository auto-define details.
* [CML](https://www.cisco.com/site/us/en/learn/training-certifications/training/modeling-labs/index.html) - Cisco Modeling Labs is a network simulation tool with both free and paid versions. CML is the successor to VIRL. Community contributed content and resources are available via [cml-community](https://github.com/CiscoDevNet/cml-community) ⭐ 631 | 🐛 4 | 🌐 Shell | 📅 2026-08-06.
* [PNETLab](https://github.com/pnetlab/pnetlab_main) ⭐ 80 | 🐛 3 | 🌐 JavaScript | 📅 2023-07-24 - Introducing the most powerful tool to create, share and practice Networking Lab with multi-vendors.
* [Cisco DevNet Labs](https://developer.cisco.com/site/sandbox/) - Cisco's sandboxing environment.
* [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) - Cisco's original (and in later years free) network simulation tool.
* [dCloud](https://dcloud.cisco.com/) - Fully scripted, customizable environments available almost instantly in the cloud for free.
* [EVE-NG](https://www.eve-ng.net/) - The Emulated Virtual Environment For Network, Security and DevOps Professionals. There is a paid Professional Edition as well as a free [Community Edition](https://www.eve-ng.net/index.php/community/).

# Related resources

## DevNet Tools

* [netshoot](https://github.com/nicolaka/netshoot) ⭐ 10,941 | 🐛 41 | 🌐 Shell | 📅 2026-07-01 - a Docker + Kubernetes network trouble-shooting swiss-army container.
* [netshoot](https://github.com/nicolaka/netshoot) ⭐ 10,941 | 🐛 41 | 🌐 Shell | 📅 2026-07-01 - a Docker + Kubernetes network trouble-shooting swiss-army container.
* [chromaterm](https://github.com/hSaria/ChromaTerm) ⚠️ Archived - ChromaTerm is a Python module and script used for coloring the output to terminals.
* [ops\_tcpdump\_handler](https://github.com/cerner/ops_tcpdump_handler) ⚠️ Archived - Chef Cookbook to test network connectivity .
* [Celery](http://www.celeryproject.org/) - Asynchronous task queue/job queue based on distributed message passing. It is focused on real-time operation, but supports scheduling as well.
* [Ajenti](https://ajenti.org/) - Manage a remote Linux box at any time using everyday tools like a web terminal, text editor, file manager and others.
* [ProxMox Virtualiation Platform](https://www.proxmox.com/en/proxmox-ve) - Open-source platform for enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking functionality on a single platform, and easily manages high availability clusters and disaster recovery tools with the built-in web management interface.
* [telnetmyip.com](https://telnetmyip.com/) - Simple service that returns your source IP information in a json format.
* [icanhaztraceroute.com](https://icanhaztraceroute.com/) - Simple service that returns a traceroute back to your source IP.
* [Who is my ISP?](https://www.whoismyisp.org) - Simple service that shows the ISP of an IP.
* [NsLookup.io](https://www.nslookup.io) - Simple service that shows all DNS records for a domain name.
* [Topolograph](https://topolograph.com/) - Network visualization and analytics platform that reconstructs OSPF and IS-IS topologies from LSDB data. Supports offline analysis, topology comparison, what-if scenarios and historical event tracking.
* [DNSlookup](https://dnslookup.pro/) - Easy DNS lookup Tools
* [What is my isp](https://whois-myisp.com/) -  tool to find ISP name
* [iptoolspro.com](https://iptoolspro.com) - Free browser-based network tools: IP lookup, DNS lookup, port checker, traceroute, MAC address lookup, VPN leak test, IP blacklist check, and more.

## DevNet Monitoring

* [netdata](https://github.com/firehol/netdata) ⭐ 80,204 | 🐛 416 | 🌐 Go | 📅 2026-08-17 - Distributed real-time performance and health monitoring.
* [Grafana](https://grafana.com/) - Open source software for time series analytics.
* [monit](https://mmonit.com/monit/) -Small Open Source utility for managing and monitoring Unix systems. Monit conducts automatic maintnance and repair and can execute meaningful causal actions in error situations.
* [Prometheus](https://prometheus.io/) - Open-source systems monitoring and alerting toolkit originally built at SoundCloud.
* [sensu](https://sensuapp.org/) - Monitor servers, services, application health, and business KPIs. Collect and analyze custom metrics. Get notified about failures before your users do. Give your business the competitive advantage it deserves. (Open Source or Commercial).
* ELK Stack
  * [Elasticsearch](https://github.com/elastic/elasticsearch) ⭐ 77,840 | 🐛 6,072 | 🌐 Java | 📅 2026-08-17 - Open Source, Distributed, RESTful Search Engine.
  * [Kibana](https://github.com/elastic/kibana) ⭐ 21,246 | 🐛 14,239 | 🌐 TypeScript | 📅 2026-08-16 - Analytics and search dashboard for Elasticsearch.
  * [LogStash](https://github.com/elastic/logstash) ⭐ 14,921 | 🐛 2,249 | 🌐 Java | 📅 2026-08-14 - Transport and process your logs, events, or other data.
* [Graylog](https://www.graylog.org/) - Parse and enrich logs, wire data, and event data from any data source (Commercial, Free for less than 5GB/day).

## DevNet Knowledgebase

* [ITGlue](https://www.itglue.com/) - IT focused documentation solution (Commercial).

## DevNet Inventory

* [Snipe IT](https://snipeitapp.com/) - Open Source Asset Management tool.

## Knowledge Resources

* [Packet Pushers Podcast](https://packetpushers.net/) - Podcast about data networking by network architects. Deeply technical & unabashedly nerdy.
* [Risky Business Podcast](https://risky.biz/) - Features news and in-depth commentary from security industry luminaries.
* [Software Gone Wild Podcast](https://www.ipspace.net/Podcast/Software_Gone_Wild/) - Software Gone Wild is focusing on architectures, solutions and technologies that real networking engineers use in production networks.
* [Cisco DevNet Basics](https://developer.cisco.com/video/net-prog-basics) - Learn network programmability basics.
* [Cisco Tools](https://www.cisco.com/c/en/us/support/web/tools-catalog.html) - List of Cisco tools maintained by Cisco.
* [Juniper Day One Books](https://www.juniper.net/documentation/jnbooks/us/en/day-one-books) - Day One Books cover networking technologies using step-by-step instructions and practical examples written by working engineers
* [Network Lab Pro Edition](https://chaithu-lets-code.github.io/SubnetPro) - Network reference and utilities

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-17._
