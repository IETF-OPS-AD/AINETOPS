# AI for Network Operations

This repo is meant to inventory work, drafts, meetings, etc. related to AINETOPS within the IETF. 

This repo is maintained by Qin Wu (bill.wu@huawei.com) and Dan King (d.king@lancaster.ac.uk). Please email them any missing work or meetings you would like to see included/linked in this repositry. 

The following mailing list exist for **discussion of AI techniques -- including but not limited to agentic and generative approaches -- as they relate to IETF-based network operations.**

* [ainetops](https://mailman3.ietf.org/mailman3/lists/ainetops.ietf.org/)

Several other IETF lists covering AI-topics may also be found at the [end of this page](#ai-related-mailing-lists).

## Table of Contents

- [Meetings](#meetings)
  - [Upcoming IETF Meetings](#upcoming-ietf-meetings)
  - [Previous Side Meetings](#previous-side-meetings)
- [Presentations](#presentations)
- [Internet-Drafts](#internet-drafts)
  - [Network Operation](#network-operations) (OPS)
  - [LLM/AI Benchmarking](#llmai-benchmarking) (OPS)
  - [Networking for AI / AIDC](#networking-for-ai--aidc)
  - [Discovery & Naming](#discovery--naming)
  - [Transport](#transport)
  - [Security (including Authentication & Authorization)](#security-including-authentication--authorization)
  - [Inter-Agent](#inter-agent)
  - [Misc](#misc)
- [AI-related Mailing Lists](#ai-related-mailing-lists)

## Meetings

### IETF Meetings

* AINETOPS@IETF125 OPSAREA Session (03/2026): Operators Perspectices & Challenges ([Agenda](https://datatracker.ietf.org/meeting/125/materials/agenda-125-opsarea-01))(Slides)
* [AINETOPS@IETF123 OPSAREA Session](https://datatracker.ietf.org/meeting/123/materials/slides-123-opsarea-2-state-of-the-opsarea-nation-04)(Slide 21) (07/2025) 

### Side Meetings

#### IETF#125

#### IETF#124

#### IETF#123

#### IETF#122

#### IETF#121

#### IETF#120

#### IETF#119

* AI4NETWORK: 
    + Scope: Applicability of AI in the Network
    + [IETF#119 Slides](https://github.com/muzixing/IETF119-AI4NET/tree/main)

* CCO (Collective Communication Optimization) for AI Networking 
   + Scope: In-network computing has been being discussed to improve the overall performance in terms of the bandwidth consumed and/or latency when collective communications are used. The primary goals of this effort are to discuss the requirements, analysis and new technologies to optimize collective communications and to explore some usage expansion like data consistency to leverage the in-network computing capabilities.
    + [IETF#119 Material](https://github.com/CCO-IETF/ietf119-side-meeting/)

* Large Language Model (LLM) for Networking 
    + Scope: Explore the transformative potential of LLMs in the networking domain and open the discussion on potential standards for this topic.
    + [IETF#119 Slides](https://github.com/wangtz19/ietf-side-meetings) 

#### IETF#118

* AI4NETWORK: 
    + Scope: Applicability of AI in the Network
    + [IETF#119 Slides](https://github.com/muzixing/IETF119-AI4NET/tree/main)

#### IETF#117 

* Data Center Networking for AI Clusters: 
    + Scope: Discussion of challenges, requirements and technologies for data center networks tailored for large-scale AI model training.
    + [IETF#117 Slides](https://github.com/Yingzhen-ietf/AIDC-IETF117)
      
## Presentations

## Internet-Drafts

### Network Operations

* [draft-wmz-nmrg-agent-ndt-arch Network Digital](https://datatracker.ietf.org/doc/draft-wmz-nmrg-agent-ndt-arch): Network Digital Twin and Agentic AI based Architecture for AI driven Network Operations
* [draft-hong-nmrg-agenticai-ps](https://datatracker.ietf.org/doc/draft-hong-nmrg-agenticai-ps): Motivations and Problem Statement of Agentic AI for network management
* [draft-yang-nmrg-mcp-nm](https://datatracker.ietf.org/doc/draft-yang-nmrg-mcp-nm): Applicability of MCP for the Network Management
* [draft-yang-nmrg-a2a-nm](https://datatracker.ietf.org/doc/draft-yang-nmrg-a2a-nm): Applicability of A2A to the Network Management
* [draft-jadoon-nmrg-agentic-ai-autonomous-networks](https://datatracker.ietf.org/doc/draft-jadoon-nmrg-agentic-ai-autonomous-networks): Agentic AI Architectural Principles for Autonomous Computer Networks
* [draft-zhao-nmrg-ai-agent-for-ndt](https://datatracker.ietf.org/doc/draft-zhao-nmrg-ai-agent-for-ndt): AI Agent Architecture for Network Digital Twin
* [draft-bernardos-nmrg-agentic-network-optimization](https://datatracker.ietf.org/doc/draft-bernardos-nmrg-agentic-network-optimization): Solutions for enabling agentic sensing with network optimization
* [draft-chuyi-nmrg-agentic-network-inference](https://datatracker.ietf.org/doc/draft-chuyi-nmrg-agentic-network-inference): Agentic Network Architecture and Protocol for Supporting Agent Interconnection Communication and Multi-level Inference 
* [draft-zhao-ccamp-actn-optical-network-agent](https://datatracker.ietf.org/doc/draft-zhao-ccamp-actn-optical-network-agent): Integration of Network Management Agent (NMA) into ACTN-Based Optical Network
* [draft-zhao-nmop-network-management-agent](https://datatracker.ietf.org/doc/draft-zhao-nmop-network-management-agent):  AI based Network Management Agent(NMA): Concepts and Architecture
* [draft-king-rokui-ainetops-usecases](https://datatracker.ietf.org/doc/draft-king-rokui-ainetops-usecases): Artificial Intelligence (AI) for Network Operations
* [draft-irtf-nmrg-ai-challenges](https://datatracker.ietf.org/doc/draft-irtf-nmrg-ai-challenges): Research Challenges in Coupling Artificial Intelligence and Network Management
* [draft-irtf-nmrg-llm-nm](https://datatracker.ietf.org/doc/draft-irtf-nmrg-llm-nm): A Framework for LLM-Assisted Network Management with Human-in-the-Loop
* [draft-irtf-nmrg-ai-deploy](https://datatracker.ietf.org/doc/draft-irtf-nmrg-ai-deploy): Considerations of network/system for AI services
* [draft-pedro-nmrg-ai-framework](https://datatracker.ietf.org/doc/draft-pedro-nmrg-ai-framework): Artificial Intelligence Framework for Network Management

### LLM/AI Benchmarking

#### Terminology

 * [draft-gaikwad-llm-benchmarking-terminology](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-terminology/)
 * [draft-calabria-bmwg-ai-fabric-terminology/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-terminology/)
     
#### Methodology

  * [draft-gaikwad-llm-benchmarking-methodology](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-methodology/)
  * [draft-calabria-bmwg-ai-fabric-training-bench/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-training-bench/)
  * [draft-calabria-bmwg-ai-fabric-inference-bench/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-inference-bench/)

#### Profiles: SUT boundary definitions for model engines, AI firewall, AI gateways, etc.

  * [draft-gaikwad-llm-benchmarking-profiles](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-profiles/)

### Networking for AI / AIDC

* [draft-hu-rtgwg-cbfc-rsvp](https://datatracker.ietf.org/doc/draft-hu-rtgwg-cbfc-rsvp): Credit-based Flow Control Based on RSVP for RDMA transmission in WAN
* [draft-hcl-rtgwg-ai-network-problem](https://datatracker.ietf.org/doc/draft-hcl-rtgwg-ai-network-problem): Gap Analysis, Problem Statement, and Requirements in AI Networks
* [draft-hcl-rtgwg-osf-framework](https://datatracker.ietf.org/doc/draft-hcl-rtgwg-osf-framework): An OSF Framework for Artificial Intelligence (AI) Network
* [draft-cheng-rtgwg-ai-network-reliability-problem](https://datatracker.ietf.org/doc/draft-cheng-rtgwg-ai-network-reliability-problem): Reliability in AI Networks Gap Analysis, Problem Statement, and Requirements
* [draft-li-rtgwg-distributed-lossless-framework](https://datatracker.ietf.org/doc/draft-li-rtgwg-distributed-lossless-framework): Framework of Distributed AIDC Network
* [draft-du-catalist-routing-considerations](https://datatracker.ietf.org/doc/draft-du-catalist-routing-considerations): Routing Considerations in Agentic Network

### Discovery & Naming

* [draft-nandakumar-agent-sd-jwt](https://datatracker.ietf.org/doc/draft-nandakumar-agent-sd-jwt): SD Agent: Selective Disclosure for Agent Discovery and Identity Management
* [draft-cui-dns-native-agent-naming-resolution](https://datatracker.ietf.org/doc/draft-cui-dns-native-agent-naming-resolution): DNS-Native AI Agent Naming and Resolution
* [draft-mapmw-task-discovery](https://datatracker.ietf.org/doc/draft-mapmw-task-discovery): Task discovery in agentic networks
* [draft-mp-agntcy-ads](https://datatracker.ietf.org/doc/draft-mp-agntcy-ads): Agent Directory Service

### Transport

* [draft-mpsb-agntcy-messaging](https://datatracker.ietf.org/doc/draft-mpsb-agntcy-messaging): An Overview of Messaging Systems and Their Applicability to Agentic AI
* [draft-liu-agent-protocol-over-moq](https://datatracker.ietf.org/doc/draft-liu-agent-protocol-over-moq): Agent Protocol over MoQ
* [draft-nandakumar-ai-agent-moq-transport](https://datatracker.ietf.org/doc/draft-nandakumar-ai-agent-moq-transport): MoQ Transport for Agent Protocols
* [draft-jennings-ai-mcp-over-moq](https://datatracker.ietf.org/doc/draft-jennings-ai-mcp-over-moq): Model Context Protocol and Agent Skills over Media over QUIC Transport
* [draft-wang-lisp-ai-agent](https://datatracker.ietf.org/doc/draft-wang-lisp-ai-agent): Using LISP as a Network Substrate for AI Agent Communication

### Security (including Authentication & Authorization)

* [draft-klrc-aiagent-auth](https://datatracker.ietf.org/doc/draft-klrc-aiagent-auth): AI Agent Authentication and Authorization
* [draft-mishra-oauth-agent-grants](https://datatracker.ietf.org/doc/draft-mishra-oauth-agent-grants): Delegated Agent Authorization Protocol (DAAP)
* [draft-song-oauth-ai-agent-collaborate-authz](https://datatracker.ietf.org/doc/draft-song-oauth-ai-agent-collaborate-authz): OAuth2.0 Extension for Multi-AI Agent Collaboration
* [draft-liu-agent-operation-authorization](https://datatracker.ietf.org/doc/draft-liu-agent-operation-authorization): Agent Operation Authorization
* [draft-chen-oauth-scope-agent-extensions](https://datatracker.ietf.org/doc/draft-chen-oauth-scope-agent-extensions): Structured and Constraint Extensions for OAuth Scopes
* [draft-barney-caam](https://datatracker.ietf.org/doc/draft-barney-caam): Contextual Agent Authorization Mesh (CAAM)
* [draft-sarischo-6gip-aiml-security-privacy](https://datatracker.ietf.org/doc/draft-sarischo-6gip-aiml-security-privacy): Security and Privacy Implications of 3GPP AI/ML Services for 6G


### Inter-Agent

* [draft-hw-protocol-agent](https://datatracker.ietf.org/doc/draft-hw-protocol-agent)-00 AI Agent Protocols for Multi-modality
* [draft-yao-catalist-problem-space-analysis](https://datatracker.ietf.org/doc/draft-yao-catalist-problem-space-analysis)-01 Problem Space Analysis of AI Agent Protocols in IETF
* [draft-yc-ipv6-for-ioa](https://datatracker.ietf.org/doc/draft-yc-ipv6-for-ioa): Capabilities and Future Requirements of IPv6 for the Internet of Agents (IoA)
* [draft-cowles-aocl](https://datatracker.ietf.org/doc/draft-cowles-aocl): Agent Orchestration Control Layers (AOCL) Protocol
* [draft-cowles-aee](https://datatracker.ietf.org/doc/draft-cowles-aee): Agent Envelope Exchange (AEE): A Minimal JSON Envelope Format for Inter-Agent Communication
* [draft-ni-a2a-ai-agent-security-requirements](https://datatracker.ietf.org/doc/draft-ni-a2a-ai-agent-security-requirements): Security Requirements for AI Agents
* [draft-li-dmsc-macp](https://datatracker.ietf.org/doc/draft-li-dmsc-macp): Multi-agent Collaboration Protocol Suite
* [draft-zhang-dmsc-ioa-semantic-interaction](https://datatracker.ietf.org/doc/draft-zhang-dmsc-ioa-semantic-interaction): Ontology-based Semantic Interaction for Internet of Agents
* [draft-nennemann-wimse-ect](https://datatracker.ietf.org/doc/draft-nennemann-wimse-ect): Execution Context Tokens for Distributed Agentic Workflows
* [draft-song-dmsc-problem-statement](https://datatracker.ietf.org/doc/draft-song-dmsc-problem-statement): Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC)

### Misc

* [draft-scrm-aiproto-usecases](https://datatracker.ietf.org/doc/draft-scrm-aiproto-usecases): Agentic AI Use Cases
* [draft-dunbar-agent-attachment](https://datatracker.ietf.org/doc/draft-dunbar-agent-attachment): Agent Attachment Protocol
* [draft-birkholz-verifiable-agent-conversations](https://datatracker.ietf.org/doc/draft-birkholz-verifiable-agent-conversations): Verifiable Agent Conversation Records
* [draft-bondar-wca](https://datatracker.ietf.org/doc/draft-bondar-wca): Warrant Certificate Authorities (WCA): Auditable Data Provenance for AI-Agent Tool-Call Chains
* [draft-ni-wimse-ai-agent-identity](https://datatracker.ietf.org/doc/draft-ni-wimse-ai-agent-identity): WIMSE Applicability for AI Agents

## AI-related Mailing Lists

* [ainetops](https://mailman3.ietf.org/mailman3/lists/ainetops.ietf.org/)
* [agent2agent](https://mailman3.ietf.org/mailman3/lists/agent2agent.ietf.org/)
* [ai-control](https://mailman3.ietf.org/mailman3/lists/ai-control.ietf.org/)
* [aidc](https://mailman3.ietf.org/mailman3/lists/aidc.ietf.org/)
* [pidloc](https://mailman3.ietf.org/mailman3/lists/pidloc.ietf.org/)
