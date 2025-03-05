# inNet - Intent-Based Network Management Tool

## Overview
**inNet** is an intent-driven network management tool designed to implement the **TM Forum's TMF921 Intent Management API**. It enables autonomous management of network resources across the **cloud-edge continuum**, ensuring efficient resource allocation, and dynamic resource and service level adaptations.

## APIs
- As stated before, inNet will follow TMF921 Intent Management API (v5). The specification in OpenAPI format is available here: https://www.tmforum.org/oda/open-apis/directory/intent-management-api-TMF921/v5.0

## Key Features
- **TMF921 Compliance**: Implements the TM Forum's standard for intent management.
- **Intent-Driven Operations**: Allows users to define high-level network intents without specifying low-level configurations.
- **Monitoring & Adaptation**: Continuously assesses network conditions and adjusts configurations dynamically.
- **Scalability & Extensibility**: Built with modularity in mind for easy expansion and integration.

## Architecture
**inNet** follows the TMF921 intent lifecycle, consisting of:
1. **Intent Creation**: Users express network objectives (e.g., latency constraints, data rate requirements, coverage areas, device mobility, etc).
2. **Validation**: The system validates and negotiates feasibility.
3. **Translation and Fulfilment**: Intent is translated into actionable network configurations.
4. **Monitoring & Reporting**: Continuous evaluation to ensure alignment with intent expectations.
5. **Assurance**: The system autonomously adjusts to maintain compliance.


## Roadmap
- [ ] Implement intent validation, translation and fulfilment leveraging 3GPP Network Slice management interfaces
- [ ] Implement Closed-loop based assurance mechanisms



## Contact
For support or inquiries, reach out via:
- Email: j.brenes@nextworks.it



