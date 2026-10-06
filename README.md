# Awesome-Virtual-Desktop-Infrastructure-API

## Top Virtual Desktop Infrastructure (VDI) API Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Desktop Provisioning APIs, Session Management & Infrastructure Automation*  

**Last updated: October 2026**



This repository tracks notable **commercial VDI APIs** and **open-source projects** that expose virtual desktop infrastructure through programmatic interfaces — enabling automation, orchestration, and integration of VDI provisioning, session management, and lifecycle operations into broader IT workflows.



**Examples** include Amazon WorkSpaces Core, Workspot Cloud Desktop API, Citrix DaaS REST API, VMware Horizon Cloud API, Cameyo Virtual App API, Microsoft Cloud PC Graph API, Parallels RAS API, Kasm Server API, Ericom DaaS, and Tehama Cloud API (the category leaders).



**Open-source emphasis**: VDI APIs are an emerging open-source domain. **Apache Guacamole** provides a REST API for clientless remote desktop gateway, **Kasm Workspaces** exposes API endpoints for containerized VDI automation, and **Proxmox VE** offers a comprehensive REST API for VM lifecycle management. **openvdi** brings API-first modern VDI architecture. **noVNC** and **FreeRDP** provide protocol-level APIs. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amazon WorkSpaces Core](https://aws.amazon.com/workspaces-core/)**  

  **AWS's API-driven VDI infrastructure** — provision and manage virtual desktops programmatically. **Best for AWS-centric organizations** wanting managed VDI with API automation.



- **[Microsoft Cloud PC Graph API](https://learn.microsoft.com/en-us/graph/api/resources/cloudpc)**  

  **Microsoft Graph API for Windows 365** — programmatic provisioning, management, and reporting of Cloud PCs. **Best for Microsoft 365 ecosystem integration** .



- **[Citrix DaaS REST API](https://developer.cloud.com/citrixworkspace/)**  

  **The enterprise VDI API standard** — automate desktop and app delivery, session management, and monitoring. **The most comprehensive VDI API** .



- **[VMware Horizon Cloud API](https://developer.vmware.com/)**  

  VMware's REST API for Horizon — automate desktop pools, entitlements, and session management.



- **[Workspot Cloud Desktop API](https://www.workspot.com/)**  

  Cloud-native VDI API — programmatic desktop provisioning on Azure, AWS, and GCP.



- **[Cameyo Virtual App API](https://cameyo.com/)**  

  **Application virtualization API** — package, deliver, and manage virtual apps programmatically. **Best for app virtualization automation** .



- **[Parallels RAS API](https://www.parallels.com/products/ras/)**  

  PowerShell and REST API for Parallels RAS — automate farm management and session control.



- **[Kasm Server API](https://kasmweb.com/)**  

  **Kasm Workspaces API** — programmatic session management, user provisioning, and workspace automation. **The best commercial API for containerized VDI** .



- **[Ericom DaaS](https://www.ericom.com/)**  

  DaaS platform with API for remote browser isolation and virtual desktop management.



- **[Tehama Cloud API](https://www.tehama.io/)**  

  **Secure remote work platform API** — provision and manage virtual desktops with compliance controls.



## Open-Source GitHub Projects



- **[Apache Guacamole](https://github.com/apache/guacamole-server)**  

  **Clientless remote desktop gateway with comprehensive REST API**, Apache-2.0 licensed with **3,000+ GitHub stars** . **REST API for connection management, user administration, and session control** . **Supports VNC, RDP, and SSH** — manage connections programmatically . **The most widely deployed open-source VDI API** . **Best for programmatic remote desktop access** .



- **[Kasm Workspaces API](https://github.com/kasmtech/workspaces-core-images)**  

  **Containerized VDI platform with API endpoints**, Apache-2.0 licensed with **10,000+ GitHub stars** (main repo) . **API for session management, user provisioning, and workspace automation** . **Community Edition includes API access** . **Best for containerized VDI automation** .



- **[Proxmox VE API](https://github.com/proxmox/pve-manager)**  

  **Comprehensive REST API for virtualization management**, AGPL-3.0 licensed . **API for VM/container lifecycle, storage, networking, and cluster management** . **The foundation for self-hosted VDI automation** . **Best for building VDI infrastructure on Proxmox** .



- **[XCP-ng API](https://github.com/xcp-ng/xcp)**  

  **Xen-based hypervisor with XenAPI**, GPL-2.0 licensed . **Programmatic VM lifecycle management** . **Xen Orchestra provides REST API wrapper** . **Best for Xen-based VDI automation** .



- **[openvdi](https://github.com/openvdi/openvdi)**  

  **Open-source API-first VDI platform**, AGPL-3.0 licensed . **Modern TypeScript/Node.js architecture with REST API** . **Self-hosted VDI with programmatic control** . **Best for API-first VDI deployments** .



- **[oVirt API](https://github.com/oVirt/ovirt-engine)**  

  **KVM virtualization management with REST API**, Apache-2.0 licensed . **Programmatic VM and infrastructure management** . **Best for enterprise KVM VDI automation** .



- **[OpenStack Nova API](https://github.com/openstack/nova)**  

  **Open-source cloud compute API**, Apache-2.0 licensed . **Programmatic VM lifecycle management** . **The foundation for cloud VDI** . **Best for large-scale VDI deployments** .



- **[Apache CloudStack API](https://github.com/apache/cloudstack)**  

  **Open-source cloud platform API**, Apache-2.0 licensed . **Programmatic VM, network, and storage management** . **Best for service provider VDI** .



- **[noVNC](https://github.com/novnc/noVNC)**  

  **HTML5 VNC client with JavaScript API**, MPL-2.0 licensed with **10,000+ GitHub stars** . **Embeddable VNC client for web applications** . **Best for browser-based VDI clients** .



- **[FreeRDP](https://github.com/FreeRDP/FreeRDP)**  

  **Open-source RDP client with API**, Apache-2.0 licensed . **Programmatic RDP connections** . **Best for RDP automation** .



- **[libvirt](https://github.com/libvirt/libvirt)**  

  **Virtualization management API**, LGPL-2.1 licensed . **Unified API for KVM, Xen, VMware, and more** . **The standard for virtualization management** . **Best for multi-hypervisor VDI automation** .



- **[xpra](https://github.com/Xpra-org/xpra)**  

  **Screen-for-X with HTML5 client and API**, GPL-2.0 licensed . **Programmatic remote application access** . **Best for Linux application streaming APIs** .



- **[Selkies](https://github.com/selkies-project/selkies-gstreamer)**  

  **GPU-accelerated remote desktop with API**, MPL-2.0 licensed . **WebRTC-based streaming with programmatic control** . **Best for GPU-accelerated VDI APIs** .



### Session Management & Brokering



- **[Apache Guacamole](https://github.com/apache/guacamole-server)** — Already listed. **Connection brokering API** .



- **[Kasm Workspaces](https://github.com/kasmtech/workspaces-core-images)** — Already listed. **Session management API** .



- **[UDL (Universal Desktop Linux)](https://github.com/udl/udl)** — Remote desktop with API for session management .



- **[xrdp](https://github.com/neutrinolabs/xrdp)**  

  **Open-source RDP server for Linux**, Apache-2.0 licensed . **Programmatic session management via RDP** . **Best for Linux RDP sessions** .



### Identity & Access Integration



- **[Keycloak](https://github.com/keycloak/keycloak)**  

  **Open-source identity provider with Admin REST API**, Apache-2.0 licensed . **Programmatic user and role management for VDI** . **Best for VDI identity integration** .



- **[Authentik](https://github.com/goauthentik/authentik)**  

  **Identity provider with API**, MIT/GPL licensed . **Programmatic authentication for VDI platforms** . **Best for VDI SSO integration** .



### Additional Strong Open-Source Options



- **virt-manager** — Desktop VM management (not API but GUI) .

- **Cockpit** — Web-based server management with API .

- **Portainer** — Container management with API .

- **Rancher** — Kubernetes management API .

- **Terraform Provider for Proxmox** — IaC for Proxmox VDI .

- **Ansible Proxmox Module** — Configuration management for Proxmox .

- **Ansible oVirt Module** — Configuration management for oVirt .

- **Ansible KVM Module** — Configuration management for KVM .

- **Pulumi Proxmox Provider** — IaC for Proxmox VDI .



**Frameworks for building custom VDI API solutions**: Combine **Apache Guacamole** for clientless remote desktop gateway with REST API . Use **Kasm Workspaces** for containerized VDI with API automation . Deploy **Proxmox VE** with its comprehensive REST API as the virtualization foundation . Choose **openvdi** for API-first modern VDI architecture . Integrate **Keycloak** for identity and access management . Use **libvirt** for multi-hypervisor abstraction . Note that true enterprise VDI APIs with session brokering, profile management, and vendor-supported SLAs (Citrix DaaS, Horizon Cloud, Cloud PC Graph API) remain primarily commercial territory; open-source stacks provide strong virtualization management, remote access, and containerized VDI APIs that require integration for complete enterprise VDI automation.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- VDI APIs control access to virtual desktops and potentially sensitive data. **Secure API credentials** — use API keys, OAuth, and least-privilege access . Self-hosted solutions require proper security hardening.

- **API rate limits and quotas vary** — commercial VDI APIs impose limits. Open-source APIs depend on your infrastructure capacity .

- **Open-source VDI APIs are not direct replacements for enterprise VDI APIs** — they lack session brokering, profile management, and policy controls of Citrix or Horizon . Evaluate gaps before deployment.

- **Authentication integration is critical** — VDI APIs should integrate with your identity provider for SSO and MFA. Keycloak and Authentik provide open-source options .

- The open-source ecosystem provides strong virtualization management, remote access, and containerized VDI APIs, but **session brokering, profile management, and vendor-supported SLAs** remain primarily commercial offerings.



---



**Made for DevOps engineers, platform teams, and organizations seeking VDI automation sovereignty.**  

Let's make VDI APIs more open, transparent, and programmable.
