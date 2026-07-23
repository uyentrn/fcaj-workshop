---
title: "Event 1"
date: 2026-07-31
weight: 1
chapter: false
pre: " <b> 4.1. </b> "
---

# Summary Report: “AWS Cloud & AI Mastery Workshop”

### Event Purpose

- Systematically organize comprehensive knowledge on Cloud infrastructure, security, modern software development workflows, and AI/ML applications within the AWS ecosystem.
- Discuss and analyze real-world engineering problems through 6 in-depth topics presented by speakers and students.
- Share career development roadmaps, soft skills, and personal growth methodologies in the Cloud & DevOps domain.
- Connect the academic community with project execution: Create a collaborative networking space for students, domain experts, and engineers from leading enterprises.

### List of Speakers

- **Lê Hoàng Gia Đại** (Final-year student at HUTECH University) — WAF + ML for Cyber Attack Detection.
- **Bao Huynh** (Junior Cloud Native Developer - Endava Vietnam, Founder / Head Lab - ITea Lab) — Docker – A containerization technology.
- **Trần Trung Vinh** (System Administrator at Central Retail Group) — From IT Helpdesk to Senior Sysadmin.
- **Nguyễn Quốc Bảo** — Multiplayer in the Cloud: Connecting Godot Clients with AWS WebSockets.
- **Trương Huy Phước** — The Art of Effective Teamwork.
- **Việt Phát** (AI majoring at Swinburne University of Technology) — Build GraphRAG applications using Amazon Bedrock and Amazon Neptune.

### Key Highlights

#### WAF + Machine Learning for Cyber Attack Detection

- Limitations of traditional WAFs: Static rule-based systems struggle against Zero-day vulnerabilities, hybrid/spoofing attacks, and unprecedented anomalous behaviors.
- ML-based NIDS solution: Utilizes the CSE-CIC-IDS2018 dataset to train Machine Learning models (specifically LightGBM for superior accuracy) to perform real-time network traffic analysis.
- AWS Infrastructure Integration: Combines AWS WAF, EC2, Lambda, S3, Kinesis Data Firehose, CloudWatch, and Security Hub to automate threat detection and alerting.

#### Containerization Technology with Docker

- **Virtualization vs. Containerization Comparison:**
  * Virtual Machines (VMs) are resource-intensive because each runs its own Guest OS, resulting in slow boot times.
  * Containers share the Host OS via the Docker Engine, boot in milliseconds, feature lightweight footprints, and run consistently across all environments.

- **Core Architecture & Key Commands:**
  * Layered Image model in Dockerfiles (each instruction creates a cached layer).
  * Essential CLI command groups controlling the lifecycle of Containers, Networks, Volumes, and Docker Compose.

- **Practical Use Cases:**
  * Integration into CI/CD pipelines, Microservices architectures, dev/test environments, and legacy application modernization.

#### Career Roadmap: From Helpdesk to Senior Sysadmin / Cloud DevOps

- **System Operations Mindset:**
  * **Prevent first — fix later:** Automate repetitive tasks, maintain thorough documentation/runbooks, and deploy monitoring prior to incidents occurring.
  * **Core Principle:** "Never test in production" to safeguard system reliability and availability.
- **Transformation Roadmap:** Master Linux & Networking $\rightarrow$ Build hands-on labs $\rightarrow$ Adopt Cloud Mindset (AWS, Elastic Scaling) $\rightarrow$ Infrastructure as Code (Terraform) $\rightarrow$ DevOps Culture (CI/CD, Docker).
- **Interview & Career Lessons:** Preparation grounded in real-world experience (portfolios and projects) carries significantly more weight than certifications alone.

#### Cloud Multiplayer Gaming with AWS WebSockets & Godot

- **Game Network Architecture Selection:** Comparison between UDP/ENet (low latency for FPS), HTTP Polling (simple but high latency), and WebSockets (full-duplex messaging, ideal for turn-based games, chat, and lobbies).
- **AWS Serverless Infrastructure:** Integrates Godot Clients with API Gateway WebSocket, AWS Lambda (handling connection and matchmaking logic), and Amazon DynamoDB (storing connection IDs and room states).
- **Challenges & Mitigations:** Handling `GoneException` issues (abrupt disconnections), optimizing DynamoDB Scan operation costs, and transitioning from Stateless Lambda to AWS GameLift when dedicated servers are required.

#### The Art of Effective Teamwork

- **4 Golden Rules:**
  1. Clear & Shared Goals: Explicit objectives and mutual alignment.
  2. Right Person, Right Place: Effective task delegation based on individual strengths.
  3. Open Communication & Active Listening: Empathetic listening and transparent discussions.
  4. Personal Accountability: High level of individual responsibility.
- **Digital Tool Adoption:** Leveraging Trello, ClickUp (project management), Google Workspace, Slack, and Discord to maximize team productivity.

#### Building GraphRAG Applications with Amazon Bedrock & Neptune

- **Limitations of Traditional RAG:** Inefficiencies when answering queries requiring multi-hop reasoning.
- **The Power of GraphRAG:** Utilizes Knowledge Graphs to explicitly model relationships between entities via edges.
- **Two AWS Deployment Approaches:**
  * **Fully Managed Route:** Uses Amazon Bedrock Knowledge Bases (text chunking, entity extraction) integrated with Amazon Neptune Analytics (graph storage and graph search).
  * **Custom Route:** Builds custom pipelines using LlamaIndex with Amazon Neptune for flexible Cypher query execution.

### Key Takeaways

#### Design Mindset

- **Operations & Security Mindset:** Shift from reactive incident management to proactive prevention. Understand that application security cannot rely solely on static WAF rules but requires integration with ML and automated monitoring.
- **Building Core Capabilities:** Deepen 1–2 foundational skills (Linux, Networking) before scaling out to advanced Cloud/DevOps technologies. Prioritize real-world project experience over accumulating certifications.
- **Business & User Impact:** Whether building infrastructure, games, or AI applications, the ultimate goal remains optimizing cost, performance, and user experience.

#### Technical Architecture

- **Containerization & Deployment:** Master application packaging with Docker and optimize image layers to maintain environment parity from Development to Production.
- **Serverless Real-Time Architecture:** Understand real-time application development via WebSockets and manage asynchronous disconnection states using AWS Lambda and DynamoDB.
- **GraphRAG Architecture:** Overcome traditional RAG boundaries by unifying Knowledge Graphs and LLMs on Amazon Bedrock & Neptune infrastructure.

#### Practical Application to Projects

- **Optimizing Development Workflows:** Integrate Docker into current projects to standardize developer environments and eliminate "works on my machine" issues.
- **Serverless Implementation:** Apply the API Gateway + Lambda + DynamoDB pattern to web/app projects requiring real-time features or lightweight event handling.
- **Adopting DevOps Culture & IaC:** Write automation scripts for configuration management and provision infrastructure resources using code (Infrastructure as Code) instead of manual configurations.
- **Enhancing Team Collaboration:** Establish clear task delegation rules, maintain transparent communication via Slack/Discord, and set well-defined team goals.

### Event Experience

Attending the **“AWS Cloud & AI Mastery Workshop”** was a highly rewarding experience. It provided a well-rounded perspective spanning infrastructure theory, container technology, software architecture, advanced AI, and practical career development insights.

#### Learning from High-Caliber Speakers
- Gained authentic career insights from Mr. Trần Trung Vinh on his transition from Helpdesk to Sysadmin, Cloud Native engineering experiences from Mr. Bao Huynh, as well as creative technical implementations presented by Gia Đại, Quốc Bảo, and Việt Phát.

#### Hands-On Technical Experience
- Observed live technical demonstrations, including real-time matchmaking with Godot and DynamoDB, attack classification models using LightGBM, and Docker Image layer structures.

#### Networking & Exchange
- The workshop provided a valuable opportunity to engage directly with industry seniors and peers.

#### Lessons Learned
- Career growth and digital transformation require persistence: every incremental step (from mastering Linux and writing Dockerfiles to configuring CI/CD pipelines) builds a solid technical foundation.
- Combining infrastructure knowledge (Cloud/DevOps), application programming paradigms (Serverless/WebSockets), and AI techniques (GraphRAG) creates a strong competitive advantage for the future.

#### Event Photos
* Insert your photos here

```