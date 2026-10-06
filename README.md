# Awesome Virtual Desktop Infrastructure (VDI) API

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

> **A curated list of commercial SaaS products, enterprise DaaS APIs, and open-source GitHub projects for Virtual Desktop Infrastructure (VDI) provisioning, remote desktop session management, hypervisor control, and infrastructure automation.**

*Focused on Desktop Provisioning APIs, Session Management, Hypervisor Integration, and VDI Infrastructure Automation.*

---

## Table of Contents

- [Overview & Industry Context](#overview--industry-context)
- [SaaS & Hosted Enterprise VDI Platforms](#saas--hosted-enterprise-vdi-platforms)
- [Open-Source VDI & Virtualization Repositories](#open-source-vdi--virtualization-repositories)
- [Key Use Cases & Architecture](#key-use-cases--architecture)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Overview & Industry Context

Virtual Desktop Infrastructure (VDI) and Desktop-as-a-Service (DaaS) APIs enable platform engineers, DevOps teams, and enterprise IT managers to programmatically spin up, manage, scale, and tear down virtual desktops and remote application sessions. 

---

## SaaS & Hosted Enterprise VDI Platforms

**Market Size & Concentration:** The global Virtual Desktop Infrastructure (VDI) & Desktop-as-a-Service (DaaS) market is estimated at **$15 Billion to $25 Billion** (projected to reach $40+ Billion by 2030 at a ~14% CAGR). The SaaS and enterprise sector is **moderately concentrated**, dominated by tech hyperscalers (Microsoft, AWS) and legacy virtualization leaders (Citrix, Broadcom/Omnissa), alongside specialized security and cloud desktop providers.

*Table sorted by parent company size / market capitalization / enterprise valuation (Descending).*

| Product & API | Company & Valuation / Revenue | Starting Pricing | Free Tier / Free Trial Limit | Description & Key Capabilities |
| :--- | :--- | :--- | :--- | :--- |
| **[Microsoft Cloud PC Graph API](https://learn.microsoft.com/en-us/graph/api/resources/cloudpc)** | **Microsoft**<br>~$3.1 Trillion Market Cap<br>~$245 Billion Revenue | **$28.00** / user / month *(2 vCPU, 4GB RAM, 64GB storage)* | **30-Day Free Trial** *(up to 3 Cloud PCs for eligible tenant accounts)* | Microsoft Graph REST API for Windows 365. Automates enterprise Cloud PC provisioning, user entitlements, policy management, and status monitoring. |
| **[Cameyo Virtual App API](https://cameyo.com/)** | **Google / Alphabet**<br>~$2.1 Trillion Market Cap<br>~$307 Billion Revenue | **$12.00** / user / month *(Cameyo Cloud starting tier)* | **14-Day Free Trial** *(Instant access, no credit card required)* | Application virtualization REST API (acquired by Google in 2024). Delivers Windows desktop applications directly to browsers and ChromeOS environments without full desktop overhead. |
| **[Amazon WorkSpaces Core](https://aws.amazon.com/workspaces-core/)** | **Amazon (AWS)**<br>~$2.1 Trillion Market Cap<br>~$105 Billion AWS Revenue | **$7.25** / user / mo base + **$0.25** / hr *(or $22.00/mo flat rate)* | **AWS Free Tier: 2 Months** *(2 Standard bundle desktops, 40 hrs/month each)* | AWS programmatic VDI infrastructure API. Enables VDI management partners and internal platform teams to orchestrate AWS virtual desktop pools at cloud scale. |
| **[Ericom DaaS API](https://www.ericom.com/)** | **Zscaler / Ericom**<br>~$30 Billion Market Cap<br>~$2.1 Billion Revenue | **$18.00** / user / month *(starting secure access tier)* | **14-Day Free Trial** *(Guided sandbox demo environment)* | Enterprise Remote Browser Isolation (RBI) and virtual workspace delivery platform with security-focused REST APIs for access control and session management. |
| **[Citrix DaaS REST API](https://developer.cloud.com/citrixworkspace/)** | **Cloud Software Group (Citrix)**<br>~$16.5 Billion Valuation<br>~$3.2 Billion Revenue | **$15.00** / user / month *(Citrix DaaS Standard starting plan)* | **60-Day Free Trial** *(via Citrix Cloud Console, up to 25 user pilot)* | Industry-standard enterprise VDI and virtual app delivery API. Exposes comprehensive endpoint management, session brokering, security policy control, and infrastructure orchestration. |
| **[VMware Horizon Cloud API](https://developer.vmware.com/)** | **Omnissa (KKR / VMware EUC)**<br>~$4.0 Billion Valuation<br>~$1.5 Billion ARR | **$4.67** / user / month *(Horizon Apps Standard)* to **$12.50** / user / mo | **60-Day Free Trial** *(Evaluation license via Omnissa Tech Zone)* | REST API for Omnissa (formerly VMware) Horizon Cloud. Controls desktop pool lifecycle, user entitlements, session brokering, and vSphere/multi-cloud hypervisor integration. |
| **[Parallels RAS API](https://www.parallels.com/products/ras/)** | **Alludo / Parallels**<br>~$150+ Million Valuation<br>~$92 Million Revenue | **$9.99** / user / month *($120/year billed annually, 15 user min)* | **30-Day Free Trial** *(Full features for up to 50 concurrent users)* | PowerShell and REST API for Parallels Remote Application Server. Enables automated remote application publishing, load balancing, and multi-tenant farm control. |
| **[Workspot Cloud Desktop API](https://www.workspot.com/)** | **Workspot Inc.**<br>~$135 Million Total Funding<br>~$15.4 Million Est. Revenue | **$15.00** / user / month *(Workspot Enterprise starting tier)* | **30-Day Free Trial** *(Dedicated proof-of-concept environment)* | Multi-cloud enterprise VDI control plane API. Automates global virtual desktop provisioning across Microsoft Azure, AWS, and Google Cloud Platform. |
| **[Kasm Server API](https://kasmweb.com/)** | **Kasm Technologies**<br>Private Company<br>~$10 Million Est. Revenue | **$10.00** / user / month *(Starter Edition)* | **Free Forever** Community Edition *(up to 5 concurrent sessions)* or **30-Day Enterprise Trial** | REST API for containerized Workspaces (Web-Native VDI). Automates docker-based browser isolation, streaming desktop sessions, and user workspace provisioning. |
| **[Tehama Cloud API](https://www.tehama.io/)** | **Tehama Inc.**<br>Private Company<br>~$3.7 Million Est. Revenue | **$15.00** / user / month *(or $0.20/room-hour pay-as-you-go)* | **14-Day Free Trial** *(Includes 5 workspace room credits)* | Compliance-focused cloud security platform API. Programmatically provisions SOC 2 / HIPAA compliant virtual workrooms and secure remote desktop enclaves. |

---

## Open-Source VDI & Virtualization Repositories

Open-source VDI APIs and remote desktop infrastructure tools are rapidly evolving. The options below range from complete clientless remote access gateways and containerized desktop environments to bare-metal hypervisor APIs and protocol implementations.

*Table sorted by GitHub star count (Descending).*

| Open-Source Project & Repo | Star Count | License | Category & Focus | Key Features & API Highlights |
| :--- | :--- | :--- | :--- | :--- |
| **[RustDesk](https://github.com/rustdesk/rustdesk)** | [![GitHub stars](https://img.shields.io/github/stars/rustdesk/rustdesk?style=social&color=white)](https://github.com/rustdesk/rustdesk/stargazers) | AGPL-3.0 | Remote Desktop Client & Server | Open-source remote desktop client/server written in Rust. Features web console APIs, self-hosted relay servers, and cross-platform remote control. |
| **[Dockur Windows](https://github.com/dockur/windows)** | [![GitHub stars](https://img.shields.io/github/stars/dockur/windows?style=social&color=white)](https://github.com/dockur/windows/stargazers) | MIT | Containerized Windows VDI | Windows inside a Docker container with web-based HTML5 VNC/RDP access. Features REST APIs and environment variable orchestration for fast VDI container spins. |
| **[Portainer](https://github.com/portainer/portainer)** | [![GitHub stars](https://img.shields.io/github/stars/portainer/portainer?style=social&color=white)](https://github.com/portainer/portainer/stargazers) | zlib | Container Management API | Universal container management platform with HTTP REST APIs for orchestrating containerized desktop workloads, Kasm workspaces, and edge VDI nodes. |
| **[Firecracker](https://github.com/firecracker-microvm/firecracker)** | [![GitHub stars](https://img.shields.io/github/stars/firecracker-microvm/firecracker?style=social&color=white)](https://github.com/firecracker-microvm/firecracker/stargazers) | Apache-2.0 | MicroVM Hypervisor API | Minimalist, ultra-fast microVM hypervisor built in Rust by AWS. REST API controls microVM lifecycles in milliseconds for ephemeral VDI and serverless compute. |
| **[Keycloak](https://github.com/keycloak/keycloak)** | [![GitHub stars](https://img.shields.io/github/stars/keycloak/keycloak?style=social&color=white)](https://github.com/keycloak/keycloak/stargazers) | Apache-2.0 | Identity & Access Provider | Open-source IAM solution with Admin REST API. Essential for securing VDI infrastructures, providing SSO, SAML, and OAuth2/OIDC integration for virtual desktop gateways. |
| **[Rancher](https://github.com/rancher/rancher)** | [![GitHub stars](https://img.shields.io/github/stars/rancher/rancher?style=social&color=white)](https://github.com/rancher/rancher/stargazers) | Apache-2.0 | Kubernetes Orchestration API | Complete container management platform with RESTful APIs to manage Kubernetes clusters hosting containerized desktop sessions and streaming microservices. |
| **[Authentik](https://github.com/goauthentik/authentik)** | [![GitHub stars](https://img.shields.io/github/stars/goauthentik/authentik?style=social&color=white)](https://github.com/goauthentik/authentik/stargazers) | GPL-3.0 | Identity Provider & SSO | Modern identity provider with clean REST API. Enables seamless Single Sign-On (SSO), multi-factor authentication (MFA), and user directory synchronization for self-hosted VDI. |
| **[Deskreen](https://github.com/pavlobu/deskreen)** | [![GitHub stars](https://img.shields.io/github/stars/pavlobu/deskreen?style=social&color=white)](https://github.com/pavlobu/deskreen/stargazers) | AGPL-3.0 | WebRTC Screen Sharing | Turns any device with a web browser into a second display or remote application window via WebRTC, leveraging client-side streaming protocols. |
| **[WinApps](https://github.com/winapps-org/winapps)** | [![GitHub stars](https://img.shields.io/github/stars/winapps-org/winapps?style=social&color=white)](https://github.com/winapps-org/winapps/stargazers) | MIT | Application Virtualization | Run Windows applications inside Linux or Docker as if they were native OS applications using RDP and FreeRDP seamlessly. |
| **[Cockpit](https://github.com/cockpit-project/cockpit)** | [![GitHub stars](https://img.shields.io/github/stars/cockpit-project/cockpit?style=social&color=white)](https://github.com/cockpit-project/cockpit/stargazers) | LGPL-2.1 | Web-Based Server API | Web-based graphical interface and REST/JSON API for Linux servers, virtual machine management (KVM), storage, and user session monitoring. |
| **[noVNC](https://github.com/novnc/noVNC)** | [![GitHub stars](https://img.shields.io/github/stars/novnc/noVNC?style=social&color=white)](https://github.com/novnc/noVNC/stargazers) | MPL-2.0 | HTML5 VNC Client API | HTML5 VNC client library using WebSockets. Provides embeddable JavaScript APIs for integrating interactive remote desktop viewing into browser applications. |
| **[QEMU](https://github.com/qemu/qemu)** | [![GitHub stars](https://img.shields.io/github/stars/qemu/qemu?style=social&color=white)](https://github.com/qemu/qemu/stargazers) | GPL-2.0 | Machine Emulator & Hypervisor | Generic machine emulator and virtualizer. Features QEMU Monitor Protocol (QMP) JSON API for fine-grained VM state control and machine orchestration. |
| **[FreeRDP](https://github.com/FreeRDP/FreeRDP)** | [![GitHub stars](https://img.shields.io/github/stars/FreeRDP/FreeRDP?style=social&color=white)](https://github.com/FreeRDP/FreeRDP/stargazers) | Apache-2.0 | RDP Protocol API | Free implementation of the Remote Desktop Protocol (RDP). Offers C/C++ libraries and APIs for building custom RDP clients, servers, and gateways. |
| **[xrdp](https://github.com/neutrinolabs/xrdp)** | [![GitHub stars](https://img.shields.io/github/stars/neutrinolabs/xrdp?style=social&color=white)](https://github.com/neutrinolabs/xrdp/stargazers) | Apache-2.0 | RDP Server for Linux | Open-source Remote Desktop Protocol server for X11/Linux. Allows RDP clients to connect natively to Linux virtual desktops with PAM session control. |
| **[Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor)** | [![GitHub stars](https://img.shields.io/github/stars/cloud-hypervisor/cloud-hypervisor?style=social&color=white)](https://github.com/cloud-hypervisor/cloud-hypervisor/stargazers) | Apache-2.0 | KVM Cloud Hypervisor API | Rust-based Virtual Machine Monitor (VMM) running on KVM. Controlled via an OpenAPI-compliant REST API for high-density cloud desktop provisioning. |
| **[Apache Guacamole Server](https://github.com/apache/guacamole-server)** | [![GitHub stars](https://img.shields.io/github/stars/apache/guacamole-server?style=social&color=white)](https://github.com/apache/guacamole-server/stargazers) | Apache-2.0 | Remote Desktop Gateway | Native C daemon for Apache Guacamole clientless gateway. Translates VNC, RDP, and SSH protocols into WebSocket streams for browser clients. |
| **[OpenStack Nova](https://github.com/openstack/nova)** | [![GitHub stars](https://img.shields.io/github/stars/openstack/nova?style=social&color=white)](https://github.com/openstack/nova/stargazers) | Apache-2.0 | Cloud Compute Controller API | OpenStack Cloud Compute service providing REST APIs for massive multi-tenant VM provisioning, hypervisor management, and private VDI backends. |
| **[Apache CloudStack](https://github.com/apache/cloudstack)** | [![GitHub stars](https://img.shields.io/github/stars/apache/cloudstack?style=social&color=white)](https://github.com/apache/cloudstack/stargazers) | Apache-2.0 | Cloud Infrastructure API | Open-source Infrastructure-as-a-Service (IaaS) platform offering robust REST APIs to manage compute, storage, networking, and virtual desktop infrastructure. |
| **[Xpra](https://github.com/Xpra-org/xpra)** | [![GitHub stars](https://img.shields.io/github/stars/Xpra-org/xpra?style=social&color=white)](https://github.com/Xpra-org/xpra/stargazers) | GPL-2.0 | Multi-Platform Screen for X | "Screen for X11" remote application server with HTML5 client and python bindings. Seamlessly forwards individual GUI application windows to remote endpoints. |
| **[Selkies GStreamer](https://github.com/selkies-project/selkies-gstreamer)** | [![GitHub stars](https://img.shields.io/github/stars/selkies-project/selkies-gstreamer?style=social&color=white)](https://github.com/selkies-project/selkies-gstreamer/stargazers) | MPL-2.0 | WebRTC Streaming API | GPU-accelerated WebRTC streaming platform for Linux containers and VMs. Optimized for ultra-low latency desktop streaming and gaming VDI APIs. |
| **[libvirt](https://github.com/libvirt/libvirt)** | [![GitHub stars](https://img.shields.io/github/stars/libvirt/libvirt?style=social&color=white)](https://github.com/libvirt/libvirt/stargazers) | LGPL-2.1 | Virtualization API toolkit | Standard C toolkit and API for managing platform virtualization (KVM, Xen, VMware ESXi, QEMU). Foundation for custom VDI hypervisor orchestration. |
| **[Apache Guacamole Client](https://github.com/apache/guacamole-client)** | [![GitHub stars](https://img.shields.io/github/stars/apache/guacamole-client?style=social&color=white)](https://github.com/apache/guacamole-client/stargazers) | Apache-2.0 | Clientless Web Application | Java HTML5 web application providing REST API for connection brokering, authentication modules, session recording, and user access management. |
| **[XCP-ng](https://github.com/xcp-ng/xcp)** | [![GitHub stars](https://img.shields.io/github/stars/xcp-ng/xcp?style=social&color=white)](https://github.com/xcp-ng/xcp/stargazers) | GPL-2.0 | Xen Hypervisor Platform | Turnkey open-source hypervisor based on XenServer. Uses XenAPI (JSON-RPC / XML-RPC) for programmatic VM lifecycle management and VDI pools. |
| **[oVirt Engine](https://github.com/oVirt/ovirt-engine)** | [![GitHub stars](https://img.shields.io/github/stars/oVirt/ovirt-engine?style=social&color=white)](https://github.com/oVirt/ovirt-engine/stargazers) | Apache-2.0 | Enterprise KVM Management | Complete KVM management platform offering an enterprise REST API for VM pools, virtual desktop storage domains, and host cluster management. |
| **[Kasm Workspaces Core Images](https://github.com/kasmtech/workspaces-core-images)** | [![GitHub stars](https://img.shields.io/github/stars/kasmtech/workspaces-core-images?style=social&color=white)](https://github.com/kasmtech/workspaces-core-images/stargazers) | Apache-2.0 | Docker VDI Images | Core Docker container images and scripts for Kasm Workspaces containerized desktop streaming, browser isolation, and API integration. |
| **[Proxmox VE Manager](https://github.com/proxmox/pve-manager)** | [![GitHub stars](https://img.shields.io/github/stars/proxmox/pve-manager?style=social&color=white)](https://github.com/proxmox/pve-manager/stargazers) | AGPL-3.0 | Virtualization Management | Management backend for Proxmox VE. Exposes a comprehensive REST API for VM/LXC creation, storage, networking, and self-hosted VDI orchestration. |

---

## Key Use Cases & Architecture

1. **Automated Desktop Provisioning:** Spin up temporary or persistent virtual desktops on-demand for contractors, developers, or remote employees using REST APIs.
2. **Clientless Remote Access Gateways:** Embed HTML5/WebSocket remote desktop sessions directly into web portals without requiring endpoint client installation (e.g., Apache Guacamole, noVNC, Kasm).
3. **Containerized VDI & Ephemeral Workspaces:** Run isolated browser sessions or desktop apps in Docker containers or MicroVMs for remote browser isolation (RBI) and security sandboxing.
4. **Multi-Tenant Session Brokering:** Manage user entitlements, identity SSO, SAML/OIDC authentication, and session limits programmatically.

---

## How to Contribute

Contributions are welcome! Please follow these guidelines:

1. Fork this repository.
2. Add or update entries in [README.md](file:///C:/Users/hp/Documents/Projects/Awesome-Virtual-Desktop-Infrastructure-API/README.md) following the tabular structure.
3. Ensure exact pricing, free trial specifications, or GitHub star badges are included.
4. Submit a Pull Request with a short summary of changes.

---

## Disclaimer

- This repository is a community-curated list and does not constitute an official endorsement.
- All product names, logos, brands, and trademarks belong to their respective owners.
- Financial figures, market capitalization, and valuations are accurate as of late 2026 based on public filings and industry disclosures.
