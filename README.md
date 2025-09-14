# Integrating Agentic AI and LLMs with TOGAF in the Enterprise

#### These set of project demonstrates how an Agentic AI system — powered by OpenAI's GPT-4o LLM, OpenAI vector embeddings, Pinecone vector database, Google Cloud Storage, Azure Kubernetes Services, Azure CLI, Langchain, Streamlit, Prometheus, Grafana, Google Cloud Platform and n8n orchestration — can be effectively mapped to the TOGAF ADM (Architecture Development Method) to support intelligent automation within an enterprise context. 

#### Rather than viewing AI as an isolated capability, this implementation positions it as a modular, governable, and incrementally scalable architecture component that aligns directly with the enterprise TOGAF (Open Group Architecture Framework) principles.

<ins>Projects</ins>: 

* (I) Automating Complex Enterprise Business & Financial Decisions Using Agentic AI in n8n ( manuelbomi/Automating-Complex-Enterprise-Business-Financial-Decisions-Using-Agentic-AI-in-n8n )

* (2) Enterprise Agentic AI: Scalable Meeting Orchestration with n8n ( manuelbomi/Enterprise-Agentic-AI---Scalable-Meeting-Orchestration-with-n8n )

* (3) Agentic AI Workflow: Enterprise Data Integration Pipeline and Vector Storage with n8n ( manuelbomi/Agentic-AI-Workflow----Enterprise-Data-Integration-Pipeline-and-Vector-Storage-with-n8n )

* (4) Scalable Agentic AI System: Enterprise Data Orchestration & Event Coordination with n8n, Pinecone & OpenAI  ( https://github.com/manuelbomi/Scalable-Agentic-AI-System-Enterprise-Data-Orchestration-Event-Coordination-with-n8n-Pinecone-OpenAI )

* (5) An Enterprise Generative-AI LLM System for Manufacturing and Business Applications ( manuelbomi/An-Enterprise-Generative-AI-LLM-System-for-Manufacturing-and-Business-Applications- )
  
- Deployed implementation  of project 5 (on Azure Kubernetes Services & Namecheap): (https://app.emmanueloyekanluprojects.com) – Here , you can upload your own pdf files and then chat with the system
  
- Deployed implementation of project 5 (Prometheus & Grafana monitoring): https://grafana.emmanueloyekanluprojects.com/login 
  
* (6) An Enterprise LLM System for Healthcare Applications (manuelbomi/An-Enterprise-LLM-System-for-HealthCare-Applications)

---

## Phase A: Architecture Vision  🧭
#### The goal of the Agentic AI system is to advance the enterprise vision of real-time intelligent automation with autonomous AI Agents that learns from the environments and increases its intelligence and capabilities. 

#### By leveraging vector databases like Pinecone in combination with large language models (LLMs), the agent dynamically interacts with business knowledge and user context without requiring model retraining. 

#### This directly supports enterprise-level goals such as business agility, self-service intelligence, and lower time-to-decision. 

#### The n8n-based agentic and LLM workflow thus becomes a tangible proof-of-concept for broader enterprise AI adoption. In a nutshell, in these set of projects, in the architecture vision phase, we:

        ◦ Show how Agentic AI supports the vision of enterprise-wide intelligent automation by connecting business goals with AI capabilities.
		
        ◦ Example: Using Pinecone + LLMs in several contexts ensures real-time knowledge integration without retraining, aligning with “business agility” goals.

---

## Phase B: Business Architecture  🏛️ 
#### From a business perspective, the AI agent acts as an intelligent assistant capable of handling real workflows — such as enterprise data pipeline orchestration and event/meeting scheduling — using the enterprise data. 

#### It supports Retrieval-Augmented Generation (RAG) from the Pinecone vector store, allowing the reuse of internal documentation and knowledge assets across teams. 

#### This breaks down data silos and aligns with TOGAF's vision of reusable, shared capabilities. The agent is designed to be extensible — future versions could handle financial analysis, aid enterprise-wide troubleshooting and project assistance, or detailed customer interactions (as shown in project 5).  

#### In a nutshell, in the business architecture phase, across all the projects (1 – 6), we:

        ◦ Position the AI agent as a business enabler that can handle RAG workflows, event scheduling & management, or financial analysis.
		
        ◦ Emphasize enterprise data reuse: no silos, just embeddings across shared knowledge bases.

--- 

## Phase C: Information Systems Architecture  🧩 
#### Data Architecture is centered around Pinecone, which acts as a semantic memory layer for the enterprise. Embeddings are generated using OpenAI and stored in indexes (databases), enabling accurate retrieval and contextual understanding across workflows. 

#### On the Application Architecture side, the agent is decomposed into modular services: language models, memory buffers, vector tools, data storage APIs, and calendar interfaces. 

#### These nodes are reusable, low-code (except for projects 5 and 6 that was developed using VSCode); and loosely coupled. This workflows seamlessly aligns with TOGAF’s principles of service orientation and modularity. 

#### In a nutshell, in the information system architecture phase, we designed:

        ◦ Data Architecture → vector databases like Pinecone become the data backbone for semantic search and enterprise knowledge.
		
        ◦ Application Architecture → agent nodes (LLM, memory, tools) become modular “AI services” that plug into different enterprise workflows.
---

## Phase D: Technology Architecture  ☁️ 
#### The implementation is fully cloud-native, orchestrated within n8n, and designed to run in Docker, Kubernetes (AKS, EKS), or serverless environments. This ensures horizontal scalability, uptime, and operational reliability. 

#### The use of credentials management (for example in AKS Secrets/Vaults; as in project 5), logging, and reusable nodes supports enterprise-grade governance, monitoring, and security, which are essential components of a compliant technology stack. 

#### In a nutshell, in the technological architecture phase, we:

        ◦ We designed AI Agents to run on scalable, cloud-native platforms (e.g., n8n, Docker, AKS).
		
        ◦ This ensures elasticity, reliability, and governance at scale.
---

## Phase E: Opportunities & Solutions  🚀 
#### As shown here: tmanuelbomi/Designing-an-Enterprise-Agentic-AI-Scheduler-in-n8n  the Agentic AI system already integrates with Google Drive and Google Calendar to check availability and create events, showcasing seamless integration with enterprise productivity tools. This serves as a template for future integrations with enterprise ERP, CRM, or ticketing systems. 

#### We show how we can vary the design of the Agentic AI Scheduler to perform the function of an enterprise data pipeline orchestrator here: manuelbomi/Agentic-AI-Workflow----Enterprise-Data-Integration-Pipeline-and-Vector-Storage-with-n8n . 

#### With that solution, The Agentic AI system can automatically warehouse any enterprise data from any source into the Pinecone vector database. Hence, all enterprise data can be located in a single source of truth. 

#### We also used a slight variation of the base Agentic AI system for complex enterprise financial and business decision here: manuelbomi/Automating-Complex-Enterprise-Business-Financial-Decisions-Using-Agentic-AI-in-n8n    

#### We fully discussed how the base Agentic AI system can be scaled up for various other enterprise use cases here: manuelbomi/Enterprise-Agentic-AI---Scalable-Meeting-Orchestration-with-n8n   

#### All the above-mentioned projects are all low-code designs with n8n. The full code counterparts with variations of the same base agents for other use-cases such as for business/manufacturing and for healthcare applications are shown in projects 5 and 6.

#### The variations in use cases for the base Agentic AI system demonstrates how re-usability and scalability can be achieved for LLM and Agentic AI use cases in the enterprise domain. 

#### We also demonstrate how the system can be made to scale up with the number of users by deploying a variation of the system via the use on an Azure Kubernetes cluster (AKS) here: manuelbomi/An-Enterprise-Generative-AI-LLM-System-for-Manufacturing-and-Business-Applications-   

#### The system described in this instance was extended from the base Agentic AI system to include Langchain, and monitoring tools such as Prometheus and Grafana.

#### Interested readers can use the system to upload their own pdf files and chat with the system here: https://app.emmanueloyekanluprojects.com 

#### Each connected service can be viewed as a target capability within the enterprise portfolio — one that automates manual tasks, improves user experience, and maintains compliance. In a nutshell, in the opportunities and solution phase, we:

        ◦ Demonstrate integration with existing enterprise apps like Google Drive, Google Calendar, and how to scale up by integrating ERP systems, CRM and other enterprise systems.
		
        ◦ Use the same base Agentic AI system for complex financial/business decision
		
        ◦ Show how it reduces manual effort while ensuring compliance.
	
