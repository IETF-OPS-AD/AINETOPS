# AI for Network Operations

This repository inventories work, drafts, meetings, etc. related to AINETOPS within the IETF.

This repository is maintained by Qin Wu (bill.wu@huawei.com) and Dan King (d.king@lancaster.ac.uk). Please email them any missing work or meetings you would like to see included or linked in this repository.

The following mailing list exists for **discussion of AI techniques -- including but not limited to agentic and generative approaches -- as they relate to IETF-based network operations.**

* [ainetops](https://mailman3.ietf.org/mailman3/lists/ainetops.ietf.org/)

Several other IETF lists covering AI topics may also be found at the [end of this page](#ai-related-mailing-lists).

## Table of Contents

- [Meetings](https://github.com/IETF-OPS-AD/AINETOPS/blob/main/meetings.md)
- [Presentations](#presentations)
- [Internet-Drafts](#internet-drafts)
  - [Network Operations](#network-operations) (OPS)
  - [LLM/AI Benchmarking](#llmai-benchmarking) (OPS)
  - [Discovery & Naming](#discovery--naming) (Discussion in DAWN)
  - [Transport](#transport) (Discussion in Agent2Agent)
  - [Security (including Authentication & Authorization)](#security-including-authentication--authorization)
  - [Observability Intervention and Control](#observability-intervention-and-control) (OPS)
  - [Inter-Agent Communication](#inter-agent-communication) (Discussion in Agent2Agent)
  - [Networking for AI / AIDC](#networking-for-ai--aidc)
  - [Misc](#misc)
- [Side Meetings](#side-meetings)
- [Hackathons](#hackathons)
- [Incoming IETF Liaison Statements](#incoming-ietf-liaison-statements)
- [AI-related Mailing Lists](#ai-related-mailing-lists)
- [Further AINETOPS Reading](#further-ainetops-reading)
      
## Presentations

## Internet-Drafts

### Network Operations

#### Engineering Topics
* [draft-mackey-nmop-kg-for-netops](https://datatracker.ietf.org/doc/draft-mackey-nmop-kg-for-netops): Knowledge Graph Framework for Network Operations
* [draft-smith-opsawg-ai-network-governance](https://datatracker.ietf.org/doc/draft-smith-opsawg-ai-network-governance): Governance Framework for AI-Mediated Autonomous Network Device Management
   communication in network management.
* [draft-wu-nmop-nma-nti-problem-statement](https://datatracker.ietf.org/doc/draft-wu-nmop-nma-nti-problem-statement/):Problem Statement for Standardizing the northbound Task Interface (NTI) of
  the Network Management Agent
* [draft-zhao-nmop-nma-a2u-yang](https://datatracker.ietf.org/doc/draft-zhao-nmop-nma-a2u-yang/):Framework and YANG Data Model for the NMA A2U Interface
* [draft-cui-nmop-agent-sketch-com](https://datatracker.ietf.org/doc/draft-cui-nmop-agent-sketch-com/):Operational Requirements for Network State Exchange in Agent-Assisted Network Operations
* [draft-king-rokui-ainetops-usecases](https://datatracker.ietf.org/doc/draft-king-rokui-ainetops-usecases): Artificial Intelligence (AI) for Network Operations
* [draft-zeng-opsawg-applicability-mcp-a2a](https://datatracker.ietf.org/doc/draft-zeng-opsawg-applicability-mcp-a2a/): When NETCONF Is Not Enough: Applicability of MCP and A2A for Advanced Network
   Management Scenarios
* [draft-zeng-opsawg-llm-netconf-gap](https://datatracker.ietf.org/doc/draft-zeng-opsawg-llm-netconf-gap/): Gap Analysis of Network Configuration Protocols in LLM-Driven Intent-Based Networking
* [draft-zw-opsawg-mcp-network-mgmt](https://datatracker.ietf.org/doc/draft-zw-opsawg-mcp-network-mgmt/): Model Context Protocol (MCP) Extensions for Network Equipment Management
* [draft-zhao-nmop-network-management-agent](https://datatracker.ietf.org/doc/draft-zhao-nmop-network-management-agent): AI-based Network Management Agent (NMA): Concepts and Architecture
* [draft-zhao-ccamp-actn-optical-network-agent](https://datatracker.ietf.org/doc/draft-zhao-ccamp-actn-optical-network-agent): Integration of Network Management Agent (NMA) into ACTN-Based Optical Network
* [draft-cgfabk-nmrg-ibn-generative-ai](https://datatracker.ietf.org/doc/draft-cgfabk-nmrg-ibn-generative-ai): Generative AI for Intent-Based Networking
* [draft-xu-nmrg-idp-framework](https://datatracker.ietf.org/doc/draft-xu-nmrg-idp-framework): Intelligent Data Plane (IDP): Framework and Protocol Considerations
* [draft-chen-nmrg-multi-provider-inference-api](https://datatracker.ietf.org/doc/draft-chen-nmrg-multi-provider-inference-api): Multi-Provider Extensions for Agentic AI Inference APIs
* [draft-yang-nmrg-mcp-nm](https://datatracker.ietf.org/doc/draft-yang-nmrg-mcp-nm): Applicability of MCP for the Network Management
* [draft-yang-nmrg-a2a-nm](https://datatracker.ietf.org/doc/draft-yang-nmrg-a2a-nm): Applicability of A2A to the Network Management
* [draft-bernardos-nmrg-agentic-network-optimization](https://datatracker.ietf.org/doc/draft-bernardos-nmrg-agentic-network-optimization): Solutions for enabling agentic sensing with network optimization
* [draft-yan-nmrg-cross-domain-agent-architecture](https://datatracker.ietf.org/doc/draft-yan-nmrg-cross-domain-agent-architecture/):Cross-Domain Network Agent Architecture for Autonomous Operations

#### Research Topics
* [draft-irtf-nmrg-ai-challenges](https://datatracker.ietf.org/doc/draft-irtf-nmrg-ai-challenges): Research Challenges in Coupling Artificial Intelligence and Network Management
* [draft-irtf-nmrg-ai-deploy](https://datatracker.ietf.org/doc/draft-irtf-nmrg-ai-deploy): Considerations of network/system for AI services
* [draft-irtf-nmrg-ibn-usecases](https://datatracker.ietf.org/doc/draft-irtf-nmrg-ibn-usecases): Use Cases and Practices for Intent-Based Networking
* [draft-cxxx-nmrg-ai4ibn](https://datatracker.ietf.org/doc/draft-cxxx-nmrg-ai4ibn/):Agentic AI for Intent-Based Networking
* [draft-janz-nmrg-inter-agent-conflict-resolution](https://datatracker.ietf.org/doc/draft-janz-nmrg-inter-agent-conflict-resolution): Sources of Inter-Agent Conflicts and Approaches to Conflict
  Resolution in  Network Management
* [draft-janz-nmrg-naas-agentic-negotiation](https://datatracker.ietf.org/doc/draft-janz-nmrg-naas-agentic-negotiation): Dynamic Network-as-a-Service Life-Cycle Automation Using End-to-End Agent Negotiation
* [draft-janz-nmrg-ontology-reconciliation](https://datatracker.ietf.org/doc/draft-janz-nmrg-ontology-reconciliation):  Describes a possible direction for inter-system
* [draft-wmz-nmrg-agent-ndt-arch](https://datatracker.ietf.org/doc/draft-wmz-nmrg-agent-ndt-arch): Network Digital Twin and Agentic AI-based Architecture for AI-driven Network Operations
* [draft-hong-nmrg-agenticai-ps](https://datatracker.ietf.org/doc/draft-hong-nmrg-agenticai-ps): Motivations and Problem Statement of Agentic AI for network management
* [draft-jadoon-nmrg-agentic-ai-autonomous-networks](https://datatracker.ietf.org/doc/draft-jadoon-nmrg-agentic-ai-autonomous-networks): Agentic AI Architectural Principles for Autonomous Computer Networks
* [draft-april-cmie-research-problem](https://datatracker.ietf.org/doc/draft-april-cmie-research-problem): Constrained Manifold Inference Engine (CMIE): A Research Problem for Deterministic AI-Network Resilience
* [draft-pedro-nmrg-ai-framework](https://datatracker.ietf.org/doc/draft-pedro-nmrg-ai-framework): Artificial Intelligence Framework for Network Management
* [draft-irtf-nmrg-llm-nm](https://datatracker.ietf.org/doc/draft-irtf-nmrg-llm-nm): A Framework for LLM-Assisted Network Management with Human-in-the-Loop
* [draft-zhao-nmrg-ai-agent-for-ndt](https://datatracker.ietf.org/doc/draft-zhao-nmrg-ai-agent-for-ndt): AI Agent Architecture for Network Digital Twin
* [draft-feng-nmrg-ain-architecture](https://datatracker.ietf.org/doc/draft-feng-nmrg-ain-architecture): Agentic Intent Network (AIN) Architecture
* [draft-feng-nmrg-ain-deployment](https://datatracker.ietf.org/doc/draft-feng-nmrg-ain-deployment): Agentic Intent Network (AIN): Applicability and Deployment Scenarios

### LLM/AI Benchmarking (OPS)

#### AI for Networking
##### Terminology

 * [draft-gaikwad-llm-benchmarking-terminology](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-terminology/)

##### Methodology

  * [draft-gaikwad-llm-benchmarking-methodology](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-methodology/)
  * [draft-contreras-bmwg-ai-agent-benchmarking](https://datatracker.ietf.org/doc/draft-contreras-bmwg-ai-agent-benchmarking/)
  * [draft-han-bmwg-agent-security-benchmark] (https://datatracker.ietf.org/doc/draft-han-bmwg-agent-security-benchmark/)

##### Profiles: SUT boundary definitions for model engines, AI firewall, AI gateways, etc.

  * [draft-gaikwad-llm-benchmarking-profiles](https://datatracker.ietf.org/doc/draft-gaikwad-llm-benchmarking-profiles/)
  * [draft-mondal-llm-serving-workload-profiles](https://datatracker.ietf.org/doc/draft-mondal-llm-serving-workload-profiles/)

#### Network for AI
#### Terminology

 * [draft-calabria-bmwg-ai-fabric-terminology/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-terminology/)
     
#### Methodology

  * [draft-calabria-bmwg-ai-fabric-training-bench/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-training-bench/)
  * [draft-calabria-bmwg-ai-fabric-inference-bench/](https://datatracker.ietf.org/doc/draft-calabria-bmwg-ai-fabric-inference-bench/)
  * [draft-cui-nmrg-auto-test](https://datatracker.ietf.org/doc/draft-cui-nmop-auto-test): Framework and Automation Levels for AI-Assisted Network Protocol Testing

### Discovery & Naming (Discussion in DAWN)

* Detailed [list](https://github.com/danielkinguk/discovery/blob/main/solutions-list.md)

### Transport

* [draft-mpsb-agntcy-messaging](https://datatracker.ietf.org/doc/draft-mpsb-agntcy-messaging): An Overview of Messaging Systems and Their Applicability to Agentic AI
* [draft-liu-agent-protocol-over-moq](https://datatracker.ietf.org/doc/draft-liu-agent-protocol-over-moq): Agent Protocol over MoQ
* [draft-nandakumar-ai-agent-moq-transport](https://datatracker.ietf.org/doc/draft-nandakumar-ai-agent-moq-transport): MoQ Transport for Agent Protocols
* [draft-jennings-ai-mcp-over-moq](https://datatracker.ietf.org/doc/draft-jennings-ai-mcp-over-moq): Model Context Protocol and Agent Skills over Media over QUIC Transport
* [draft-wang-lisp-ai-agent](https://datatracker.ietf.org/doc/draft-wang-lisp-ai-agent): Using LISP as a Network Substrate for AI Agent Communication
* [draft-mpsb-agntcy-slim](https://datatracker.ietf.org/doc/draft-mpsb-agntcy-slim):Secure Low-Latency Interactive Messaging (SLIM)
* [draft-ietf-slim-use-cases](https://datatracker.ietf.org/doc/draft-ietf-slim-use-cases):SLIM Use Cases

### Security (including Authentication & Authorization)

* [draft-klrc-aiagent-auth](https://datatracker.ietf.org/doc/draft-klrc-aiagent-auth): AI Agent Authentication and Authorization
* [draft-mishra-oauth-agent-grants](https://datatracker.ietf.org/doc/draft-mishra-oauth-agent-grants): Delegated Agent Authorization Protocol (DAAP)
* [draft-song-oauth-ai-agent-collaborate-authz](https://datatracker.ietf.org/doc/draft-song-oauth-ai-agent-collaborate-authz): OAuth2.0 Extension for Multi-AI Agent Collaboration
* [draft-liu-agent-operation-authorization](https://datatracker.ietf.org/doc/draft-liu-agent-operation-authorization): Agent Operation Authorization
* [draft-chen-oauth-scope-agent-extensions](https://datatracker.ietf.org/doc/draft-chen-oauth-scope-agent-extensions): Structured and Constraint Extensions for OAuth Scopes
* [draft-barney-caam](https://datatracker.ietf.org/doc/draft-barney-caam): Contextual Agent Authorization Mesh (CAAM)
* [draft-sarischo-6gip-aiml-security-privacy](https://datatracker.ietf.org/doc/draft-sarischo-6gip-aiml-security-privacy): Security and Privacy Implications of 3GPP AI/ML Services for 6G
* [draft-birkholz-verifiable-agent-conversations](https://datatracker.ietf.org/doc/draft-birkholz-verifiable-agent-conversations): Verifiable Agent Conversation Records
* [draft-bondar-wca](https://datatracker.ietf.org/doc/draft-bondar-wca): Warrant Certificate Authorities (WCA): Auditable Data Provenance for AI-Agent Tool-Call Chains
* [draft-ni-wimse-ai-agent-identity](https://datatracker.ietf.org/doc/draft-ni-wimse-ai-agent-identity): WIMSE Applicability for AI Agents

### Observability, Intervention and Control
* [draft-wnd-opsawg-icon-ps](https://datatracker.ietf.org/doc/draft-wnd-opsawg-icon-ps/): Problem Statement for Observability, Intervention and Control (I&C) in Multi-Agent Autonomous Networks
* [draft-mcw-opsawg-icon-requirements](https://datatracker.ietf.org/doc/draft-mcw-opsawg-icon-requirements/)): Architecture and Requirements for Observability, Control and Intervention of Network Management Agents
* [draft-sato-soos-hem](https://datatracker.ietf.org/doc/draft-sato-soos-hem): The Human Escalation Mechanism (HEM) for Agentic AI Systems
* [draft-sato-soos-pt](https://datatracker.ietf.org/doc/draft-sato-soos-pt): Progressive Trust (PT) for Agentic AI Governance Systems
* [draft-sato-soos-mad](https://datatracker.ietf.org/doc/draft-sato-soos-mad/): Multi-Agent Delegation in Sovereign Object Systems
* [draft-sato-soos-cap-rrs](https://datatracker.ietf.org/doc/draft-sato-soos-cap-rrs/): Constitutional AI Protocol -- Regulation Record Specification (CAP-RRS)
* [draft-sato-soos-cap](https://datatracker.ietf.org/doc/draft-sato-soos-cap/):  The Constitutional AI Protocol (CAP) for Agentic AI Systems
* [draft-sato-soos-faip](https://datatracker.ietf.org/doc/draft-sato-soos-faip/): The Federated Agent Intelligence Protocol (FAIP) for Agentic AI Systems
* [draft-sato-soos-aep](https://datatracker.ietf.org/doc/draft-sato-soos-aep/): The Agent Execution Protocol (AEP) for Agentic AI Systems
* [draft-sato-soos-gar](https://datatracker.ietf.org/doc/draft-sato-soos-gar/): The Governance Audit Record (GAR) for Agentic AI Systems
* [draft-sato-soos-mjwt](https://datatracker.ietf.org/doc/draft-sato-soos-mjwt/) The Mandate JWT (MJWT) for Agentic AI Systems
* [draft-sato-soos-sov](https://datatracker.ietf.org/doc/draft-sato-soos-sov/):  The Sovereign Object (SOV) for Agentic AI Systems
* [draft-sato-soos-idp](https://datatracker.ietf.org/doc/draft-sato-soos-idp/): The Intent Declaration Primitive (IDP) for Agentic AI Systems


### Inter-Agent Communication ( Discussion in AgentProto BOF)

* [draft-hw-protocol-agent](https://datatracker.ietf.org/doc/draft-hw-protocol-agent): AI Agent Protocols for Multi-modality
* [draft-yao-catalist-problem-space-analysis](https://datatracker.ietf.org/doc/draft-yao-catalist-problem-space-analysis): Problem Space Analysis of AI Agent Protocols in IETF
* [draft-yc-ipv6-for-ioa](https://datatracker.ietf.org/doc/draft-yc-ipv6-for-ioa): Capabilities and Future Requirements of IPv6 for the Internet of Agents (IoA)
* [draft-cowles-aocl](https://datatracker.ietf.org/doc/draft-cowles-aocl): Agent Orchestration Control Layers (AOCL) Protocol
* [draft-cowles-aee](https://datatracker.ietf.org/doc/draft-cowles-aee): Agent Envelope Exchange (AEE): A Minimal JSON Envelope Format for Inter-Agent Communication
* [draft-ni-a2a-ai-agent-security-requirements](https://datatracker.ietf.org/doc/draft-ni-a2a-ai-agent-security-requirements): Security Requirements for AI Agents
* [draft-li-dmsc-macp](https://datatracker.ietf.org/doc/draft-li-dmsc-macp): Multi-agent Collaboration Protocol Suite
* [draft-zhang-dmsc-ioa-semantic-interaction](https://datatracker.ietf.org/doc/draft-zhang-dmsc-ioa-semantic-interaction): Ontology-based Semantic Interaction for Internet of Agents
* [draft-nennemann-wimse-ect](https://datatracker.ietf.org/doc/draft-nennemann-wimse-ect): Execution Context Tokens for Distributed Agentic Workflows
* [draft-song-dmsc-problem-statement](https://datatracker.ietf.org/doc/draft-song-dmsc-problem-statement): Problem Statement and Requirements for Dynamic Multi-agent Secured Collaboration (DMSC)
* [draft-scrm-aiproto-usecases](https://datatracker.ietf.org/doc/draft-scrm-aiproto-usecases): Agentic AI Use Cases

### Networking for AI / AIDC

* [draft-filsfils-srv6ops-srv6-ai-backend](https://datatracker.ietf.org/doc/draft-filsfils-srv6ops-srv6-ai-backend/): SRv6 for Deterministic Path Placement in AI Backends
* [draft-hu-rtgwg-cbfc-rsvp](https://datatracker.ietf.org/doc/draft-hu-rtgwg-cbfc-rsvp): Credit-based Flow Control Based on RSVP for RDMA transmission in WAN
* [draft-hcl-rtgwg-ai-network-problem](https://datatracker.ietf.org/doc/draft-hcl-rtgwg-ai-network-problem): Gap Analysis, Problem Statement, and Requirements in AI Networks
* [draft-hcl-rtgwg-osf-framework](https://datatracker.ietf.org/doc/draft-hcl-rtgwg-osf-framework): An OSF Framework for Artificial Intelligence (AI) Network
* [draft-cheng-rtgwg-ai-network-reliability-problem](https://datatracker.ietf.org/doc/draft-cheng-rtgwg-ai-network-reliability-problem): Reliability in AI Networks Gap Analysis, Problem Statement, and Requirements
* [draft-li-rtgwg-distributed-lossless-framework](https://datatracker.ietf.org/doc/draft-li-rtgwg-distributed-lossless-framework): Framework of Distributed AIDC Network
* [draft-du-catalist-routing-considerations](https://datatracker.ietf.org/doc/draft-du-catalist-routing-considerations): Routing Considerations in Agentic Network

### Misc

* [draft-dunbar-agent-attachment](https://datatracker.ietf.org/doc/draft-dunbar-agent-attachment): Agent Attachment Protocol
* [draft-chuyi-nmrg-agentic-network-inference](https://datatracker.ietf.org/doc/draft-chuyi-nmrg-agentic-network-inference): Agentic Network Architecture and Protocol for Supporting Agent Interconnection
  Communication and Multi-level Inference
* [draft-verma-dmsc-nlip-notes](https://datatracker.ietf.org/doc/draft-verma-dmsc-nlip-notes/): Use of Natural Language for Agent Communication
* [draft-prabhu-nmrg-prompt-schema-llm](https://datatracker.ietf.org/doc/draft-prabhu-nmrg-prompt-schema-llm/): Framework for Normalizing Multi-Vendor Network Inputs for LLM-Assisted Network Management

## Side Meetings

### IETF-126 (OPS)

* Monday 14:45~15:45
  Agent Authorization (Agent Security)
  Park Suite 4
 
* Monday 18:00~19:00
  Remote Attestation Challenges for AI Agent (Agent Security)
  Grand Klimt Hall3
 
* Tuesday 15:00~16:00
  Agentic AI Research Group 
  Park Suite 4
 
* Wednesday 8:00~9:30
  Agent Observability, Intervention and Control 
  Park Suite 4
 
* Wednesday 14:45~15:45
  AI Consumable Data model
  Park Suite 4
 
* Thursday 16:15~17:45
  Agent Operation
  Park Suite 4
 
* Thursday 17:00~19:00
  AAuth (Agent Security)
  Grand Klimt Hall3
 
* Friday 8:00~10:00
  AIOPS Scope and Charter Discussion
  Park Suite4

## Hackathons

### IETF-126 (OPS)

* **AI-based Network Management Agent (NMA)**
  Announcement: [NMOP] IETF 126 Hackathon - AI based Network Management Agent (NMA)
  Scope: Team plans to build concrete NMA agent demos for network domains such as OTN and SPN, and to explore standardisation of northbound interfaces to operator OSS/BSS systems.
  Expected output: A live demo of a single NMA agent integrating with SDN controllers for intent-based closed-loop automation.
  Links: [NMOP archive message](https://mailarchive.ietf.org/arch/msg/nmop/sft5m2slKjzMtdcT59xMCB1ZhE8/), [Draft: draft-zhao-nmop-network-management-agent](https://datatracker.ietf.org/doc/draft-zhao-nmop-network-management-agent/), [Hackathon repo notes](https://github.com/xingzhao92/draft-zhao-nmop-network-management-agent/ietf126-hackathon)

* **Security for Agent Communication**
  Goal:Test security tools and agent skills focused on three key areas: intent source validation, agent and tool identity, and heterogeneous credentials verification.
 
* **Security Evaluation Benchmark for AI Agents**
  Goal: A security evaluation benchmark for AI agents
  * Evaluating dimensions like algorithms, data, execution, third-party components, and evolution. Key metrics include adversarial, privacy, and jailbreak defenses, as well as plugin,
    skill and autonomous iteration security. 
  * Using static and dynamic testing, the framework assesses agents before, during, and after deployment. By scoring these metrics, it quantitatively evaluates the security posture,
    enabling direct capability comparisons and security grading across agents.

* **AI Agent observability for network management operations**
  Goal: AI Agent observability for network management operations
  * AI agent observability framework for network diagnosis AI agent Capture Operational metrics
  Key Applications: Agent Benchmarking, Agent Intervention Control

### IETF-125

* [Agent Communication Framework for Network AIOps](https://wiki.ietf.org/en/meeting/125/hackathon#agent-communication-framework-for-network-aiops)
* [LLM Driven Automated Network Protocol Testing](https://wiki.ietf.org/en/meeting/125/hackathon#llm-driven-automated-network-protocol-testing)
* [E2E SRv6 for AI service access with quality and security assurance](https://wiki.ietf.org/en/meeting/125/hackathon#e2e-srv6-for-ai-service-access-with-quality-and-security-assurance)
* [Knowledge Graph Enhanced Network Management](https://wiki.ietf.org/en/meeting/125/hackathon#knowledge-graph-enhanced-network-management)
* [Enhancing LLMs for Network Traffic Analysis (TrafficLLM)](https://wiki.ietf.org/en/meeting/125/hackathon#enhancing-llms-for-network-traffic-analysis-trafficllm)
* [Task Discovery in AI Network](https://wiki.ietf.org/en/meeting/125/hackathon#task-discovery-in-ai-network)

## Incoming IETF Liaison Statements

* **2026-05-21 | ITU-T FG-AINN to OPSAWG | For information**
  Subject: New Liaison Statement on completion of the FG-AINN WG1 draft deliverable, "Technical Specification - Vocabulary for Artificial Intelligence Native for Telecommunication Networks".
  Summary: ITU-T FG-AINN notified OPSAWG that WG1 completed draft deliverable output FG-AINN-O-023 at the seventh FG virtual meeting (5-7 May 2026). The deliverable defines common AI-native telecom terminology and is aligned with FG-AINN-O-024 (concepts, characteristics, and definitions). Release of the final version is planned for 30 November 2026.
  Links: [IETF mail archive message](https://mailarchive.ietf.org/arch/msg/opsawg/I9GIEkenPKNOW8xJZloI7q5Kvj8/), [Datatracker liaison page](https://datatracker.ietf.org/liaison/2159/)
  Attachments: [Standardization Gap Analysis of the FG-AINN](https://www.ietf.org/lib/dt/documents/LIAISON/liaison-2026-05-21-itu-t-opsawg-ls-on-completion-of-the-fg-ainn-wg1-draft-deliverable-technical-specification-vocabulary-for-artificial-intellige-attachment-1.docx), [Technical Specification - Vocabulary for Artificial Intelligence Native Telecommunication Networks (May 2026)](https://www.ietf.org/lib/dt/documents/LIAISON/liaison-2026-05-21-itu-t-opsawg-ls-on-completion-of-the-fg-ainn-wg1-draft-deliverable-technical-specification-vocabulary-for-artificial-intellige-attachment-2.docx)

## AI-related Mailing Lists

* [ainetops](https://mailman3.ietf.org/mailman3/lists/ainetops.ietf.org/)
* [dawn](https://mailman3.ietf.org/mailman3/lists/dawn.ietf.org/)
* [agent2agent](https://mailman3.ietf.org/mailman3/lists/agent2agent.ietf.org/)
* [ai-control](https://mailman3.ietf.org/mailman3/lists/ai-control.ietf.org/)
* [aidc](https://mailman3.ietf.org/mailman3/lists/aidc.ietf.org/)
* [pidloc](https://mailman3.ietf.org/mailman3/lists/pidloc.ietf.org/)
* [Multicast for AI](https://mailarchive.ietf.org/arch/browse/mcast4ai/)

## Further AINETOPS Reading

* [Building the networks that build AI](https://storage.googleapis.com/site-media-prod/meetings/NANOG96/5627/20260202_Conrad_From_Datacenter_To_v1.pdf): From Datacenter to AI Center
* [Beyond the Chip](https://storage.googleapis.com/site-media-prod/meetings/NANOG96/5612/20260202_Conrades_Keynote_Beyond_The_v1.pdf)
