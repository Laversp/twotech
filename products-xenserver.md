Home
›
Solutions
›
Citrix
›
XenServer

Citrix Cloud Solutions — XenServer

# XenServer — Built for Work and Not Built to Break the Bank

Citrix XenServer is a Type-1 bare-metal hypervisor purpose-built for high-performance virtualisation — specifically optimised to power Citrix Virtual Apps and Desktops workloads, while supporting everyday server virtualisation needs. Enterprise-grade reliability, straightforward management, and a total cost of ownership that does not require a finance committee to approve.

Type-1 Bare-Metal Hypervisor
Optimised for Citrix CVAD & VDI
Included in Citrix Subscriptions
Managed via XenCenter

Powered by

Citrix

XenServer

The Citrix Solutions Series

XenServer is a **server virtualisation platform** that enables you to create and manage a pool of virtual machines across your infrastructure. **XenCenter** is the management console for XenServer — providing a single, intuitive interface for configuration, monitoring, live migration, and resource pool management. Together, they form a robust, cost-effective hypervisor offering that is fully integrated with the broader Citrix product stack, from Virtual Apps and Desktops to Citrix Provisioning and DaaS.

Type-1 Hypervisor

XenCenter Management

Resource Pools

Citrix Overview

Platform Overview

## What Is Citrix XenServer?

XenServer (formerly Citrix Hypervisor, and before that Citrix XenServer) is built on the open-source Xen Project hypervisor — one of the most tested and deployed virtualisation technologies in the world. As a Type-1 hypervisor, it runs directly on bare-metal server hardware, with no host operating system in between — giving virtual machines direct, efficient access to physical resources. Here are the four things every organisation should understand about it.

Type-1 Bare-Metal Performance

XenServer installs directly on server hardware — no host OS, no overhead layer. Virtual machines access physical CPU, memory, and storage resources with near-native efficiency, making it the right choice for performance-sensitive workloads including VDI, multi-session desktops, and database servers.

Purpose-Built for Citrix Workloads

XenServer is the only hypervisor purpose-engineered for Citrix Virtual Apps and Desktops and Citrix Provisioning. Unique optimisations — IntelliCache, PVS-Accelerator, MCS Read Cache — are available exclusively on XenServer and deliver tangible performance and cost advantages for Citrix environments that no other hypervisor can match.

Simple Management via XenCenter

XenCenter is the Windows-based management console included with all XenServer editions. It provides a single pane of glass for managing hosts, resource pools, virtual machines, storage repositories, and networking — with intuitive wizards for common tasks and no requirement for specialised CLI expertise.

Included in Your Citrix Subscription

XenServer Premium Edition is now included at no additional cost in Citrix for Private Cloud, Citrix Universal Hybrid Multi-Cloud, and Citrix Platform License subscriptions. If your organisation is already a Citrix customer, you may already be entitled to XenServer — eliminating the need to pay separately for a third-party hypervisor.

Core Capabilities

## Six Capabilities That Make XenServer a Solid Platform

XenServer covers the essential virtualisation capabilities that organisations need day-to-day — with specific deep integrations for Citrix environments and broad support for general workloads.

Resource Pools & Live Migration

XenServer groups physical hosts into resource pools — managed as a single unit, with shared storage and unified networking. Virtual machines can be live-migrated between hosts within a pool with no downtime, enabling rolling maintenance and workload balancing across the entire pool without disrupting running services.

High Availability

Flexible Storage Repositories

XenServer supports a wide range of storage backends — local disk, NFS, iSCSI, Fibre Channel, and software-defined storage. Storage Repositories are managed centrally via XenCenter and can be shared across pool hosts, providing flexibility to match storage architecture to budget and performance requirements without vendor lock-in.

Multi-Storage Support

IntelliCache — Citrix VDI Optimisation

IntelliCache is a XenServer-exclusive feature that dramatically reduces shared storage I/O for Citrix Virtual Desktop deployments. By caching common OS read operations in the host's local storage, IntelliCache reduces storage network traffic by up to 95% in MCS environments — cutting storage costs and improving desktop boot and logon times.

Citrix Exclusive

PVS-Accelerator

PVS-Accelerator works alongside Citrix Provisioning to cache streaming disk data locally on each XenServer host, eliminating repetitive reads from central provisioning servers. This dramatically accelerates VM boot storms, reduces network load during mass boot events, and improves the consistency of user experience across all provisioned desktops and servers.

Citrix Provisioning

Advanced Networking

XenServer supports virtual switching, VLAN tagging, NIC bonding for redundancy and throughput, and QoS traffic shaping — all configurable through XenCenter without CLI expertise. Multiple physical NICs can be bonded for high-availability network paths, and storage and management traffic can be isolated to dedicated networks for security and performance.

VLAN & Bonding

Docker Containers on Linux VMs

XenServer supports running Docker containers inside Linux virtual machines — meaning organisations can consolidate traditional server workloads and containerised microservices on the same hypervisor platform. This removes the need for a separate container host infrastructure, reducing server count and management complexity across mixed workload environments.

Container Support

Guest Operating System Support

## What Can Run on XenServer?

XenServer supports a broad range of guest operating systems for virtualised workloads — covering current and legacy Windows Server editions, modern Linux distributions, and both 32-bit and 64-bit architectures. This makes it suitable for consolidating mixed server environments, not just Citrix desktops.

Windows Server 2022

Fully supported guest

Windows Server 2019

Fully supported guest

Windows Server 2016

Fully supported guest

Windows 11 & 10

VDI / desktop workloads

Red Hat Enterprise Linux

RHEL 7, 8 & 9

Ubuntu Server

LTS releases supported

CentOS / Rocky Linux

Community Linux guests

SUSE Linux Enterprise

SLES guest support

**General-purpose workloads:** While XenServer is engineered to deliver the best performance for Citrix CVAD and VDI, it is equally capable as a general-purpose hypervisor for file servers, application servers, database workloads, and infrastructure services — making it a viable platform for organisations that want to consolidate their entire server estate onto a single, cost-effective hypervisor.

Industry Comparison

## XenServer vs VMware vSphere — The Honest Comparison

VMware vSphere remains a feature-rich platform well-suited to complex, performance-intensive enterprise environments. However, since Broadcom's acquisition of VMware in November 2023, pricing and licensing changes have been dramatic — and for many organisations, the cost equation has shifted fundamentally.

**The Broadcom pricing reality:** Since acquiring VMware, Broadcom has eliminated perpetual licensing, enforced subscription-only contracts, consolidated roughly 8,000 product SKUs down to four bundles, and introduced a 72-core minimum purchase requirement from April 2025. Customers have reported cost increases ranging from **150% to over 1,000%** on renewal. Missing a renewal anniversary date now triggers a 20% penalty fee. For many South African organisations — particularly SMBs and mid-market businesses — XenServer has become the only financially viable hypervisor option.

| Comparison Area | Citrix XenServer | VMware vSphere (Post-Broadcom) |
| --- | --- | --- |
| Licensing model | ● Included in Citrix subscription — Premium Edition at no additional cost for Citrix customers. Per-socket term licence available for standalone deployments. | ● Subscription-only. Perpetual licences discontinued. All customers must renew on Broadcom's timetable or face a 20% late penalty. |
| Minimum purchase | ● Per-socket licensing — pay for the sockets you use. No artificial minimum core requirements imposed. | ● 72-core minimum per CPU from April 2025. A server with 8 cores must be licensed for 72 — paying for capacity you do not use. |
| Cost trend | ● Stable, predictable licensing. Included with Citrix subscriptions — potential net cost of zero if already a Citrix customer. | ● Reported increases of 150%–1,000%+ on renewal. Customers report 8–15× cost increases with no corresponding value increase. |
| Product flexibility | ● Standard and Premium editions with clear feature differentiation. Trial Edition available for evaluation. | ● Reduced from ~8,000 SKUs to 4 bundles. Customers must purchase bundled products they may not need, at higher aggregate cost. |
| Citrix integration | ● Purpose-built. Exclusive features — IntelliCache, PVS-Accelerator, MCS Read Cache — only available on XenServer. Native integration with CVAD and Provisioning. | ● Supported but not optimised. No Citrix-specific hypervisor features. IntelliCache and PVS-Accelerator unavailable. |
| Management tooling | ● XenCenter included in all editions — no additional cost. Intuitive Windows client suitable for administrators without deep hypervisor expertise. | ● vCenter Server required for cluster management — now bundled into subscription tiers, adding to base cost. |
| Storage costs | ● No storage throughput licence fees. Use any compatible storage without additional per-GB or per-IO licensing charges. | ● vSAN storage features are bundled into higher-tier subscriptions, often forcing customers into more expensive tiers than their compute needs require. |
| Ecosystem maturity | ● Broad Windows and Linux guest support. Mature platform with a decade-plus track record in production environments globally. | ● Widest ecosystem compatibility. However, ongoing licensing changes and partner programme reductions introduce vendor dependency risk. |

**The honest assessment:** VMware vSphere remains the more feature-rich platform for very large, complex environments that require capabilities beyond XenServer's scope — and for organisations already deeply invested in VMware tooling where migration costs outweigh licence savings. For organisations running Citrix workloads, or those looking for a reliable, straightforward hypervisor without enterprise-scale complexity, XenServer delivers everything needed at a total cost that makes sound financial sense.

Business Value

## How XenServer Will Help Your Business

Beyond the technical specifications, XenServer delivers three categories of business value that matter to decision-makers — not just IT teams.

Predictable, Controllable Infrastructure Costs

XenServer eliminates the budget shock that VMware customers are now experiencing. Included in your Citrix subscription, or available on straightforward per-socket term licensing, XenServer gives finance teams a predictable line item — not an unpredictable renewal negotiation with a vendor that has fundamentally changed its pricing model.

Financial Predictability

Faster Deployment — Lower Operational Overhead

XenServer is straightforward to install, configure, and manage. XenCenter guides administrators through host setup, pool creation, VM deployment, and storage configuration without deep hypervisor expertise. This reduces the skills barrier for organisations without dedicated virtualisation specialists and shortens time-to-production for new workloads.

Operational Simplicity

Better Citrix Performance — Out of the Box

For organisations running Citrix CVAD, DaaS, or Provisioning, XenServer delivers measurably better user experience than any competing hypervisor — because IntelliCache, PVS-Accelerator, and MCS Read Cache are engineered specifically for Citrix workload patterns. Faster logons, faster boot storms, and lower storage costs are not configuration options — they are defaults.

Citrix Performance

How It's Delivered

## Delivered as a Managed Service by OAS

OAS designs, deploys, and manages XenServer environments on your behalf — from initial architecture through to day-to-day operations, patching, and incident response.

Architecture & Deployment

OAS designs your XenServer environment from the ground up — host sizing, resource pool architecture, storage repository design, and networking layout — ensuring the platform is correctly engineered for your workload mix from day one.

Expert Design

Monitoring & Health Management

Continuous monitoring of host health, resource utilisation, storage capacity, and VM performance — with proactive intervention before issues reach your users or cause unplanned downtime.

Always On

Patching & Lifecycle Management

OAS manages the XenServer patch cycle — applying hotfixes and updates using rolling pool upgrades via XenCenter to maintain host currency without VM downtime, keeping your environment supported and secure.

Fully Managed

Incident Response & Escalation

When something goes wrong — a host failure, a storage issue, or an unexpected VM crash — OAS responds immediately, using XenServer's live migration and HA capabilities to restore service and investigate root cause.

Expert Support

## Ready to Move to a Hypervisor That Won't Break the Budget?

Speak to an OAS consultant about XenServer — whether you are a Citrix customer looking to use your included entitlement, or considering a move away from VMware.

Talk to a Consultant

Download Product Overview