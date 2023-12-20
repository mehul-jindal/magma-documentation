---
layout: page
---

# Architecture


The Magma architecture is depicted as agnostic to 3GPP generation and access networks like cellular or WiFi. It comprises three main components:

**Access Gateway (AGW):** This element provides network services and policy enforcement, operating as an evolved packet core in LTE networks. It collaborates with standard commercial radio hardware without requiring modifications.

**Orchestrator:** This cloud-based service offers a user-friendly method to configure and monitor wireless networks securely. It can be hosted on public or private clouds, enabling users to access analytics and traffic flow data through the Magma web UI.

**Federation Gateway:** This gateway connects the Magma network with an existing Mobile Network Operator (MNO) core network via standard 3GPP interfaces. It acts as an intermediary, ensuring consistency in core functions such as authentication, data plans, policy enforcement, and charging between the Magma network and the operator's network.
