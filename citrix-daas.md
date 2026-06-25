---
product: "Citrix DaaS"
url: /products/citrix-daas
short_description: "Citrix Cloud Solutions — Desktop as a Service"
summary: "Citrix DaaS is the platform at the heart of most enterprise Citrix deployments. It virtualises applications and desktops inside your data centre or cloud, and delivers them to any device over Citrix's proprietary HDX protocol — so users get a rich, responsive experience and your data never leaves the boundary you define. The control plane is managed entirely by Citrix in the cloud. Your workloads stay exactly where you need them."

# === Hero extras — to be wired up when ProductHero is built ===
hero_badges:
  - "Gartner #1 — All 4 DaaS Use Cases 2025"
  - "HDX Protocol — Industry-Leading Performance"
  - "Microsoft Entra ID & MFA Integration"
  - "Any Cloud · Any Hypervisor · Any Device"
hero_aside_label: "Powered by"
hero_aside_pillar: "Citrix"
hero_aside_sub: "DaaS — Virtual Apps & Desktops"

# === Per-page CTA (consumed by route file when built) ===
cta_heading: "Ready to Modernise Your Application Delivery?"
cta_body: "Speak to an OAS consultant about Citrix DaaS — whether you are virtualising your first application estate, migrating from a legacy Citrix on-premises deployment, or exploring hybrid resource locations."
cta_primary_label: "Talk to a Consultant"
cta_primary_href: "/contact/sales"
cta_secondary_label: "Download Product Overview"
cta_secondary_href: "#"   # placeholder — replace with actual PDF link when available
---


## The Citrix Solution Series

Citrix DaaS is the core of the Citrix portfolio — the platform that virtualises applications and desktops and has been the **industry standard for secure application delivery for over 30 years**. It works alongside Secure Private Access for ZTNA-based access, XenServer as the preferred hypervisor for on-premises workloads, and uberAgent for deep performance monitoring — all deployed and managed by OAS as a unified, enterprise-grade workspace.


## The Cloud Control Plane And Your Resource Locations

The fundamental architecture of Citrix DaaS separates the control plane from the workloads — Citrix manages the orchestration layer in the cloud, while your applications and desktops run wherever your business requires them to.

### The Control Plane

Managed by Citrix in the cloud. Citrix manages the Delivery Controllers, brokering database, Citrix Studio, Citrix Monitor, and licensing entirely in the cloud. There are no infrastructure components for you to deploy, patch, or maintain at the control layer. **Citrix handles redundancy, updates, and availability** — your administrators manage policies and resources through a browser-based Studio portal, not servers.

### The Bridge

Deployed by OAS at each resource location. Cloud Connectors are lightweight Windows servers that act as the secure, outbound-only communication channel between your workloads and the Citrix Cloud control plane. **No inbound firewall ports are required.** A minimum of two per resource location provides high availability, with Local Host Cache enabling continued session brokering even if cloud connectivity is temporarily interrupted.

### The Resource Locations

Your workloads, wherever they live. Virtual Delivery Agents (VDAs) are installed on the Windows or Linux machines that host your applications and desktops — in your data centre, Azure, AWS, Google Cloud, or any combination. **The VDA registers with Citrix Cloud via the Cloud Connector** and handles the HDX session with the end user's device directly.


## The Business Case in Four Numbers

Citrix DaaS has been ranked first by Gartner across all four DaaS use cases for three consecutive years. The platform's advantage is measurable — in operational savings, user experience, security, and deployment flexibility.

### 71% — Reduction in Operational Overhead

Forrester's Total Economic Impact study found organisations adopting Citrix DaaS reduced IT operational overhead by up to 71% — driven by the elimination of control-plane server management and Citrix-automated platform updates.

### #1 — Gartner DaaS Leader, All 4 Use Cases, 3 Years Running

Citrix was ranked highest by Gartner in Remote Workers, High Security & Compliance, High Performance, and Custom Enterprise Architecture use cases in both the 2024 and 2025 Critical Capabilities reports.

### Any Cloud, Hypervisor, or Data Centre

DaaS supports Azure, AWS, Google Cloud, XenServer, Hyper-V, Nutanix AHV, and VMware vSphere as resource locations — all managed from the same Citrix Studio console with a unified policy and monitoring framework.

### ~3 Weeks — Continuous Feature Updates, No Downtime

Citrix DaaS releases new features and security updates approximately every three weeks — automatically, transparently, and without requiring maintenance windows or infrastructure changes from your team.


## What Citrix DaaS Does For Your Business

Six capabilities that make DaaS the right platform for organisations delivering applications at scale — across diverse device types, multiple locations, and complex user populations.

### HDX Protocol — Performance on Any Network

Citrix HDX (High Definition Experience) is the proprietary protocol that carries application sessions from the VDA to the user's device. It adapts in real time to available bandwidth, latency, and packet loss — maintaining a responsive, visually accurate session even on constrained or congested connections. HDX supports adaptive transport over UDP/DTLS for low-latency scenarios, and handles specialist peripherals including Bloomberg keyboards, dictation devices, webcams, USB redirection, and GPU-intensive workloads with full fidelity.

### Machine Creation Services — Provisioning at Scale

Machine Creation Services (MCS) is Citrix's provisioning engine — it creates and manages pools of virtual machines from a single master image across any supported hypervisor or cloud platform. Changes to the master image are published to the entire pool at the next reboot. MCS supports persistent VDI (assigned desktops), non-persistent pooled desktops (where the machine resets at logoff), and multi-session RDS servers — with Autoscale powering machines on and off based on schedule or load to control cloud infrastructure costs.

### Citrix Profile Management — User Personalisation

In non-persistent desktop environments, user settings, application preferences, and personal files must travel with the user — not stay on the machine. Citrix Profile Management captures and synchronises user profiles to a central file share or cloud storage, ensuring that regardless of which pooled desktop a user lands on, their environment is consistent and personalised. Profile Management integrates with Microsoft FSLogix for Office 365 container support, covering Outlook OST files, OneDrive, and Teams caches in pooled deployments.

### Citrix Studio & Monitor — Unified Management

Citrix Studio is the web-based administration console for the entire DaaS environment — machine catalogues, delivery groups, policies, image management, and hosting connections are all configured here. Citrix Monitor provides real-time session visibility, logon performance analysis, historical trending, and the ability to shadow or disconnect user sessions remotely. Both are cloud-hosted by Citrix, require no local infrastructure, and receive new capabilities automatically with each platform update.

### HDX Policies — Granular Session Security Controls

HDX policies govern exactly what users can and cannot do within a virtual session — clipboard direction (copy/paste in or out), client drive mapping, USB device access, printer redirection, watermarking, session recording, and screen capture prevention. Policies are applied through Group Policy or Citrix Studio and can be scoped to specific delivery groups, users, or device types — providing precise, auditable control over data movement within every application session.

### Citrix Analytics for Performance

Citrix Analytics for Performance uses machine learning to quantify user experience across every session and every site — generating a User Experience Score that makes performance visible at a glance. It identifies the root cause of logon delays, application launch failures, and session instability, and surfaces proactive alerts before users raise support tickets. Analytics spans all resource locations simultaneously, giving your OAS team a single view of experience quality across your entire Citrix estate.


## Your Workloads, Your Location — One Control Plane

A resource location is anywhere you install Cloud Connectors and place VDA workloads. Citrix DaaS supports multiple resource locations simultaneously — each managed from the same Studio console, with the same policies, monitoring, and user workspace. Your data stays where you need it; Citrix handles everything else.

### On-Premises Data Centre — Your Infrastructure, Full Data Sovereignty

- VDAs run on XenServer, Hyper-V, Nutanix AHV, or VMware vSphere
- Applications and data never leave your physical facility
- Ideal for regulated workloads, sensitive data, and legacy application estates
- Cloud Connectors provide outbound-only connectivity — no inbound ports required
- Local Host Cache enables session brokering during cloud outages

### Public Cloud — Azure, AWS, or Google Cloud, On Demand Scale

- VDAs provision on demand using MCS and Autoscale — pay only for what you use
- Microsoft Azure is the primary cloud partner — deep MCS and Entra ID integration
- AWS and Google Cloud supported as full resource locations
- Citrix Managed Azure option available — Citrix manages the Azure subscription too
- Windows 365 Cloud PCs integrated as a resource location via the Citrix W365 Connector

### Hybrid — On-Premises and Cloud, Side by Side

- Deploy sensitive workloads on-premises and burst capacity to Azure when demand spikes
- Users see one unified workspace regardless of which resource location serves them
- Optimal Gateway Service routing connects users to the nearest resource location globally
- Separate resource locations per site, region, or compliance boundary — all from one console
- Migrate workloads to cloud at your pace — no forced cutover or architecture change

**Why this matters for South African businesses:** Data sovereignty is a key consideration under POPIA. Citrix DaaS's resource location model means your application workloads and data remain in South Africa — in your own data centre or a local cloud region — while Citrix manages the global control plane. You meet your data residency obligations without sacrificing the operational benefits of cloud-managed infrastructure.


## Microsoft Entra ID Integration and MFA

Citrix DaaS integrates natively with Microsoft Entra ID (formerly Azure Active Directory) for authentication, device identity, and conditional access — giving organisations that have invested in Microsoft 365 a seamless, unified identity experience across their virtual workspace.

### Microsoft Entra Single Sign-On for DaaS

- Single login — Entra credentials flow through to virtual session
- Federated Authentication Service (FAS) issues session certificates
- Eliminates double-login friction on non-persistent pooled desktops
- Supported on Windows, Linux, and macOS VDAs
- Configurable directly from the Citrix Cloud portal

### Entra ID Multi-Factor Authentication

- Entra Conditional Access policies enforce MFA at Workspace login
- Microsoft Authenticator, TOTP, SMS, and hardware token support
- Device compliance checks via Entra ID and Microsoft Intune integration
- MFA scope configurable by user group, location, or risk signal
- Entra ID extension attributes supported in MCS for advanced policy filtering

### Microsoft Entra Joined VDAs

- VDAs can be Entra joined, Hybrid Entra joined, or domain-joined
- MCS provisions Entra joined catalogs in Microsoft Azure
- Intune co-management supported for Hybrid Entra joined non-persistent VMs
- Entra ID service accounts manage device objects — separate from provisioning credentials
- Supports organisations migrating from on-premises AD to cloud-only identity

### Citrix Gateway Service & Optimal Routing

- Citrix Gateway Service — cloud-hosted, globally distributed, no on-premises VPX required
- Rendezvous Protocol bypasses Cloud Connector for reduced overhead
- Network Locations define internal vs external routing automatically
- Optional on-premises NetScaler gateway for environments requiring local control
- TLS encryption for all HDX sessions traversing the public internet


## Delivered as a Managed Service by OAS

OAS has 40+ years of enterprise IT experience and deep Citrix expertise. We design, deploy, and operate your DaaS environment — from initial architecture through day-to-day management, monitoring, and incident response.

### Architecture & Deployment

OAS designs your DaaS environment from the ground up — resource location strategy, Cloud Connector sizing, MCS catalogue design, Autoscale configuration, Entra ID integration, and HDX policy framework — ensuring the platform is correctly engineered for your user populations and application mix from day one.

### 24/7 Monitoring & Session Management

OAS monitors your Citrix environment continuously via Citrix Monitor and Analytics for Performance — tracking session health, logon times, VDA registration, and resource utilisation. Issues are identified and resolved proactively, before users experience disruption.

### Image & VDA Lifecycle Management

OAS manages the full VDA image lifecycle — OS patching, application updates, MCS image publishing, and VDA version upgrades via the VDA Upgrade Service. Your desktop pool stays current, secure, and consistent without impacting production users during business hours.

### Incident Response & Escalation

When something goes wrong — a VDA registration failure, a Cloud Connector outage, an Entra ID authentication issue, or a degraded user experience — OAS responds immediately, investigates root cause, and restores service. We are your first call, not your last resort.
